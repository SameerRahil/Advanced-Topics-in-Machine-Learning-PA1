Modern vision models show different inductive
biases that shape what they learn and how they
generalize. We dissect these biases across three
paradigms: discriminative (ResNet-50 vs. ViT-
S/16), generative (VAE vs. GAN), and contrastive
(CLIP ViT-B/32), using lightweight datasets
and controlled perturbations to probe semantic
(shape/texture/colour) and architectural (locality,
positional sensitivity) assumptions. For discrimi-
native models, we benchmark in-distribution per-
formance and test with grayscale, stylization and
cue-conflict, translations, patch shuffling, occlu-
sion, and a PACS domain shift, quantifying shape
bias and consistency under perturbations. For
generative models, we compare fidelity vs. diver-
sity, latent continuity (interpolations), and OOD
(out of distribution) behavior (reconstruction error
and extrapolative failures), linking outcomes to
training objectives. For CLIP, we study zero-shot
classification, image - text retrieval, representa-
tion geometry, and robustness across styles to
assess multimodal, semantic priors. Synthesizing
findings across tasks, we relate which biases (e.g
shape orientation, global context) most improve
OOD robustness, when architectural priors help
or hurt, and how data/objective choices modulate
these effects, offering practical guidance for bias-
aware model selection and training. We find that
CNNs heavily rely on textures, whereas ViTs and
CLIP are more shape/semantic oriented, leading
to better robustness on distribution shifts. VAEs
vs GANs trade off diversity and fidelity due to
their training biases. Our results highlight that incorporating human-aligned inductive biases (either via architecture or training data) can improve
OOD generalization.


Thank you Dr. Tahir, Associate Professor at the EE Department at Lahore University of Management Sciences, Lahore, Pakistan, and the TAs for their guidance, namely Abdullah Bin Faisal and Haseeb Tahir.
