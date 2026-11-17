# Yahia Ghallale

MSc student in **High Performance Computing Engineering** at Politecnico di Milano.
I build efficient ML systems and run careful ML experiments: GPU memory, compilers,
and models evaluated against real baselines.

- Student researcher in **scientific ML** (MOX Lab) and **computational pathology** (NECSTLab), Politecnico di Milano
- Teaching assistant: Python, ML & Neural Networks (120-seat course)
- Contributing to **PyTorch / TorchInductor**: [pytorch#199328](https://github.com/pytorch/pytorch/pull/199328), *Preserve empty-dimension semantics for `any` and `all`* (in review)

[Website](https://yahiaghallale.com) · [LinkedIn](https://www.linkedin.com/in/yahiaghallale) · [Email](mailto:ghallale.yahia04@gmail.com)

## Selected work

### Systems

**[gpumemd](https://github.com/yahiag04/gpumemd)**: a C++20 broker that keeps one GPU-resident copy of model weights or data and shares it across worker processes over CUDA IPC.
On an NVIDIA T4 with eight workers, total GPU usage dropped from 5,017 MiB to 1,433 MiB (−71%). Broker round-trip is 80 µs at p50 and 195 µs at p99.
`C++20` `CUDA` `CMake` `CTest`

### Research

**[SONIC](https://github.com/yahiag04/SONIC)**: instruction-guided sound removal with explicit temporal localization ([listen to the demo](https://yahiag04.github.io/SONIC/)).
It preserves background audio +16 dB better than global removal, at a measured 2.6 dB cost in target suppression. Results are reported with 95% CIs on a held-out split.
`PyTorch` `CLAP` `audio`

**[MORPH](https://github.com/yahiag04/MORPH)**: turns human hand demonstrations from phone video into simulated Franka Panda manipulation in MuJoCo, then learns an action-conditioned world model.
Evaluated with source-video-held-out folds against persistence baselines, including where it doesn't win.
`MuJoCo` `PyTorch` `robotics`

**[pneumonia-cxr-generalization](https://github.com/yahiag04/pneumonia-cxr-generalization)**: BSc thesis on cross-dataset generalization of five CNNs for chest X-ray pneumonia classification.
The main finding is that no architecture wins everywhere: rankings flip across target domains, metrics and thresholds. The study covers calibration, paired statistical tests and compute cost.
`PyTorch` `medical imaging` `evaluation`

**[jepa-embedding-study](https://github.com/yahiag04/jepa-embedding-study)**: does predicting one embedding view from another help few-label classification and retrieval?
It helps paired retrieval (Recall@1 7.9% → 12.3%) and 1-shot nearest-centroid (59% → 72%), but not class-disjoint retrieval.
`NumPy` `representation learning`

### Applied ML

**[flight-log-anomaly-ml](https://github.com/yahiag04/flight-log-anomaly-ml)**: anomaly detection for PX4 drone flight logs. A One-Class SVM trained on 110 normal flights reaches AUC 0.94 on held-out logs, alongside rule-based detectors, in a Streamlit dashboard.
`scikit-learn` `PX4` `Streamlit`

## Toolbox

- **Languages:** C++20, Python, C, CUDA, SQL, Bash
- **ML & compilers:** PyTorch, TorchInductor, JAX, ONNX Runtime, scikit-learn
- **HPC & GPU:** CUDA IPC, pinned memory, MPI, Eigen, NVIDIA Jetson
- **Tooling:** CMake, CTest, pytest, Docker, ROS 2, Linux
