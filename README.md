# MedGAN
 Optimized Generative Adversarial Network with Graph Convolutional Networks for Novel Molecule Design

## Instructions

### ZINC15 dataset
- two subsets of ZINC15 data
- 1 million random molecules stored in archive folder comptacted in chunks of 100,000

### 1. MedGAN_WGAN-GP
- Create a `logs` folder for TensorBoard metrics (one for each model).
- Create a `training_checkpoints` directory to store each training step (one for each model).
- Create a `training_model` directory to store the model saved after training (one for each model).
- Create summaries for the generator and discriminator in both `.txt` and `.png` formats (one for each model).

### 2. MedGAN_generator
- Generate molecules for each model.
- Compute model performance metrics.

### 3. MedGAN_drug-likeness_analysis
- Use the toxicity prediction model to make predictions on the generated molecules.
- Utilize `sascorer.py` to apply the Erl algorithm on synthetic accessibility.
- Calculate Lipinski's Rule of Five for the generated molecules.
