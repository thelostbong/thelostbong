## Hey, I'm Nayeem

Training models that are just as confused as I am.

MLOps and AI infrastructure. I spent two years running production DevOps at Tata Consultancy Services, Terraform-provisioned Kubernetes on EKS, 50+ microservices, GitLab and Jenkins pipelines that took deployment from 48 hours to under 30 minutes. Now I'm at TH Deggendorf applying the same standards to ML systems, so they end up in production instead of in a notebook.

Finishing an M.Eng in Applied AI for Digital Production Management (Oct 2026). Looking for MLOps, AI infrastructure, or ML platform roles in Germany.

### What I actually build

Models that survive leaving the laptop: quantized exports, containerized inference, CI/CD, and a way to see what the thing is doing once it is running.

Computer vision at the station rather than in a datacentre, edge devices on a line, wired into the MES the factory already runs on.

Generative pipelines built from several small models handing off to each other, with an automated scoring step instead of eyeballing the output.

Forecasting and simulation where the decision has a cost attached, so the model gets ranked on that cost and not on RMSE alone.

### Selected work

| Project | What it does | Stack |
|---|---|---|
| [Assembly Inspection + MES](https://github.com/thelostbong/AI-Based-Automated-Assembly-Inspection-with-MES-Integration) | Resolves 16 LEGO build variants from three fixed cameras on a Raspberry Pi 5 and posts the result into a Tulip MES. Full edge-to-MES round trip under a second. | YOLOv12s, ONNX, Flask, FastAPI, Tulip MES |
| [Edge AI Defect Detection](https://github.com/thelostbong/Automated-Defect-Detection-using-Edge-AI) | Two-stage detector for colour and missing piece defects, quantized to INT8 and running on an ESP32-P4 NPU. Stage 1 hits 0.995 mAP@0.5 at recall 1.0. | YOLOv11n, INT8 quantization, ESP-IDF, UVC |
| [Fashion Article Image Generation](https://github.com/thelostbong/Fashion-article-image-generation) | Turns German product copy into catalogue ready product images through four chained models, with CLIP scoring as the quality gate. Built with NKD. | MarianMT, Phi-3 Mini, FLUX.1-schnell + LoRA, CLIP |
| [Cost-Aware Demand Forecasting](https://github.com/thelostbong/Cost-aware-demand-forecasting) | Backtests ARIMA, SARIMA and Prophet on an expanding window, then ranks them on total inventory cost — where the accuracy winner and the cost winner disagree. | statsmodels, Prophet, pandas |
| [Fetal Health Classification](https://github.com/thelostbong/Fetal_Health_Classification_using_Machine_Learning) | Triages cardiotocography readings into three classes, with SMOTE applied inside the training pipeline so nothing leaks into the test set. Random Forest at 94.6%. | scikit-learn, imbalanced-learn |
| [Call-Center Staffing Simulator](https://github.com/thelostbong/Queueing-Simulation-and-Optimization-System) | Discrete-event M/M/c model that finds the staffing level meeting the wait-time SLA at the lowest cost, cross-checked against Erlang C. | SimPy, NumPy, matplotlib |

### Tools

Python, PyTorch, Ultralytics YOLO, ONNX, OpenCV, scikit-learn, FastAPI

Docker, Kubernetes (Amazon EKS), Terraform, GitLab CI, Jenkins, AWS, Grafana

R, SimPy, statsmodels, Prophet

Tulip MES, ESP-IDF, Raspberry Pi

### Background

M.Eng Applied AI for Digital Production Management, TH Deggendorf (2025–2026)

Research Assistant, TH Deggendorf: edge inspection, MES integration, design of experiments

DevOps Engineer, Tata Consultancy Services (2023–2025): AWS, Terraform, Kubernetes, IoT pipelines

B.Tech Mechanical Engineering, SRM IST Chennai

### Reach me

[LinkedIn](https://www.linkedin.com/in/nayeemuddin-mohammed-03/) · nayeemuddin.mohammed@stud.th-deg.de
