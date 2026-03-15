---
layout: cv
title: Dimitrios Dagdilelis's CV
---

# Dimitrios Dagdilelis
Sr. ML Engineer

<div id="webaddress">
<a href="mailto:dimidagd@gmail.com">dimidagd@gmail.com</a>
| <a href="https://www.linkedin.com/in/dimidagd/">LinkedIn</a>
| <a href="https://scholar.google.com/citations?hl=en&user=29wM-aMAAAAJ">Google Scholar</a>
| <a href="https://dimidagd.github.io">dimidagd.github.io</a>
</div>

## Summary

ML Engineer, 6+ years of experience, specializing in 3D computer vision, multimodal data fusion, and production-grade MLOps. I build reliable ML systems, end-to-end data pipelines, conduct model research and training, evaluation frameworks, deployment, and monitoring. My work can be found in systems operating as you are reading these lines, processing thousands of datapoints and continuously improving. OS contributions to popular ML computer vision libraries. Comfortable working async and collaborating remotely. Proud Hugging Face open-source contributer.

## Selected Achievements

- Architected and deployed the multimodal perception stack for an operational autonomous passenger ferry, validating real world autonomy in dynamic maritime traffic and adverse environmental conditions.
- Owned foundation model based self supervised domain adaptation pipelines trained on millions of unlabeled images, deployed into production systems with continuous retraining loops.
- Designed tightly coupled deep sensor fusion in Bird’s Eye View representations and 3D multi object tracking frameworks across camera, LiDAR, and radar.
- Built production data flywheels integrating autolabeling, failure mining, drift monitoring, and structured regression testing to continuously improve long tail robustness.
- Optimized deep models with ONNX and TensorRT under strict real time latency constraints for deployment inside autonomy control loops.

## Professional Experience

`2020 – 2024`  
__AI Engineer, Autonomy__, ShippingLab, Copenhagen  

- Led development of a modular perception stack for an autopilot system, transforming research prototypes into production oriented components despite pandemic related constraints ([system preview](https://youtu.be/-U8SjiTo37w)).
- Designed a transformer based multimodal architecture for 3D scene understanding and multi object tracking, integrating camera, LiDAR, and radar to improve spatial reasoning and robustness in dynamic maritime traffic ([architecture preview](https://www.youtube.com/watch?v=8h_lvCD6gCU)).
- Developed the ML perception stack for Denmark’s first autonomous ferry operation, collaborating closely with downstream stakeholders to align algorithmic choices with operational constraints and reliability requirements ([operational deployment](https://www.youtube.com/watch?v=3ldAIurDOso)).
- Built and integrated automatic and semi automatic data annotation workflows, reducing manual labeling effort and accelerating iteration cycles ([data workflow preview](https://youtu.be/TZas_vM9sgI)).
- Operated under strict real time constraints, optimizing models with ONNX and TensorRT to meet maximum per frame latency requirements within the autonomy control loop.
- Designed dataset strategy and trained models on large scale real world datasets (tens of thousands of frames across multi day operations), balancing generalization and long tail robustness.
- Led safety validation campaigns and on water experimental demonstrations, translating perception performance into system level autonomy validation.
- Established reproducible evaluation pipelines spanning simulation and real world data to enable structured regression testing before deployment.

`2024 – Present`  
__Senior AI Engineer__, Danish Defence, Copenhagen  

- Led development of large scale vision foundation model pipelines using self supervised learning on millions of unlabeled images for domain adaptation under distribution shift.
- Architected and owned the full ML development lifecycle: data ingestion, pretraining, evaluation, observability, logging, deployment, and continuous retraining on fresh operational data.
- Deployed Vision Transformer based models into production systems processing thousands of data points per day, with structured monitoring and drift control mechanisms.
- Designed data flywheels to leverage streaming multimodal sensor data for iterative model improvement while maintaining reliability under high stakes operational constraints.
- Standardized CI/CD, model versioning, and reproducible experimentation practices across teams to enable safe and scalable model releases.

`2022`  
__Visiting AI Research Engineer__, SeaAI, Vienna  

- Built large scale training and evaluation pipelines for maritime visual datasets under evolving environmental distributions.
- Prototyped transition from 2D detection to depth aware 3D spatial reasoning models, emphasizing validation feasibility and deployment constraints.

## Education

`2020 – 2024`  
__Technical University of Denmark__  
PhD in Multimodal Machine Learning [thesis]((https://orbit.dtu.dk/files/388731705/Thesis_2_.pdf))

## Technical Skills

**Autonomy & 3D Perception**  
3D object detection, multi object tracking, trajectory prediction, multimodal fusion, Bird’s Eye View representations, scene understanding under real world constraints  

**Foundation Models & Learning**  
Vision Transformers, contrastive self supervised learning, domain adaptation, large scale pretraining, active learning, continuous retraining pipelines  

**Deployment & Optimization**  
PyTorch, TensorFlow, ONNX, TensorRT, Python, C++ familiarity, real time inference optimization, production observability and logging  

**MLOps & Infrastructure**  
Docker, CI/CD, experiment tracking, reproducible ML pipelines, monitoring, data flywheel design  

