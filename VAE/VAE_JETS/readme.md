Here is the current progress on the Variational Autoencoder (VAE) applied to Quark-Gluon Jet images.
For this implementation, we adapted the base architecture from the Cats vs. Dogs model, introducing minor modifications. The primary changes focus on the metrics used to evaluate the network's performance. In addition to the standard loss functions—Binary Cross-Entropy (BCE) and Kullback-Leibler Divergence (KLD)—we have included the following evaluation metrics:
- Wasserstein-1 Distance
- RDF (Radial Distribution Function)
- SSIM (Structural Similarity Index Measure)
