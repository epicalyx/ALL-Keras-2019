# Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project

## Acute Lymphoblastic Leukemia Keras Classifier 2019

[![CUREENT DEV BRANCH](https://img.shields.io/badge/CURRENT%20DEV%20BRANCH-0.0.1-blue.svg)](https://github.com/AMLResearchProject/ALL-Keras-2019/tree/0.0.1)

![Peter Moss Acute Myeloid / Lymphoblastic Leukemia AI Research Project](https://www.PeterMossAmlAllResearch.com/media/images/banner.png)

An Acute Lymphoblastic Leukemia classifier programmed in Python using Keras. Project by research intern [Taru Jain](https://www.petermossamlallresearch.com/students/student/taru-jain/profile "Taru Jain"), and [Amita Kapoor](https://www.leukemiaresearchassociation.ai/team/amita-kapoor/profile "Amita Kapoor").

This project aims to classify Acute Lymphoblastic Leukemia Cells from blood sample images with the aid of deep learning techniques. 
## Dataset:
* Class 0 - normal cells dataset is available [here](https://drive.google.com/drive/folders/1J-NIJ4AauKm9Oz3RZQ50ctE8rUgnu7SM?usp=sharing)
* Class 1 - leukemia cells dataset is available [here](https://drive.google.com/drive/folders/1K8iaxFudZZ0FxrXyIZLl8dNws_QXLsCn?usp=sharing)

## Model
The model used in this work is based on this [research work](http://www.ijcte.org/vol10/1198-H0012.pdf)

## Quantization
The model has been converted to its quantized version, so that it can be deployed on edge devices.

&nbsp;

# Getting Started 

To get started make sure your system meets the following requirements:

## Hardware
Google Colab GPU

## Software 
* Google Colab
* Keras (ver 2.2.5)
* Tensorflow (ver 1.15.0)

&nbsp;

## Clone latest development branch

First of all you should clone the [ALL-Keras-2019](https://github.com/AMLResearchProject/ALL-Keras-2019 "ALL-Keras-2019") repository from the [Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project](hhttps://github.com/AMLResearchProject "Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project") Github Organization. 

To do this, make sure you have Git installed, navigate to the location you want to clone the repository to on your device using terminal/commandline, and then use the following command.

The **-b "0.0.1"** parameter ensures you get the code from the latest development branch. Before using the below command please check our latest development branch in the button at the top of this page.

```
  $ git clone -b "0.0.1" https://github.com/AMLResearchProject/ALL-Keras-2019.git
```

Once you have used the command above you will see a directory called **ALL-Keras-2019** in the location you chose to clone to. In terminal, navigate to the **ALL-Keras-2019* directory, this is your project root directory.

## Acute Lymphoblastic Leukemia Image Database for Image Processing dataset

You need to be granted access to use the Acute Lymphoblastic Leukemia Image Database for Image Processing dataset. You can find the application form and information about getting access to the dataset on [this page](https://homes.di.unimi.it/scotti/all/#download) as well as information on how to contribute back to the project [here](https://homes.di.unimi.it/scotti/all/results.php). If you are not able to obtain a copy of the dataset please feel free to try this tutorial on your own dataset, we would be very happy to find additional AML & ALL datasets.

### ALL-IDB2 

In this project, [ALL-IDB2](https://homes.di.unimi.it/scotti/all/#datasets) is used, one of the datsets from the Acute Lymphoblastic Leukemia Image Database for Image Processing dataset. We will use data augmentation to increase the amount of training and testing data we have.

"The ALL_IDB2 version 1.0 can be used both for testing segmentation capability of algorithms, as well as the classification systems and image preprocessing methods. This dataset is composed of 108 images collected during September, 2005. It contains about 39000 blood elements, where the lymphocytes has been labeled by expert oncologists. The images are taken with different magnifications of the microscope ranging from 300 to 500."  

&nbsp;

# Use this project

Follow the guides below to build your Acute Lymphoblastic Leukemia Keras Classifier. 
* Clone the repo
* Open the ALLKCNN notebook in google colab and change runtime to GPU to accelerate training (although it may work just fine without GPU support as well)
* The dataset has been shared via Google Drive Links
* We can now explore and run the notebook
* Weight files have also been shared!

&nbsp;

# Contributing

The Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research project encourages and welcomes code contributions, bug fixes and enhancements from the Github.

Please read the [CONTRIBUTING](https://github.com/AMLResearchProject/ALL-Keras-2019/blob/master/CONTRIBUTING.md "CONTRIBUTING") document for a full guide to forking our repositories and submitting your pull requests. You will also find information about our code of conduct on this page.

## Contributors

- [Taru Jain](https://www.petermossamlallresearch.com/students/student/taru-jain/profile "Taru Jain") - [Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project](https://www.leukemiaresearchassociation.ai "Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project") Research Intern, Delhi, India

&nbsp;

# Versioning

We use SemVer for versioning. For the versions available, see [Releases](https://github.com/AMLResearchProject/ALL-Keras-2019/releases "Releases").

# License

This project is licensed under the **MIT License** - see the [LICENSE](https://github.com/AMLResearchProject/ALL-Keras-2019/blob/master/LICENSE "LICENSE") file for details.

# Bugs/Issues

We use the [repo issues](https://github.com/AMLResearchProject/ALL-Keras-2019/issues "repo issues") to track bugs and general requests related to using this project. See [CONTRIBUTING](https://github.com/AMLResearchProject/ALL-Keras-2019/blob/master/CONTRIBUTING.md "CONTRIBUTING") for more info on how to submit bugs, feature requests and proposals.
