1st MedGAN_WGAN-GP
	- create logs folder for tensorboard metrics
	- create training_checkpoints to store each training step
	- create training_model to store the model saved after training
	- create generator and discriminator summary in txt and png
2nd MedGAN_generator
	- create generated molecules for each model
	- compute model performance metrics
3rd MedGAN_drug-likeness_analysis
	- uses toxicity prediction model to make predictions on the generated molecules
	- uses sascorer.py to apply Erl algorithm on synthetic accessibility
	- calculates lipinsky rule of 5