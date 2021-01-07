# Devops_Automates_ML

## Tech Stack 

Machine Learning | Developer Operations | Docker | Jenkins | Github |
 | :---: | :---: | :---: | :---: | :---: | 



<pre>
<img src="https://github.com/Aasthajain123/Devops_Automates_ML/blob/main/Mlops_Project_Images/001.png" width="500"> <img src="https://github.com/Aasthajain123/Devops_Automates_ML/blob/main/Mlops_Project_Images/006.jpg" width="350"></pre>

Why 50% of the Machine Learning Projects Are Never Implemented ?
Machine learning operations (MLOps) is the use of machine learning models by development/operations (DevOps) teams. MLOps seeks to add discipline to the development and deployment of machine learning models by defining processes to make ML development more reliable and productive.In the past years many organisations invested in AI/Machine Learning experiments, most of them were not deployed to production.To push a successful AI/ML experiment to production the organisation need to understand about MLOps.
## Create a container image that has Python3, tensorflow, Keras, Pandas, Sci-kit Learn and NumPy installed using Dockerfile.

# Images
<pre>
<img src="https://github.com/Aasthajain123/Devops_Automates_ML/blob/main/Mlops_Project_Images/002.jpg" width="215"> <img src="https://github.com/Aasthajain123/Devops_Automates_ML/blob/main/Mlops_Project_Images/003.jpg" width="215"> <img src="https://github.com/Aasthajain123/Devops_Automates_ML/blob/main/Mlops_Project_Images/004.png" width="215"> <img src="https://github.com/Aasthajain123/Devops_Automates_ML/blob/main/Mlops_Project_Images/005.jpg" width="215">
</pre>

## When we launch this image, It should automatically start training the model in the container.

## Create a Job chain of job1, job2, job3, job4 and job5 using build pipeline plugin in Jenkins

## Job1: Pull the Github repo automatically when some developers push the repo to Github.

## Job2: By looking at the code or program file, Jenkins should automatically start the respective machine learning software installed interpreter install image container to deploy code and start training( eg. If code uses CNN, then Jenkins should start the container that has already installed all the software required for the CNN processing).

## Job3: Train your model and predict accuracy or metrics.

## Job4: If metrics accuracy is less than 99%{Desired Accuracy}, then tweak the machine learning model architecture.

## Job5: Retrain the model until desired accuracy achieved and also notify developer by e-mail that the best model is being created.

## Create One extra job job6 for monitor: If the container where the app is running fails due to any reason then this job should automatically start the container again from where the last trained model left.

