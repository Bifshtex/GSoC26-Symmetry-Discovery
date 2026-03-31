# GSoC 2026: Semi-supervised Symmetry Discovery

This repository contains the test tasks for the ML4SCI project "Semi-supervised Symmetry Discovery".

## Project Overview
The goal is to discover hidden physical symmetries in CMS data using representation learning.

## Implementation Plan
1. **VAE Training**: Building a Variational Autoencoder to create a latent space from rotated MNIST samples (0-360 degrees in 30-degree steps).
2. **Symmetry Mapping**: Using an MLP in the latent space to learn transformation operators that preserve physical logits.
3. **Semi-supervised Extension**: Applying the methodology to raw CMS calorimetric data to identify hidden invariants.

*Status: In active development. Code updates will follow.*
