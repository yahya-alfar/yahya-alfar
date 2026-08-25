# Yahya Y. Alfar

**Machine Learning Engineer | Computer Vision | Applied AI Systems**

Riyadh, Saudi Arabia

I build applied AI systems around complex real-world problems, with experience spanning **medical imaging, computer vision, dataset engineering, model evaluation, workflow design, and automation**.

My work typically starts by structuring the problem and its data flow before moving into implementation, controlled experimentation, evaluation, and iterative refinement.

---

## Selected Work

### [MRI → Synthetic CT for Radiotherapy](https://github.com/yahya-alfar/synthetic-ct-radiotherapy-case-study)

Deep learning research focused on generating pelvic synthetic CT images from MRI for radiotherapy planning.

- Curated and quality-controlled paired MRI/CT cohorts with frozen train, validation, and test splits
- Fine-tuned a pretrained **Med2Transformer**, improving male validation MAE from **73.1 to 65.1 HU (~11%)**
- Evaluated cross-cohort generalization, reducing female zero-shot validation MAE from **261.5 to 102.0 HU**
- Performed female-specific fine-tuning achieving **87.4 HU validation MAE**
- Evaluated model behavior using **MAE, SSIM, PSNR, anatomical consistency, and tissue-level error analysis**
- Used validation-driven model selection while keeping test cohorts locked during development

**Focus:** Medical Imaging · PyTorch · MRI/CT · Synthetic CT · Model Fine-Tuning · Generalization · Error Analysis

[View full technical case study →](https://github.com/yahya-alfar/synthetic-ct-radiotherapy-case-study)

---

### [Cephalometric Landmark Localization](https://github.com/yahya-alfar/cephalometric-landmark-localization)

Computer vision research for automated localization of anatomical landmarks in lateral cephalometric X-ray images.

* Worked with **600 annotated X-ray images** and **15 cephalometric landmarks**
* Trained and evaluated **YOLO11** and **HRNet-W48**
* Built a structured training and evaluation pipeline covering ROI processing, resizing, letterboxing, augmentation, inference, and test-time augmentation
* Performed landmark-level error analysis in millimeters to identify difficult anatomical regions and guide model refinement

**Focus:** Computer Vision · PyTorch · YOLO11 · HRNet-W48 · X-ray Imaging · Landmark Localization
[View full technical case study →](https://github.com/yahya-alfar/cephalometric-landmark-localization)

---

### [Workflow & Approval Systems](https://github.com/yahya-alfar/workflow-approval-system-case-study)

Designed a multi-stage workflow platform around explicit roles, permissions, request states, review stages, and controlled transitions.

* Modeled operational processes as structured workflows rather than disconnected forms
* Designed role-based interactions across applicants, reviewers, approvers, auditors, and administrators
* Implemented request tracking, session management, access control, and traceable approval handoffs
* Structured the system around clear states and transitions to make multi-user operations understandable and auditable

**Focus:** Workflow Modeling · System Design · Role-Based Access · PostgreSQL · Node.js · REST APIs
[View full technical case study →](https://github.com/yahya-alfar/workflow-approval-system-case-study)

---

### [IoT Monitoring & Automation](https://github.com/yahya-alfar/iot-monitoring-automation)

Built an end-to-end environmental monitoring workflow connecting physical sensing, cloud data, decision logic, and automated actions.

* Integrated **ESP32-based sensing** with **Firebase** for real-time data collection
* Built **n8n** workflows for threshold validation, persistent logging, Google Sheets integration, and automated email alerts
* Separated sensing, storage, decision logic, and notification into clear system components

**Focus:** ESP32 · Firebase · n8n · Automation · Data Validation · Event-Driven Workflows
[View full technical case study →](https://github.com/yahya-alfar/iot-monitoring-automation)

---

## Private / Ongoing Work

### Medical Imaging Research Platform

Designed and developed an interactive platform supporting a medical-imaging research workflow across **data discovery, MRI/CT review, quality control, human curation, experiment preparation, and model-result analysis**.

The platform was designed to make underlying research processes visible and traceable rather than treating data preparation and evaluation as hidden backend operations.

**Implementation details and source code are currently private while intellectual-property registration is in progress.**

---

## How I Approach Problems

I tend to work from the structure of the problem outward:

**Understand the workflow → identify constraints and decision points → structure the data → define quality gates → build the system or experiment → evaluate failures → refine**

I am particularly interested in problems where **AI, software systems, data, and real operational workflows intersect**.

---

## Technical Focus

**Machine Learning & AI**
Python · PyTorch · CNNs · Transformers · GANs · Fine-Tuning · Transfer Learning · Model Evaluation

**Computer Vision & Medical Imaging**
OpenCV · MRI/CT · X-ray Imaging · Synthetic CT · Image Registration · Landmark Localization · Image Preprocessing

**Systems & Data**
Workflow Design · Process Decomposition · PostgreSQL · Node.js · REST APIs · Firebase · Data Quality Control

**Automation & Tools**
n8n · Jupyter Notebook · Google Colab · Git

---

## Connect

- **LinkedIn:** [linkedin.com/in/yahya-y-alfar-415a9432b](linkedin.com/in/yahyaalfar/)
- **Email:** [yahya.a.alfar@gmail.com](mailto:yahya.a.alfar@gmail.com)
