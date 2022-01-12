# CS4487 Machine Learning: DeepFake Detection

## Objective
For decades, visual effects have been used to generate convincing manipulations of digital facial photographs. Deep learning techniques, particularly "DeepFake," have dramatically increased the realism of fake content. DeepFake is a combination of the words "deep learning" and "fake," and it entails replacing someone's likeness on existing photographs or videos with another person.
While there are some amusing use cases for DeepFakes, their potential weaponization has aroused serious concerns, as misuse might result in reputational damage and fraud.

As a result, DeepFake Detection has emerged as a critical challenge and a hotbed of research. We hope to simplify detecting DeepFake images of humans from a set of random images in this project.

## Data
The data can be downloaded from the CS4487 Course Project [Kaggle Page](https://www.kaggle.com/c/cs4487-course-project)

Alternatively, they can be found at my deepfake-detection [onedrive link](https://portland-my.sharepoint.com/:f:/g/personal/rmohan2-c_my_cityu_edu_hk/EtpgD4ajLjVMltGRfXvDSkMB8DGhyl3-zZRu0m2bbDt7rw?e=R6loEM)

The data folder consists of 3 subfolders each with 4000 images:
<ol>
    <li>real - Consists of real images.</li>
    <li>fake_deepfake - These images have been modified using deepfake technology.</li>
    <li>fake_face2face - Face 2 Face is a system that allows live editing of facial features and emotions reenactment of an input video.</li>
</ol>

The 'data/test_plus' folder contains a set of shuffled images for real-world testing.

## Running
The pre-trained models are also present at my [ondrive link](https://portland-my.sharepoint.com/:f:/g/personal/rmohan2-c_my_cityu_edu_hk/EtpgD4ajLjVMltGRfXvDSkMB8DGhyl3-zZRu0m2bbDt7rw?e=R6loEM). The 'Testing Function' present in the jupyter notebook uses the images from the 'test_plus' folder to predict whether they are real or modified in any manner. 

## Frameworks used
<ol>
    <li>Tensorflow + Keras</li>
    <li>Scikit-Learn</li>
    <li>Python Image Library</li>
    <li>Seaborn</li>
</ol>

References are listed in the jupyter notebook.