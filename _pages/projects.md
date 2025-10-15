---
<!-- layout: archive -->
title: "Projects"
permalink: /projects/
author_profile: true
---

<img width="150" height="75" src="https://abhishekch47.github.io/images/nyu.jpg"/> <br>
<br>
<b>Parallel Embedding Optimization with CUDA</b> <br>
Feb 2025 <br>
* Designed and implemented a **CUDA-parallelized metric learning and similarity computation pipeline** for large-scale recommendation datasets (10M+ vectors). <br>
* Applied **shared memory tiling**, **warp-level primitives**, and **coalesced memory access** to maximize GPU throughput and minimize latency. <br>
* Integrated **kernel fusion techniques** to reduce intermediate writes and improve overall GPU compute efficiency. <br>
* Benchmarked performance using **Nsight Compute** and **nvprof**, identifying bottlenecks in vector similarity operations. <br>
* Achieved **3.2× speedup** over baseline implementations and demonstrated sub-millisecond query latency. <br>
* Technologies Used: **CUDA, C++, PyTorch, Nsight Compute** <br>
<br>

<img width="150" height="75" src="https://abhishekch47.github.io/images/nyu.jpg"/> <br>
<br>
<b>Multicore Programming: OpenMP vs. Rust (Rayon)</b> <br>
Apr 2025 <br>
* Conducted a detailed performance study comparing **OpenMP (C)** and **Rayon (Rust)** across 8 HPC workloads including CNN training, Monte Carlo simulations, N-Body physics, and ray tracing. <br>
* Implemented both **shared-memory** (OpenMP) and **task-parallel** (Rayon) versions to evaluate scalability, runtime overhead, and ease of development. <br>
* Analyzed **false sharing**, **load imbalance**, and **task scheduling** strategies to identify language-level performance trade-offs. <br>
* Demonstrated that **Rust + Rayon** achieved up to **4.7× speedup** by reducing false sharing and optimizing work-stealing efficiency. <br>
* Delivered detailed scalability guidelines for **multicore HPC applications**. <br>
* Technologies Used: **Rust (Rayon), C, OpenMP, Linux HPC Cluster** <br>
<br>

<img width="150" height="75" src="https://abhishekch47.github.io/images/nyu.jpg"/> <br>
<br>
<b>Operating Systems Scheduler Simulation</b> <br>
Dec 2024 <br>
* Built a **Discrete Event Simulation (DES)** framework in C++ to model scheduling algorithms: FCFS, LCFS, SRTF, RR, PRIO, and PREPRIO. <br>
* Implemented **dynamic and static priority scheduling**, including I/O burst simulation and priority decay. <br>
* Produced **Gantt chart visualizations** for process execution timelines and CPU utilization. <br>
* Computed metrics like **average turnaround time**, **wait time**, and **throughput** to evaluate algorithm efficiency. <br>
* Designed the simulation for extensibility, enabling new scheduling algorithms without altering the core logic. <br>
* Technologies Used: **C++, Data Structures, Algorithms, OS Simulation** <br>
<br>

<hr style="border:1px solid #ccc; width:80%; margin:40px 0;">

<img width="150" height="75" src="https://abhishekch47.github.io/images/pes.jpg"/> <br>
<br>
<b>Automated Traffic Light Control and Violation Detection System</b> <br>
Advisor: [Prof. Raghu B.A]<br>
* Developed an **automated traffic light system** using CCTV footage analysis, incorporating **SVM for object prediction** and **ARIMA for signal timing**. <br>
* Implemented **YOLOv3-based violation detection** for helmet and line-crossing infractions. <br>
* Integrated **EasyOCR** for automatic license plate recognition (ANPR). <br>
* Built the complete solution using **Python, OpenCV, and TensorFlow** for real-time video analytics. <br>
<br>

<img width="150" height="75" src="https://abhishekch47.github.io/images/pes.jpg"/> <br>
<br>
<b>Mini Java Compiler</b> <br>
Advisor: [Prof. Preet Kanwal]<br>
* Developed a **mini Java compiler** using **Lex and Yacc** for lexical and syntax analysis. <br>
* Implemented an **Abstract Syntax Tree (AST)** for program representation and generated **optimized MIPS assembly code**. <br>
* Added optimizations like **constant folding** and **common subexpression elimination** for faster execution. <br>
* Technologies Used: **Lex, Yacc, Python, MIPS Assembly** <br>
<br>

<img width="150" height="75" src="https://abhishekch47.github.io/images/pes.jpg"/> <br>
<br>
<b>Lie Detection AI System</b> <br>
Advisor: [Prof. Srinivas K.S]<br>
* Built an **AI-based lie detection model** analyzing eye movement and facial expression data using **neural networks**. <br>
* Enhanced accuracy with a hybrid **Genetic + Hill Climbing optimization** strategy. <br>
* Implemented in **Python** using **NumPy, Pandas, and Scikit-learn**. <br>
<br>

<img width="150" height="75" src="https://abhishekch47.github.io/images/pes.jpg"/> <br>
<br>
<b>Breast Cancer Classification - Machine Learning Project</b> <br>
Advisor: [Prof. Srikanth H.R]<br>
* Designed a **classification model** using **KNN and Logistic Regression** to predict malignant vs. benign tumors. <br>
* Evaluated models using **accuracy and F1-score metrics**, achieving high precision. <br>
* Proposed future work exploring **SVM** and **Neural Networks** for improved results. <br>
* Technologies Used: **Python, NumPy, Pandas, Scikit-learn** <br>
