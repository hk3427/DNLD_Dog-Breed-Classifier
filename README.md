Project Overview

Welcome to the Convolutional Neural Networks (CNN) project in the AI Nanodegree! In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

Sample Output

Along with exploring state-of-the-art CNN models for classification, you will make important design decisions about the user experience for your app. Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer. Your imperfect solution will nonetheless create a fun user experience!

Project Instructions

Instructions

Clone the repository and navigate to the downloaded folder.

	git clone https://github.com/udacity/dog-project.git
	cd dog-project
Download the dog dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages.

Download the human dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.

Donwload the VGG-16 bottleneck features for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

Obtain the necessary Python packages, and switch Keras backend to Tensorflow.

For Mac/OSX:

	conda env create -f requirements/aind-dog-mac.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
For Linux:

	conda env create -f requirements/aind-dog-linux.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
For Windows:

	conda env create -f requirements/aind-dog-windows.yml
	activate aind-dog
	set KERAS_BACKEND=tensorflow
	python -c "from keras import backend"
Open the notebook and follow the instructions.

	jupyter notebook dog_app.ipynb
NOTE: While some code has already been implemented to get you started, you will need to implement additional functionality to successfully answer all of the questions included in the notebook. Unless requested, do not modify code that has already been included.

Amazon Web Services

Instead of training your model on a local CPU (or GPU), you could use Amazon Web Services to launch an EC2 GPU instance. Please refer to the Udacity instructions for setting up a GPU instance for this project.

Evaluation

Your project will be reviewed by a Udacity reviewer against the CNN project rubric. Review this rubric thoroughly, and self-evaluate your project before submission. All criteria found in the rubric must meet specifications for you to pass.

Project Submission

When you are ready to submit your project, collect the following files and compress them into a single archive for upload:

The dog_app.ipynb file with fully functional code, all code cells executed and displaying output, and all questions answered.
An HTML or PDF export of the project notebook with the name report.html or report.pdf.
Any additional images used for the project that were not supplied to you for the project. Please do not include the project data sets in the dogImages/ or lfw/ folders. Likewise, please do not include the bottleneck_features/ folder.
Alternatively, your submission could consist of the GitHub link to your repository.

