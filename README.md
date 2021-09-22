# Team-Project-23


## 1. Face mask wearing detection
### Problem Statement:
- A ML based project for detecting whether a person is wearing a mask or not.

### Abstract:
- Covid-19 pandemic has caused wearing a mask to be a mandatory precaution in public places. In restaurants/offices/malls, people are required to wear a mask and this is checked at the entry of the public place itself. As of now, a person is usually in-charge of making sure people don’t pull down their mask from their nose/mouth.  As the world is gradually opening up, governments/offices need to track if public places/employers are following Covid guidelines that are mandated.
A lot of man-power can be saved if we can detect whether people are wearing face masks through surveillance cameras. This will help governments/employers in monitoring covid regulations violations with minimal human intervention.


### Approach
- First we will start by collecting data from the various open source sites available and than next we will apply the data preprocessing step like resizing the image, data augmentation as per requirement. Than we will train a neural network using available algorithm like mobilenet and for these tasks we will be using libraries like tensorflow, keras, sklearn. Than we will use the model to predict on live video using libraries like opencv.

### Persona
- project can be used by various store owners, shopping mall and other public places where wearing mask is compulsory to detect people not following the rules.

### Dataset
- From various online resources


## 2. Pathology Classification

### Problem Statement
- To detect retinal diseases from given OCT image. - choroidal neovascularization (CNV), drusen, and diabetic macular edema (DME). 

### Abstract
- Optical coherence tomography (OCT) is an emerging medical technology for performing high-resolution cross-sectional imaging. Optical coherence tomography uses light waves to look inside a living human body. It can be used to evaluate thinning skin, broken blood vessels, heart diseases, and many other medical problems.Retinal optical coherence tomography is an imaging technique used to capture high-resolution cross sections of the retinas of living patients. Approximately 30 million OCT scans are performed each year, and the analysis and interpretation of these images takes up a significant amount of time. Computer vision is emerging in healthcare. The amount of data that pathologists analyze in a day can be too much to handle. Luckily, deep learning algorithms can identify patterns in large amounts of data that humans wouldn’t notice otherwise. It can detect various diseases in plants, animals, and humans. For this application, the goal is to get datasets from Kaggle OCT and classify data into different sections. 

### Approach
- From an OCT dataset, we produced a training dataset of 83,484 images and a test dataset of 1000 images. For training, the dataset comprises 37,205 images with choroidal neovascularization (CNV), 11,348 with diabetic macular edema (DME), 8616 with drusen, and 26,315 normal images. The test dataset has 250 images from each category. For classfication we will experiment starting from algorithm like mobilenet, resnet to state of the art algorithm to get the best possible outcome from the available research.

### Persona
- This can be used for medical analysis purpose.

### Dataset links
- https://www.kaggle.com/paultimothymooney/kermany2018


## 3. Vehicle Detection and Counting
### Problem Statement:
- To count the number of vehicles entering and leaving a particular place.

### Abstract
Increasing traffic volume in urban cities is a growing concern for today’s world. There are multiple reasons for traffic problems and accidents. Urbanization, which is movement of people from rural to urban areas, is one of the most important reason for increase in number of vehicles in big cities. In contrast to this, road sizes have not increased a lot in the past years. This has resulted in increased number of accidents, congestion, pollution and a lot of other problems. Absence of real-time traffic information also leads to traffic problems.
To solve the problem explained, we are proposing a vehicle counting and classification system. This system will take as input the video recordings from surveillance systems and provide as output the number of vehicles in a palce and also the types and sizes of vehicles in that area in a given time frame.

### Approach
- For this project we will be using libraries like opencv and numpy. The process is simple: 
Frame differencing - a technique where the computer checks the difference between two video frames.
Image thresholding -  Thresholding is a very popular segmentation technique, used for separating an object considered as a foreground from its background. A threshold is a value which has two regions on its either side i.e. below the threshold or above the threshold. 
Contour finding - we can detect the borders of objects, and localize them easily in an image.
Image dilation - Dilation is a morphological operation used to enhance the features of an image. 
And finally, vehicle counting:

### Persona
- This project can be used in many areas like traffic management, crowd counting, vehicle number plate, sports, and many more.


