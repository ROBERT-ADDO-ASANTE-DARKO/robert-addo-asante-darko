<h1 align="center">Robert Agyekum Addo</h1>

<p align="center">
  <b>Machine Learning Engineer · Computer Vision & 3D Perception</b><br>
  Accra, Ghana
</p>

<p align="center">
  <a href="https://linkedin.com/in/robert-agyekum-addo-3597461b4"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:raddo2961@gmail.com"><img src="https://img.shields.io/badge/Email-raddo2961%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## About

I build computer vision systems that work on real-world footage, not just benchmarks. My work spans monocular 3D reconstruction, visual place recognition, pose-based behaviour analysis, and real-time perception pipelines, usually from raw video all the way to a deployed system.

I'm a freelance computer vision engineer at **Farmline.ai**, building AI-powered poultry monitoring. I also work as a freight dispatcher for a US trucking fleet, which gives my research direct access to real commercial dashcam footage.

## Currently working on

- 🔭 **Monocular metric 3D reconstruction**: an adaptive MapAnything + Depth Anything 3 pipeline, with a paper in preparation
- 🗺️ **A loop closure dataset**: visual place recognition on US fleet dashcam footage, benchmarked with DINOv2 and SALAD
- 🐔 **Poultry activity recognition**: DeepLabCut SuperAnimal keypoints feeding an LSTM for temporal behaviours like wing flapping

## Featured projects

### ♟️ [Chessnut Vision Tracker](https://github.com/ROBERT-ADDO-ASANTE-DARKO/chessnut-vision-tracker)
Real-time pipeline that turns a webcam view of a physical chessboard into moves, PGN, and live Stockfish analysis.
Fine-tuned YOLO11-seg · ByteTrack · homography square mapping · MediaPipe hand-occlusion handling.
I also built the 671-instance segmentation dataset on CPU, using GrabCut edge-snapping and homography label propagation.

### 🛰️ Monocular Metric 3D Reconstruction & Visual Odometry
Per-chunk mode selection, formalized as an MDP and solved with Thompson sampling, over MapAnything and Depth Anything 3.
**4.891 m ATE on KITTI seq06** (monocular + GPS), outperforming stereo baselines. Evaluated across 74 runs on Comma2k19, KITTI, and real fleet footage.

### 🐔 Poultry Monitoring System · Farmline.ai
Two-stage pipeline: YOLOv8-seg anatomical part detection (9 keypoints) feeding MobileNetV3 breed and sex classifiers, plus ByteTrack tracking, pose-based activity analysis, and a multimodal RAG module (ColPali + Qwen 2.5-VL).

### 🚗 ADAS Perception Pipeline
YOLOv9, YOLOP, DeepSORT, Depth Anything V3, and SAM2, with time-to-collision risk scoring and pseudo-LiDAR point clouds from dashcam video.

### 🌊 ThirdWave · Flood Response for Accra
Streamlit platform with a district vulnerability dashboard, crowdsourced flood reports with AI photo triage, and 3D pluvial flood simulation.

### Earlier work
[Football analysis with YOLOv8](https://github.com/ROBERT-ADDO-ASANTE-DARKO/Football-Analysis-with-YOLOv8-and-OpenCV) ·
[Crop disease detection chatbot](https://github.com/ROBERT-ADDO-ASANTE-DARKO/AI-powered-crop-disease-detection) ·
[RAG chatbot with LLaMA-2](https://github.com/ROBERT-ADDO-ASANTE-DARKO/Business-chatbot) ·
[Transfer learning on MNIST](https://github.com/ROBERT-ADDO-ASANTE-DARKO/GO2COD_ML_01)

## Tech stack

**Computer vision:** YOLOv8/9/11 · SAM2 · DeepLabCut · ByteTrack · DeepSORT · OpenCV · MediaPipe
**3D vision:** Depth Anything V2/V3 · MapAnything · visual odometry · pose graph optimization · DINOv2 · SALAD
**ML & deep learning:** PyTorch · TensorFlow · scikit-learn · Hugging Face · LSTM · Sentence Transformers
**LLMs & multimodal:** LangChain · LlamaIndex · RAG · ColPali · Qwen 2.5-VL
**Geospatial & forecasting:** QGIS · Google Earth Engine · Microsoft Planetary Computer · Sentinel-1/2 · Prophet · XGBoost
**Tools:** Python · Docker · FastAPI · Streamlit · Roboflow · CVAT

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit">
</p>

## Experience

| Role | Organization | Period |
|---|---|---|
| Freelance Computer Vision Engineer | Farmline.ai | 2026 – present |
| Freight Dispatcher | Cdell Trucking LLC | 2025 – present |
| Data Annotator | Aya Data | 2025 |
| LLM Intern | AI School by JadooAI | 2024 – 2025 |
| Data Scientist / ML Engineer | Nationwide Affordable Housing Scheme | 2023 – 2024 |
| Deep Learning Researcher | Nikasemo Technologies | 2023 – 2024 |

**Education:** B.Sc. Information Technology, BlueCrest University College, Accra

---

<p align="center"><i>Open to AI/ML engineering roles and research collaborations in computer vision and 3D perception.</i></p>
