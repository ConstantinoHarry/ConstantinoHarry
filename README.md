# CONSTANTINO HARRY ALEXANDER 
### [Repositories](https://github.com/ConstantinoHarry?tab=repositories) (View codes and what I have been doing recently) 

- Year 3 CS student at [HKBU](https://www.comp.hkbu.edu.hk/v1/) concentrating in Artificial Intelligence
- Currently an Associate Project Manage @ [Oursky](https://www.oursky.com)

  
        Java, DSA, application development, Maths and most importantly AI! 

# Recent Projects:

## 1. [**Architectural Tradeoffs in ALPR: YOLO26n vs Faster R-CNN**](https://github.com/ConstantinoHarry/Automatic-License-Plate-Detection--YOLO26n-vs.-Faster-R-CNN/blob/main/project_report.pdf)
- Conducted a controlled benchmarking study comparing the lightweight single-stage YOLO26n detector against a two-stage Faster R-CNN (ResNet-50 FPN backbone) for Automatic License Plate Recognition (ALPR).

### Architectures & Training
- **Faster R-CNN:** Achieved superior localization consistency with a mean IoU of 0.7233 and a lower catastrophic failure rate of 6.9%, making it ideal for accuracy-bounded, single-shot pipelines. Implemented a custom two-phase training curriculum utilizing plate-geometry-aware anchor ratios to compensate for license plate aspect ratios.
- **YOLO26n:** Delivered real-time performance with a 13.05x per-frame inference speed-up (41.6 FPS vs. 6.2 FPS on an NVIDIA T4). Recommended for throughput-bounded streaming deployments.

<p align="center">
  <img src="./frcnn_training_curves.png" alt="Faster R-CNN Training Curves" width="45%">
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="./yolo26_training_curves.png" alt="YOLO26n Training Curves" width="45%">
</p>

### Video Inference & Throughput
- Evaluated end-to-end video throughput and temporal consistency. Demonstrated YOLO26n's real-time streaming capabilities alongside highly stable inter-frame bounding box predictions (negligible jitter) for both models.

<p align="center">
  <img src="./video_comparison.png" alt="Video Inference and Temporal Consistency Comparison" width="90%">
</p>

### Detection Quality & End-to-End Evaluation
- **End-to-End Evaluation:** Benchmarked the detection models through EasyOCR, demonstrating that standard geometric metrics like IoU do not fully determine downstream OCR success. 
- On generalization tests, YOLO26n produced tighter bounding box crops that yielded closer matches to the ground truth when integrated with downstream Optical Character Recognition (OCR). 

<p align="center">
  <img src="./model_comparison_iou.png" alt="Model Comparison IoU" width="45%">
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="./detection_rate_comparison.png" alt="Detection Rate Comparison" width="45%">
</p>

<p align="center">
  <img src="./generalisation_test_comparison.png" alt="Generalisation Test Comparison with OCR Output" width="90%">
</p>

### Sample Predictions
<p align="center">
  <img src="./frcnn_sample_predictions.png" alt="Faster R-CNN Sample Predictions" width="45%">
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="./yolo26_sample_predictions.png" alt="YOLO26n Sample Predictions" width="45%">
</p>

## 2. [**Deep Image Colorization**](https://github.com/ConstantinoHarry/deep-image-colorization)
- Deep image colorization using a Pix2Pix-style cGAN: a ResNet‑18–backed U‑Net predicts Lab color ab channels from grayscale L, with a PatchGAN discriminator enforcing local realism. A hybrid objective (L1 + adversarial + LPIPS) plus optional FAISS retrieval hints improves vibrancy and training stability. Trained on a curated Kaggle subset; results include PSNR ≈ 22.53 dB and SSIM ≈ 0.9162.

- Semantic grayscale‑to‑color translation with ResNet‑UNet + PatchGAN in Lab space. Hybrid losses (L1 + GAN + LPIPS) and optional FAISS retrieval guidance produce vibrant, realistic colors with stable training. Colab‑ready notebook with reproducible setup, training, evaluation, and galleries.

## 3. [**FISCAL WISER**](https://github.com/ConstantinoHarry/Web-Development)
- FiscalWiser is a comprehensive financial planning web application designed to help users track income, expenses, budgets, retirement goals, and simulate paper trading for stocks and cryptocurrencies. The platform provides interactive charts, summary metrics, and persistent data storage for a seamless personal finance experience.

## 4. [**AIIGood - AI Companion for Mental Wellness Across All Ages**](https://github.com/ConstantinoHarry/JUMPSTARTER-SDG-Hackathon)
[**Initial Interface**](https://constantinoharry.github.io/JUMPSTARTER-SDG-Hackathon/) 
- AIIGood is an innovative AI-powered mental wellness platform designed to provide 24/7 anonymous support for children, adults, and the elderly in Hong Kong. Our solution addresses the growing mental health crisis by combining cutting-edge AI technology with compassionate care, reducing stigma and improving access to mental health resources.

  Team: AIIGood (Granville & Harry)



## 🌐 Connect With Me
[![Gmail](https://img.shields.io/badge/Gmail-harryconstantino16@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:harryconstantino16@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Harry%20Alexander%20Constantino-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harry-alexander-constantino/)
[![Instagram](https://img.shields.io/badge/Instagram-@ConstantinoHarry-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/constantinoharry/)


## 🛠️ Tech Stack

### 🤖 AI/ML & Data Science
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### 🌐 Web Development & APIs
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=json&logoColor=white)


### 🔧 Development Environments
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

### 📚 Version Control & Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)


<!---
ConstantinoHarry/ConstantinoHarry is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
