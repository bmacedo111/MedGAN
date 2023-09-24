# MedGAN
 Optimized Generative Adversarial Network with Graph Convolutional Networks for Novel Molecule Design

## Instructions

### 1. MedGAN_WGAN-GP
- Create a `logs` folder for TensorBoard metrics.
- Create a `training_checkpoints` directory to store each training step.
- Create a `training_model` directory to store the model saved after training.
- Create summaries for the generator and discriminator in both `.txt` and `.png` formats.

### 2. MedGAN_generator
- Generate molecules for each model.
- Compute model performance metrics.

### 3. MedGAN_drug-likeness_analysis
- Use the toxicity prediction model to make predictions on the generated molecules.
- Utilize `sascorer.py` to apply the Erl algorithm on synthetic accessibility.
- Calculate Lipinski's Rule of Five for the generated molecules.
