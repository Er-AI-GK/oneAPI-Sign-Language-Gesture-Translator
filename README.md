![Untitled](https://user-images.githubusercontent.com/106463633/230747827-b3db1985-59c8-4792-9af7-f8eca83a496f.png)

![Image](https://github.com/Er-AI-GK/oneAPI-Sign-Language-Translator/assets/106463633/8761d5bf-1264-43b3-b0bd-075d3fca2f31&width=1200&height=675)

# Intel oneAPI Sign Language Gesture Translator using MediaPipe

In this project, we will develop a Sign Gesture Language Translator using MediaPipe and the Intel OneAPI Platform. The translator will be able to recognize sign gestures captured from a video stream and convert them into corresponding text or spoken language.

## Prerequisites

Before getting started, make sure you have the following prerequisites installed:

- Python (3.6 or higher)
- MediaPipe
- Intel OneAPI Base Toolkit

## Installation

1. Install Python: Visit the Python website (https://www.python.org) and follow the instructions to install the latest version of Python for your operating system.

2. Install MediaPipe: Run the following command in your terminal to install MediaPipe using pip:

   ```bash
   pip install mediapipe
   ```

3. Install Intel OneAPI Base Toolkit: Visit the Intel Developer Zone website (https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit.html) and follow the instructions to download and install the Intel OneAPI Base Toolkit for your operating system.

## Usage

1. Clone the repository: Clone the project repository from GitHub using the following command:

   ```bash
   git clone https://github.com/Er-AI-GK/Intel-oneAPI-Speech_Emotion_Recognition_using_NLP_Audio_Text.git
   ```

2. Set up the environment: Open a terminal and navigate to the project directory. Activate the Intel OneAPI environment by running the following command:

   ```bash
   source <path-to-intel-oneapi>/setvars.sh
   ```

3. Run the translator: Execute the following command in the terminal to start the Sign Gesture Language Translator:

   ```bash
   SLT Main.ipynb
   ```

   The translator will launch and begin capturing video from your default camera.

4. Translate sign gestures: Make different sign gestures in front of the camera, and the translator will recognize them and display the corresponding text or spoken language output.

## Contributing

If you want to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Implement your changes and make sure the code passes all tests.
4. Commit your changes and push them to your forked repository.
5. Submit a pull request to the main repository.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Acknowledgments

We would like to thank the developers of MediaPipe and the Intel OneAPI Platform for their excellent tools and resources that made this project possible.

## References

- MediaPipe documentation: https://google.github.io/mediapipe/
- Intel OneAPI Platform documentation: https://devcloud.intel.com/oneapi/get_started/






# Problem Statement
Recently, deep learning algorithms have successfully addressed problems in various fields.

Emotion Recognition side it's not work properly because the previous model based on the **Facial Emotion Recognition** that model gives only the less accuracy output. 

# Solution ![image](https://cdn-icons-png.flaticon.com/128/1087/1087840.png) 
If we solve that problems it's only one way is availabe that is **Natural Language Processing** based Emotion Recognition using **Audio and Text** input signals.

The presence of various languages, accents, sentences, speaking styles, and speakers also adds another difficulty because these characteristics directly change most of the extracted features, including pitch and energy.

So, we introduced the NLP using **Audio and Text**.
## How I built it ![image](https://cdn-icons-png.flaticon.com/128/4946/4946348.png)

### 1. First I Import libraries in Intel oneAPI kernal

### 2. Preprocess the  dataset

### 3. Stemming using **NLTK Library**

### 4. Classify the sentences using **Count Vectorizer Tokenization**

### 5. Train the model using optimized TensorFlow in Intel oneDNN to get better results and faster computation.

### 6. Finally, I deploy my model using Streamlit framework

## Datasets ![](https://cdn-icons-png.flaticon.com/128/6802/6802146.png)
- IEMOCAP
- RAVDESS

## Technologies Used
- Jupyter Lab ( Intel oneAPI 2023 ) kernal
- TensorFlow
- Keras
- Streamlit
- NLTK
- Pickle

## Train & Accuracy 
https://user-images.githubusercontent.com/106463633/230749292-59d4f1cc-4aa8-4dfe-98af-2413da4d4a68.mp4

## Deployment ![image](https://user-images.githubusercontent.com/72274851/218502434-f6e66043-0db0-4f85-b7f4-f33b2d33df1f.png)

- Download and extract the project
- Download & Install requirement.

```
!pip install -r requirements.txt
  
```
- Run the web app using follow code
```
streamlit run app.py
  
```
https://user-images.githubusercontent.com/106463633/230747715-5a312479-ea23-443a-8a11-01ee70b7c294.mp4

## Role of oneAPI DNN
In this project we used large amount of dataset so normally it's take long time process.

I choosed OneAPI DNN it's have optimized library and Python OneAPI kernal. So, it's give acceleration my project and gives high accuracy output. 

![image](https://openbenchmarking.org/logos/pts_onednn.png)
## oneAPI Deep Neural Network Library (oneDNN)
oneAPI Deep Neural Network Library (oneDNN) is an open-source cross-platform
performance library of basic building blocks for deep learning applications.
oneDNN is part of [oneAPI](https://oneapi.io).
The library is optimized for Intel(R) Architecture Processors, Intel Graphics,
and Arm\* 64-bit Architecture (AArch64)-based processors. oneDNN has
experimental support for the following architectures: NVIDIA\* GPU,
AMD\* GPU, OpenPOWER\* Power ISA (PPC64), IBMz\* (s390x), and RISC-V.

oneDNN is intended for deep learning applications and framework
developers interested in improving application performance
on Intel CPUs and GPUs. Deep learning practitioners should use one of the
[applications enabled with oneDNN](#applications-enabled-with-onednn).

## Result & Output ![icon](https://cdn-icons-png.flaticon.com/128/5316/5316486.png)
https://user-images.githubusercontent.com/106463633/230747801-461227dd-2b4a-42d1-a1bc-5bf72014d939.mp4

## Intel DevMesh
https://devmesh.intel.com/projects/intel-oneapi-based-emotion-recognition-using-nlp-audio-text

## Get Start Your Intel oneAPI project 
==> https://devcloud.intel.com/oneapi/
==> www.oneapi.io/open-source/
