---
<!-- layout: archive -->
title: "Work Experience"
permalink: /work-experience/
author_profile: true
---

<img width="150" height="75" src="https://abhishekch47.github.io/images/teradata.jpg"/> <br>
<br>
<b>Software Engineer Intern (San Diego, CA / Remote) </b> <br>
Teradata Corporation <br>
May 2024 -- Present <br>

* **Compiler-Driven Performance Optimization**: Working on Teradata’s **query compiler and execution engine**, enhancing performance through **LLVM-based code generation** in C++. Focused on optimizing **floating-point operations** and **vector computation pipelines** to improve analytical query throughput on large-scale data systems. <br>
* **LLVM IR Generation and Optimization**: Implemented new modules in Teradata’s internal **CGI (Code Generation Infrastructure)** to dynamically generate **LLVM Intermediate Representation (IR)** for math and vector functions. Introduced custom passes for instruction selection, constant folding, and loop unrolling, enabling fine-grained compiler-level optimizations at runtime. <br>
* **Floating-Point Precision and Compute Efficiency**: Developed multi-precision compute paths (**FP16**, **FP32**, **FP64**) and benchmarked their trade-offs in accuracy versus performance. Leveraged **fast-math** optimizations and fused-multiply-add operations where safe, achieving up to **1.4× speedup** on floating-point intensive workloads. <br>
* **Vector Search Acceleration (HNSW)**: Integrated **Hierarchical Navigable Small World (HNSW)** indexing within the compiler pipeline to accelerate vector similarity search for analytic workloads. Tuned hyperparameters (**M**, **efConstruction**, **efSearch**) and optimized search traversal logic to minimize memory overhead and improve retrieval latency. <br>
* **Runtime Specialization and Profiling**: Used **LLVM’s MCJIT framework** to JIT-compile specialized function variants at runtime, reducing branching and improving instruction cache efficiency. Built profiling hooks to collect runtime metrics such as IPC, instruction count, and cache utilization—feeding insights back into compiler heuristics. <br>
* **Performance Analysis and Validation**: Employed **Clang sanitizers**, **perf**, and **Linux profiling tools** to evaluate instruction throughput and memory footprint across different precision modes. Validated optimization impact through controlled benchmarking using synthetic vector datasets and production query traces. <br>
* **Key Impact**: Strengthened Teradata’s compiler infrastructure for next-generation analytic workloads—improving both **numerical performance** and **codegen reliability**. This work laid the foundation for integrating **AI-optimized compute paths** into the company’s data engine. <br>
* **Technologies Used**: C++, LLVM, MCJIT, Clang, HNSW, Python, perf, Git, Linux <br>

<br>


<img width="175" height="75" src="https://abhishekch47.github.io/images/apple.jpg"/> <br>
<br>
<b>Software Engineer (Hyderabad, India) </b> <br>
Apple Inc <br>
Jul 2021 -- Aug 2024 <br>

* **Platform Development for Control Plane Monitoring**: Developed a **full-stack web platform** with a **sunburst**
alert view using **ancestral mapping** for node hierarchies and integrated Grafana dashboards for real-time metrics, using
**React**, **Django**, and **Redis**. Enhanced Apple’s control plane infrastructure efficiency by 75%. <br>
* **Slack-Based Diagnostics Microservice**: Developed a **microservice** in Golang integrated with Slack for Apple’s
cloud infrastructure, enabling users to trigger API calls through button actions. This streamlined access to diagnostic
data, reducing manual effort and response times, and improving overall operational efficiency by 33%. <br>
* **Telemetry Dashboard for Apple Cloud Infrastructure**: Built a **full-stack web application** using **React**,
**Node.js** and **Mongo** for Apple’s Cloud SRE teams, providing real-time insights on change requests (CRs), high-priority
incidents, and traffic analysis. Integrated alert management, improving operational efficiency by 40%. <br>
* **Orchestrated CLI Tool for Automated Change Requests and Tickets**: Built an CLI tool for Apple’s Backbone,
automating CR and ticket workflows, reducing processing time from 8-10 mins to 2 mins per CR.<br>
* **Scalable Kubernetes Deployment and Load Optimization**: Architected a Kubernetes deployment with modular
pods and containers, using GSLB for load distribution, which improved performance for over 8000 Apple Cloud users.<br>
* **CI/CD Automation for Docker and Kubernetes Deployment**: Engineered **CI/CD** pipelines using jenkins for
automated Docker image creation, Artifactory publication, and Kubernetes deployment, reducing deployment time by
30% and minimizing manual errors. <br>
* **Expertise in Apple Backbone L1 Architecture and Routing**: Resolved routing issues and managed various circuit
types within Apple’s Backbone L1 architecture, configuring Juniper MX2020 routers and **routing policies**, and utilizing
expertise in Arista and Cisco hardware to enhance network reliability <br>
* **Memory Leak Resolution and Hardware Performance Enhancement**: Resolved memory leaks on Juniper
devices through strategic reloads, addressed log filtering issues, and managed air filter swaps and FPC failures, resulting
in a 25% improvement in hardware performance.<br>
* **Team Leadership and Training**: Led the training of a new team in Cork, Ireland, as the Subject Matter Expert (SME) on Juniper devices. Delivered comprehensive training on JTAC procedures, Juniper hardware architecture, CLI usage, and traffic draining processes.
 <br>



<img width="85" height="75" src="https://abhishekch47.github.io/images/aruba.jpg"/> <br>
<br>
<b>Software Developer Intern (Bengaluru, India) </b> <br>
Aruba Networks, HPE <br>
Jan 2021 -- May 2021 <br>

* **Static PortFilter Implementation**: Seamlessly integrated the Static PortFilter feature within the Aruba OVA (Open Virtual Appliance) environment, enabling precise control over both inbound and outbound traffic. <br>
* **Network Security Enhancement**: Significantly strengthened network security by enforcing traffic management policies, contributing to a more robust and controlled networking infrastructure. <br>
* **Technologies Used**: Utilized C, Python, Docker, and Gerrit to implement and optimize the feature, ensuring seamless functionality in the virtual appliance environment. <br>






