<h2 align="center">Yahia Ghallale</h2>

<p align="center">
  MSc student in <b>High Performance Computing Engineering</b> at Politecnico di Milano.<br>
  I build ML that runs on real hardware: edge perception for autonomous systems, and the GPU and compiler infrastructure underneath it.
</p>

<p align="center">
  <a href="https://yahiaghallale.com"><img src="https://img.shields.io/badge/Website-yahiaghallale.com-0A0A0A?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/yahiaghallale"><img src="https://img.shields.io/badge/LinkedIn-yahiaghallale-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:yahia.ghallale@mail.polimi.it"><img src="https://img.shields.io/badge/Email-yahia.ghallale%40mail.polimi.it-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

- 🛩️ Incoming AI Engineer Intern at **Thales** (Navigation & Air Systems, Milan), from January 2027
- 🔬 Student researcher in scientific ML (MOX) and computational pathology (NECSTLab), Politecnico di Milano
- 🎓 Teaching assistant for a 120-seat Python, ML & Neural Networks course
- 🔧 Open PyTorch / TorchInductor fix: [pytorch#199328](https://github.com/pytorch/pytorch/pull/199328)

---

### ⚡ Systems

**[gpumemd](https://github.com/yahiag04/gpumemd)**: C++20 broker that keeps one GPU-resident copy of weights or data and shares it across worker processes via CUDA IPC. On an NVIDIA T4 with 8 workers, GPU memory drops 71% (5,017 → 1,433 MiB); broker round-trip 80 µs p50 / 195 µs p99.

![C++](https://img.shields.io/badge/C%2B%2B20-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![CTest](https://img.shields.io/badge/CTest-555555?style=flat-square)

### 🤖 Perception, robotics & autonomy

**[schematic2graph](https://github.com/yahiag04/schematic2graph)**: extracts circuit topology from schematic PDFs with a vision-language model and scores it against KiCad netlists. 25 open-source projects, 1,358 ground-truth edges: edge F1 0.94, no hallucinated components, with a per-error analysis of where it fails.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_VLM-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![networkx](https://img.shields.io/badge/networkx-555555?style=flat-square)

**[flight-log-anomaly-ml](https://github.com/yahiag04/flight-log-anomaly-ml)**: anomaly detection on PX4 drone flight logs. A One-Class SVM trained on 110 normal flights reaches AUC 0.94 on held-out logs, alongside rule-based detectors, in a Streamlit dashboard.

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![PX4](https://img.shields.io/badge/PX4-555555?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**[MORPH](https://github.com/yahiag04/MORPH)**: turns phone video of hand demonstrations into simulated Franka Panda manipulation in MuJoCo, then learns an action-conditioned world model. Evaluated on held-out source videos against persistence baselines, including the cases where it loses.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-555555?style=flat-square)

### 📊 Research & evaluation

**[pneumonia-cxr-generalization](https://github.com/yahiag04/pneumonia-cxr-generalization)**: BSc thesis on cross-dataset generalization of five CNNs for chest X-ray pneumonia classification. No architecture wins everywhere: rankings shift across domains, metrics and thresholds. Calibration, paired tests, compute cost.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Medical imaging](https://img.shields.io/badge/Medical_imaging-555555?style=flat-square)

**[SONIC](https://github.com/yahiag04/SONIC)**: instruction-guided sound removal with temporal localization; keeps background audio 16 dB better than global removal at a measured 2.6 dB cost in target suppression (95% CIs, held-out split). [Demo](https://yahiag04.github.io/SONIC/)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![CLAP](https://img.shields.io/badge/CLAP-555555?style=flat-square)

**[jepa-embedding-study](https://github.com/yahiag04/jepa-embedding-study)**: does predicting one embedding view from another help with few labels? Paired retrieval Recall@1 7.9% → 12.3% and 1-shot nearest-centroid 59% → 72%, but no gain on class-disjoint retrieval.

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

---

### 🧰 Toolbox

**Languages**
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**ML & compilers**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TorchInductor](https://img.shields.io/badge/TorchInductor-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-555555?style=flat-square)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**GPU, edge & tooling**
![CUDA IPC](https://img.shields.io/badge/CUDA_IPC-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
