# Charan Nallani

**AI/ML Engineer** · Advanced Computer Vision · Multimodal AI · Real-Time Deployment

I build end-to-end machine learning systems—from research-aligned model development to production-grade inference pipelines. My work spans 3D spatial perception, vision-language retrieval, and industrial anomaly detection, with a focus on architectural efficiency and deployment under real-world constraints.

📍 Open to research collaborations and senior ML engineering roles  
🔗 [LinkedIn](https://www.linkedin.com/in/charan-nallani) · [Portfolio](https://charannallani.github.io) · [Email](mailto:nallanicharan64@gmail.com)

---

## Projects

### Computer Vision & 3D Perception

**[Multi-Object Tracking with Re-Identification](#)**  
Real-time detection and identity-persistent tracking across temporary occlusions and multi-camera setups. Built on YOLOv8 + ByteTrack + torchreid. Benchmarked on MOT17.

**[Semantic Segmentation: Transformer vs. CNN](#)**  
Controlled comparative study evaluating SegFormer, Mask2Former, and DeepLabV3+ on the Cityscapes dataset. Metrics: mIoU, inference FPS, and model size footprint.

**[Monocular Depth Estimation with Uncertainty Quantification](#)**  
Single-image 3D spatial understanding using DPT / ZoeDepth with a Bayesian MC Dropout module for pixel-level confidence estimation. Evaluated on KITTI and NYUDepthV2.

---

### Multimodal AI & Video Understanding

**[Vision-Language Retrieval System](#)**  
Natural language semantic search over large image corpora using fine-tuned CLIP + BLIP-2 embeddings indexed with FAISS. Includes a VQA module. Evaluated via Recall@K.

**[Few-Shot Industrial Anomaly Detection](#)**  
Manufacturing defect detection under factory constraints using only normal reference images. 5-shot adaptation layer over PatchCore + FastFlow + WinCLIP. Benchmarked on MVTec AD.

**[Video Human Action Recognition](#)**  
Spatio-temporal transformer (VideoMAE + TimeSformer) fine-tuned on UCF-101 with a custom lightweight attention module. Benchmarked against 3D-CNN baselines.

---

## Tech Stack

| Domain | Tools |
|---|---|
| Core AI/ML | PyTorch, Torchvision, OpenCV, YOLOv8, Hugging Face Transformers |
| Retrieval & Tracking | FAISS, ByteTrack, torchreid, MLflow |
| MLOps & Infrastructure | Docker, FastAPI, AWS (S3, EC2, Bedrock) |
| Edge Integration | Flutter, Android SDK |

---

## Engineering Focus

- Real-time detection, segmentation, and spatio-temporal tracking pipelines
- Multimodal retrieval and cross-modal embedding optimization
- Accuracy–latency–model size trade-off analysis for edge deployment
- Uncertainty estimation and explainability in safety-critical vision systems

---

## GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=charannallani&show_icons=true&theme=dark&hide_border=true&count_private=true" height="160" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=charannallani&layout=compact&theme=dark&hide_border=true" height="160" alt="Top Languages" />
</p>
