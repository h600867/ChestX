Project:

![image](https://github.com/h600867/ChestX/assets/89257486/3113b263-6c99-4704-b4b8-5d4d506089d8)

According to Cem Dilegmani[1] X-rays are the most common form of medical imagery in the world.
3.6 billion images are taken each year and 45% of radiologist report suffering from burnout due to volume of scans and time preassure.
AI can therefore be a great timesaver in analysing x-rays and reducing workload for radiologist, helping lower burnout and allowing for more time for patients who need it.

AI can also be of help in developing countries where there are problems with shortages of radiologists. With the help of ai diseases can be identified through x-ray photos
without radiologists helping treat patients in areas suffering from resource constraints.



[1] https://research.aimultiple.com/xray-ai/

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
