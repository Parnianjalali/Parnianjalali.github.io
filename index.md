---
layout: home
author_profile: true
classes: wide smaller-font
---

{% capture custom_content %}
## About Me
<div style="text-align: justify; font-size: 16px;">
I am a graduate research assistant at Isfahan University of Technology (IUT) with extensive experience in designing and developing AI frameworks for healthcare applications. My passion lies in creating advanced AI tools to assist patients and healthcare professionals, ultimately enhancing quality of life. Through my work, I aim to improve clinical outcomes, detect and prevent diseases, and mitigate harmful health habits.

I thrive on conducting research and developing innovative solutions by leveraging machine learning, deep learning, and signal and image processing techniques. To stay at the forefront of this rapidly evolving field, I am  dedicated to continuously expanding my knowledge and expertise in AI. My ultimate goal is to bridge the gap between cutting-edge technology and practical healthcare solutions, fostering impactful advancements in the medical field.


</div>

## Education						       		
- M.S.,  Computer Engineering, Artificial Intelligence	| Isfahan University of Technology (_Aug 2023_)	 			        		
- B.S.,  Electrical Engineering, Telecommunication | University of Isfahan (_Jun 2019_)


---
## Research Interests

1. **AI in Healthcare**
   - My research focuses on leveraging AI and machine learning, particularly deep learning and neural networks, to detect both physical and mental health conditions early. The goal is to prevent diseases before they arise, halt their progression, and reduce complications for patients who are already affected.
  
2. **Biomedical Signal Processing**
   - My research focuses on extracting meaningful features from biomedical signals, such as ECG and EEG, using time-frequency domain techniques like wavelet transform. These features, when considered as data representations in machine learning models, enhance the accuracy and efficiency of signal interpretation. I am particularly interested in making this process computationally efficient for integration into wearable devices, enabling real-time monitoring and analysis.


3. **Computer Vision**
   - CNN architectures (ResNet, DenseNet, EfficientNet, Vision Transformer), Object detection (YOLO v3-v7), Segmentation (U-Net, Mask R-CNN, DeepLab), 3D vision (PointNet++, VoxelNet, point cloud processing), SLAM, Pose estimation, Multi-View Geometry

4. **Interpretable AI**
   - In the medical field, where decisions directly impact patient, the interpretability and explainability of deep learning models are critical. These qualities foster trust among clinicians and practitioners, enabling them to confidently adopt and rely on AI tools. Furthermore, understanding how models make decisions can uncover new insights and advance medical knowledge.

5. **Multi-modal Learning**
   - With the inherently diverse modalities of medical data—such as text, images, and time-series signals—integrating them can provide a deeper understanding of complex medical conditions, enhancing interpretability and leading to more accurate diagnoses.

6. **Large Language Model (LLM)**
   - I have experience in collecting, annotating, and creating datasets, as well as fine-tuning pretrained language models such as BERT and DeBERTa for sentiment analysis. My interests include developing multi-modal LLMs that integrate text and image data and exploring techniques like prompt engineering to enhance model performance and adaptability.
{: .small}
---
## Technical Skills
- **Programming:** Python, C/C++, MATLAB, SQL
- **Machine Learning & AI:** TensorFlow, PyTorch, torchvision, Scikit-learn, Keras, OpenAI Gym, OpenCV, PIL
- **Data Analysis & Visualization:** NumPy, Pandas, Matplotlib, Seaborn, Plotly, SKLearn, SciPy
- **Tools:** Git, GitHub, Docker, Kubernetes, Streamlit, Hugging Face, AWS
{: .small}
{% endcapture %}

{{ custom_content | markdownify }}

