---
layout: home
author_profile: true
classes: wide smaller-font
---

{% capture custom_content %}
## About Me
<div style="text-align: justify; font-size: 16px;">
I am a <strong>Ph.D. candidate</strong> and <strong>university fellow</strong> in Electrical Engineering at the University of Rhode Island, with over <strong>4 years</strong> of combined experience in academic research and professional work as a <strong>Machine Learning Engineer</strong>. I have experience in reinforcement learning, robotics, computer vision, signal processing, and natural language processing (NLP). My current research as a Ph.D. candidate focuses on autonomous and shared autonomy systems, human-in-the-loop intelligent agents, and electroencephalography (EEG) analysis and interpretation. I design multimodal AI frameworks that integrate biosignals with computer vision and reinforcement learning to enhance shared autonomy systems specifically for individuals with disabilities.
</div>


{: .small}

---
## Research Interests

1. **Robotics**
   - Kinematics, Control systems, Reinforcement larning, Imitation learning, Path planning, Human-robot interaction, Sensor integration (LiDAR, cameras, IMUs), ROS (Robot Operating System) development, Simulation software, Sim-to-real

2. **Reinforcement Learning**
   - Deep RL algorithms (DQN, DDPG, TD3, SAC, PPO, A3C), Policy gradient methods and actor-critic architectures, Inverse reinforcement learning and imitation learning, PyBullet, Custom reward functions

3. **Computer Vision**
   - CNN architectures (ResNet, DenseNet, EfficientNet, Vision Transformer), Object detection (YOLO v3-v7), Segmentation (U-Net, Mask R-CNN, DeepLab), 3D vision (PointNet++, VoxelNet, point cloud processing), SLAM, Pose estimation, Multi-View Geometry


4. **Signal Processing**
   - Time series analysis (ARIMA, LSTM, GRU- RCNN), EEG signal processing, Spectral analysis, Time-frequency analysis (STFT, wavelets, Hilbert-Huang transform), Signal filtering and enhancement (Kalman filters, FIR/IIR), Feature extraction methods (FFT, wavelets), Denoising, Blind source separation (ICA, NMF)

5. **Natural Language Processing (NLP)**
   - Text preprocessing and feature extraction (TF-IDF, word embeddings), Transformer architectures (BERT, RoBERTa, GPT), Attention mechanisms, Sentiment analysis, language modeling, and transformer architectures.

6. **Generative AI**
   - GAN architectures (DCGAN, WGAN, StyleGAN, VAE), Diffusion models

---
## Technical Skills
- **Programming:** Python, C/C++, MATLAB, SQL
- **Machine Learning & AI:** TensorFlow, PyTorch, torchvision, Scikit-learn, Keras, OpenAI Gym, OpenCV, PIL
- **Robotics:** ROS, MoveIt, PyBullet, Gazebo
- **Data Analysis & Visualization:** NumPy, Pandas, Matplotlib, Seaborn, Plotly, SKLearn, SciPy
- **Tools:** Git, GitHub, Docker, Kubernetes, Streamlit, Hugging Face, AWS
- **Hardware:** Sensor fusion, Microcontroller programming (Arduino, Raspberry Pi)

{: .small}
{% endcapture %}

{{ custom_content | markdownify }}
 ---

## Sample Projects 

### Kinova RL: a ROS package for Shared Control Deep Reinforcement Learning
This ROS package implements a shared control Deep Reinforcement Learning (DRL) system for robotic manipulation
using a Kinova robotic arm. The system integrates visual input from a camera, head motion data from an IMU
sensor, and a trained DQN (Deep Q-Network) agent to control the robot’s actions. [GitHub Link](https://github.com/ali-rabiee/Kinova_RL)
<video width="600" height="400" controls>
    <source src="{{ '/assets/videos/sim2real.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag. You can <a href="{{ '/assets/videos/sim2real.mp4' | relative_url }}">download the video</a> instead.
</video>

### Adaptive Robotic Control for Users with Severe Impairments using DRL
A system that optimizes mapping from low-DoF inputs to high-dimensional robotic actions, enabling intuitive control for users with severe impairments. It uses adaptive goal prediction and reinforcement learning to guide actions in real-time, seamlessly blending user input with autonomous assistance. [GitHub Link](https://github.com/ali-rabiee/amplification_DRL)
![GIF]({{ '/assets/videos/amplification_demo.gif' | relative_url }}) 



### Dual-Mode Robotic Arm Control with GUI and IMU Integration
This project integrates a graphical user interface (GUI) with an inertial measurement unit (IMU) sensor to provide
dual-mode control of a robotic arm. Users can choose to control the robotic arm by clicking on cursor buttons in the
GUI or by using the IMU sensor to move the cursor for button selection. [GitHub Link](https://github.com/ali-rabiee/ClickMove-Robotics)
<img src="{{ '/assets/videos/ClickMove_demo.gif' | relative_url }}" alt="Project 1 GIF" width="600" height="auto">

### Panorama Creation via Harris Corner Detection and Image Stitching
This project involves the creation of panoramic images by detecting key interest points in multiple images using the
Harris corner detector. After identifying these points, the project matches them between images and computes the
homography to accurately align and stitch the images together, resulting in panoramic views. [GitHub Link](https://github.com/ali-rabiee/Keypoint-Extraction-and-Matching)
<img src="{{ '/assets/images/panorama.png' | relative_url }}" alt="Project 1 GIF" width="700" height="auto">

## EEG Data Analysis
Developed a Python-based toolkit for processing and analyzing complex EEG datasets (64 channels, 640 time points,
99 trials). Implemented advanced signal processing techniques including epoch extraction, ERP computation, peak
time identification, topographical mapping, and Laplacian filtering for enhanced spatial resolution. [GitHub Link](https://github.com/ali-rabiee/Brain-Signal-Analysis-Topomaps)
<img src="{{ '/assets/images/EEG.png' | relative_url }}" alt="Project 1 GIF" width="500" height="auto">

## IMDB Sentiment Analysis
Implemented a comprehensive sentiment analysis pipeline on the IMDB dataset, employing various text preprocessing
techniques (stop word removal, stemming, lemmatization). Developed and compared multiple classification models for
sentiment prediction, and evaluated different clustering methods to uncover patterns in the dataset. [GitHub Link](https://github.com/ali-rabiee/sentiment-analysis)
<img src="{{ '/assets/images/sentiment.png' | relative_url }}" alt="Project 1 GIF" width="500" height="auto">

## GAN and DCGAN Implementation for Synthetic Digit Generation
Implemented Generative Adversarial Networks (GAN) and Deep Convolutional GANs (DCGAN) to synthesize realistic handwritten digits. Trained models on the MNIST dataset, comparing the performance and quality of generated images between standard GANs and DCGANs. Demonstrated proficiency in deep learning architectures, image generation techniques, and evaluating generative model outputs. [GitHub Link](https://github.com/ali-rabiee/GAN-digits)
<img src="{{ '/assets/images/digits.png' | relative_url }}" alt="Project 1 GIF" width="500" height="auto">
