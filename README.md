Project:

![image](https://github.com/h600867/ChestX/assets/89257486/3113b263-6c99-4704-b4b8-5d4d506089d8)

According to Cem Dilegmani[1] X-rays are the most common form of medical imagery in the world.
3.6 billion images are taken each year and 45% of radiologist report suffering from burnout due to volume of scans and time preassure.
AI can therefore be a great timesaver in analysing x-rays and reducing workload for radiologist, helping lower burnout and allowing for more time for patients who need it.

AI can also be of help in developing countries where there are problems with shortages of radiologists. With the help of ai diseases can be identified through x-ray photos
without radiologists helping treat patients in areas suffering from resource constraints.

The accuracy of diagnoses can also be improved. It has been shown that AI can help catch diseases more accurately. For instance AI has been proved to increase accuracy in detecting lung cancer[2]. This improved accuracy in identifying diseases can be crucial in saving many lives all over the world.

[1] https://research.aimultiple.com/xray-ai/

[2] https://www.diagnosticimaging.com/view/chest-x-rays-with-artificial-intelligence-catches-more-lung-cancer

Explainable AI:

Explainable AI is a set of processes and methods to help humans understand and trust the output of AIs.
It helps clarify how AI models make decisions, which is important for accountability, regulatory compliance, and improving user confidence.

Explainable AI uses three main methods:

Prediction Accuracy: Accuracy is key in the success of the use of AI. By running simulations and comparing the output to the results in the training data set, the prediction accuracy can be determined.

Traceability: Traceability refers to the ability to trace and understand the decision-making process of AI models. This includes identifying how inputs are transformed through the model's layers and how they contribute to the final decision.

Decision Understanding: Many people distrust in AI, but to work with it efficiently, we need to learn to trust it. This is accomplished by educating the team working with the AI so they can understand how and why the AI makes decisions

Explainable AI is important in healthcare. To be used effectively the transparency and tracability in the decision-making process is crucial for people to have trust in the help AI tools can provide

https://www.ibm.com/topics/explainable-ai

In my project i have included a confusion matrix to show the performance of the model on the diseases it is trained for and a heatmap function to highlight what part of the image the AI is looking at to identify the disease. This i feel can especially be helpfull for radiologists in streamlining their analysis of x-ray photos.

To run on your computer:

Make sure you have python and Jupyter notebooks installed on your computer:
If you don't install miniconda https://docs.anaconda.com/free/miniconda/miniconda-other-installer-links/

Once miniconda is installed open the miniconda terminal and create a new enviroment with
conda "create -n jupyter-env jupyter" and proceed.

activate your enviroment with "conda activate jupyter-env" and type " jupyter notebook &"

if you struggle here is a tutorial link: https://www.youtube.com/watch?v=DKiI6NfSIe8

To download this notebook download the raw ChestX.ipynb(top right when you open the file). Open jupyter notebook and click the upload butten in the top right.
Navigate to where you downloaded the file and select it from your files. 

You will also need to download the dataset from Mendeley(https://data.mendeley.com/datasets/jctsfj2sfn/1).
Download and extract it to a location of your choice. Once you have it downloaded make sure to change the path variable in the project to the location of where you extracted the dataset.

Once this is done you should be able to run the notebook from your computer. Once the model is trained make sure to upload an image before running the following kernels.
