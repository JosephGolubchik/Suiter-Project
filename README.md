<a href="https://github.com/elihaimov1992/SuiterFinalProject"><img src="https://github.com/elihaimov1992/SuiterFinalProject/blob/master/logo_small.png" title="Suiter - Final Project" alt="Suiter - Final Project"></a>

# Suiter - Final Project

An app for selecting a suit and adapting it to the user.


## Introduction

 * Project goal: Our goal is to create an app that helps users choose a suit and see how it looks on them before buying it.

 * The Suiter application will allow the user to choose a suit for himself and see how it will look on him. The user will provide a front view photograph of himself and 
   choose colors for the suit, and the application will draw the suit on top of him accordingly.


## Table of contents

> * [Introduction](#introduction)
> * [Table of contents](#table-of-contents)
> * [Installation](#installation)
>   * [Step #1: Android Studio and Python Installation](#step-1-android-studio-and-python-installation)
>   * [Step #2: Download the project folder (with all the files) from Github](#step-2-download-the-project-folder-with-all-the-files-from-github)
> * [Usage](#usage)
>   * [Explanation about ` AndroidProject ` folder](#explanation-about-androidproject-folder)
>   * [` AndroidProject ` (Suiter App) Example](#androidproject-suiter-app-example)
>   * [Explanation about ` PythonProject ` folder](#explanation-about-pythonproject-folder)
>   * [` PythonProject ` Example](#pythonproject-example)
>   * [Articles](#articles)
>   * [Tools](#tools)
> * [Authors](#authors)
> * [License](#license)
> * [Acknowledgments](#acknowledgments)


## Installation


#### Step #1: Android Studio and Python Installation

To get started developing in Android Studio and Python, you need to:
 * Install the [Android Studio](https://developer.android.com/studio).
 * Install the [Python](https://www.python.org/downloads/).
 
 
 #### Step #2: Download the project folder (with all the files) from Github
 
 At the end of downloading the folder, [Usage](#usage) provides detailed explanations about the installations and uses of the 2 subfolders (` AndroidProject ` and ` PythonProject `), respectively.
 
**Note: The explanation of all the algorithms is in the "Acknowledgments" content.


## Usage

The project (file) is divided into 2 parts, 2 sub-files:
1. ` AndroidProject ` folder - a folder with all the codes and graphic material (images) associated with the Suiter application.
2. ` PythonProject ` folder - a folder with all the codes (and libraries) and graphic material (images) related to the general algorithm of clothing worn on a human object identified in the image (by algorithms related to deep learning and computer vision)
"The next section is usage, in which you instruct other people on how to use your project after they’ve installed it. This would also be a good place to include screenshots of your project in action."


#### Explanation about ` AndroidProject ` folder

When you enter Android Studio, go to: ` File -> New -> Import Project.. ` and select the ` AndroidProject ` subfolder in the project folder (` Suiter-Project `).


<a href="https://github.com/elihaimov1992/SuiterFinalProject"><img src="https://github.com/elihaimov1992/SuiterFinalProject/blob/master/pic1.jpg" title="Suiter - Final Project" alt="Suiter - Final Project"></a>

Explanation of the main files of this folder (` AndroidProject `):
* ` app -> manifest -> AndroidManifest.xml `: XML file with all the permissions of this application.
* ` app -> java -> com -> example -> suiterfinalproject -> Activities -> CreateOutfitActivity `: A JAVA file that contains the main codes of this application, such as: initializing the objects and setting the actions of all the buttons in the application.


<a href="https://github.com/elihaimov1992/SuiterFinalProject"><img src="https://github.com/elihaimov1992/SuiterFinalProject/blob/master/pic2.jpg" title="Suiter - Final Project" alt="Suiter - Final Project"></a>
* ` app -> java -> com -> example -> suiterfinalproject -> Adapters -> ColorListAdapter `: A JAVA file which is responsible for matching the color list to all the items of the suit in this application.
* ` app -> java -> com -> example -> suiterfinalproject -> Models -> .. `: 
   1. ` ClothingColor ` : A JAVA file with functions (setters and getters) for receiving and returning the colors of the clothing details in this application.
   2. ` ClothingItem ` : A JAVA file with functions (setters and getters) for receiving and returning the colors of the clothing specific category in this application.
   3. ` ColorData ` : A JAVA file with arrays with a list of all the colors of the suit items in this application.
   4. ` Outfit ` : A JAVA file with functions (setters and getters) for receiving and returning the clothing items in this application.
* ` app -> res -> drawable `: Folder with all the graphic material (images) that appears in this application.

**Note: All the graphic material is in the ` drawable ` folder, when the project is uploaded in the explained instructions, all the graphic materials will also be uploaded automatically, which will be downloaded with the entire ` AndroidProject ` subfolder (in the process of downloading the ` Suiter-Project ` project file).


<a href="https://github.com/elihaimov1992/SuiterFinalProject"><img src="https://github.com/elihaimov1992/SuiterFinalProject/blob/master/pic3.jpg" title="Suiter - Final Project" alt="Suiter - Final Project"></a>
* ` app -> res -> layout -> activity_create_outfit.xml `: An XML file with all the layers of objects and graphics that appear on the main page of the application. This file is responsible for the all this page and size and location of these parts.


<a href="https://github.com/elihaimov1992/SuiterFinalProject"><img src="https://github.com/elihaimov1992/SuiterFinalProject/blob/master/pic4.jpg" title="Suiter - Final Project" alt="Suiter - Final Project"></a>
* ` app -> res -> layout -> activity_main.xml `: An XML file that serves as a login page for the application, a kind of temporary page that pops up at the login to the application and is followed by the main page of this application.
* ` app -> res -> layout -> info.xml `: An XML file used as an information page. By pressing the information button, located in the lower area on the right side of the app, the above page will appear.


#### ` AndroidProject ` (Suiter App) Example

Paste a recording of the use of the application (start from the information page + select colors for items and download the suit and show the page with the color detail of the downloaded image)


#### Explanation about ` PythonProject ` folder

(explanation of yosi + pictures like in ` AndroidProject ` example)


#### ` PythonProject ` Example

Paste, in the end, picture with all procedure from presentation (Solution Description)


#### Articles
* An research article explaining human identification and dressing it: 
[Image-based clothes changing system (by Zhao-Heng Zheng, Hao-Tian Zhang, Fang-Lue Zhang and Tai-Jiang Mu)](https://link.springer.com/content/pdf/10.1007/s41095-017-0084-6.pdf)

**Note: The photos in the project presentation were taken from this article


#### Tools

(yosi) all libraries that to need install


## Authors

* **Eli Haimov (ID. 308019306)** - *Programmer*
* **Yosi Golubchik (ID. 209195353)** - *Programmer*


## License

* Copyright (C) Eli Haimov and Yosi Golubchik - All Rights Reserved
* Unauthorized copying of this file, via any medium is strictly prohibited
* Proprietary and confidential
* Written by Eli Haimov and Yosi Golubchik < yosieli2020@gmail.com >, July 2020


## Acknowledgments

* Explanation about [License](https://softwareengineering.stackexchange.com/questions/68134/best-existing-license-for-closed-source-code)


#### Deep Learning algorithms:
* Explanation about Pose estimation algorithm: [tf-pose-estimation (by ildoonet)](https://github.com/ildoonet/tf-pose-estimation)
* Explanation about Mask R-CNN algorithm: [Mask R-CNN with OpenCV (by Adrian Rosebrock)](https://www.pyimagesearch.com/2018/11/19/mask-r-cnn-with-opencv/)

#### Computer Vision algorithms:
* Explanation about Triangulation algorithm: [Triangulation (by OpenCV)](https://docs.opencv.org/3.4/d0/dbd/group__triangulation.html)
* Explanation about Piecewise Affine Tranformation algorithm: [Affine Transformations (by OpenCV)](https://docs.opencv.org/3.4/d4/d61/tutorial_warp_affine.html)
* Explanation about GrabCut algorithm: [Interactive Foreground Extraction using GrabCut Algorithm (by OpenCV)](https://docs.opencv.org/trunk/d8/d83/tutorial_py_grabcut.html)

