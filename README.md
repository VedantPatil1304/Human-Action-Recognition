# Human Activity Recognition

### 📝 Description
This project is made with a perspective of recognizing human activities.  
The human activity recognition model was trained on the **Kinetics 400 Dataset**.

To learn more about the dataset and model:
- Kay et al.’s 2017 paper: [The Kinetics Human Action Video Dataset](https://arxiv.org/abs/1705.06950)
- Hara et al.’s 2018 CVPR paper: [Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet?](https://arxiv.org/abs/1711.09577)

The authors — Kensho Hara, Hirokatsu Kataoka, and Yutaka Satoh — explained how existing 2D CNN architectures (like ResNet, ResNeXt, DenseNet) can be extended to video classification via **3D kernels**.

---

### ✅ Prerequisites

#### Required
- Python Programming Language
- Convolutional Neural Network (CNN) basics

#### Recommended (not mandatory)
- [ONNX-Based Deep Learning Models](https://github.com/onnx/models)
- [OpenCV for Python](https://opencv.org/)

---

### ⚙️ Installations
- [Install Python](https://www.python.org/downloads/)
- [Install OpenCV for Windows](https://docs.opencv.org/master/d5/de5/tutorial_py_setup_in_windows.html)
- [Install OpenCV for Ubuntu](https://docs.opencv.org/master/d2/de6/tutorial_py_setup_in_ubuntu.html)
- Execute:
  ```bash
  pip install numpy

###  Directory Structure:
![Direcory Stucture](https://github.com/user-attachments/assets/fa3183a4-2893-4eae-a194-7f29445dbaa6)

### External Download:
-You need to dowwload a resnet-34_kinetics.onnx model from here and once downloaded drop it inside the model directory of our project (shown in directory structure)

### Setup:
1.I have added a video example for testing in test directory
2.If you want to test your own video file be sure to add it in test folder
3.Now, inside recognise_human_activity.py constructor set instance variable VIDEO_PATH to you file path.
4.Otherwise, if you want test the model on using web-camera live video just set self.VIDEO_PATH = None

-Once your setup is done run the following to execute code:
```bash
python recognise_human_activity.py
```
### Screenshots:
-Playing keyboard-

![image](https://github.com/user-attachments/assets/2cf275ca-d014-4e9e-8018-dcd75b4ee020)

-High Kick-

![image](https://github.com/user-attachments/assets/92400e77-50da-4425-a432-aee05a17942f)

-Push ups-

![image](https://github.com/user-attachments/assets/7ac30412-85e3-4cf7-a89e-2603c69d7391)

### 👤 Project Team

**Vedant Patil ,Yogesh Kunde ,Vedant Kokate**  

### Acknowledgements:
-This project was inspired from work by [Chaitanya Sonavane](https://www.linkedin.com/in/chaitanya-sonavane-3766521a0/). We extended and modified the implementation for college demonstration purposes.

-Kay et al.’s 2017 paper, The Kinetics Human Action Video Dataset.
-Hara et al.’s 2018 CVPR paper, Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet?
-OpenCV's Action Recognition Example






  
