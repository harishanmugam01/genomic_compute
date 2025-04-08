# Secure & Scalable Genomic Computing in HPC Environments

This repository presents two co-authored technical research documentation reports, authored by Harihara Sudhan Shanmugam (Computational Research Technician) in collaboration with Chamodi Korala Hewage (Research System Developer) at Buckinghamshire New University. The work was carried out within the Pathogen Genomics Unit and addresses real-world system design challenges in high-performance computing (HPC) environments tailored to biomedical research.

These reports document the secure architectural design and deployment of hybrid HPC infrastructures and AI-powered bioinformatics systems, developed to support sensitive genomic variant analysis. The project integrates container security, cloud-native orchestration, and model optimization techniques to deliver both high computational performance and robust data protection, ensuring compliance and scalability in research-intensive environments.

This page serves as a **summary portal** for both projects. Interested reviewers, supervisors, or evaluators may directly access the **technical research documentation reports** by clicking the PDF links below.

## 📁 Repository Contents

### 📄 1. 1. [HPC_BioBERT_System_Architecture_Technical_Report.pdf](./HPC_BioBERT%20System%20Architecture.Report.pdf)
> **Scalable Genomic Processing through Hybrid HPC-Cloud Integration and AI-Driven Annotation**

- Implements a hybrid architecture combining Slurm-managed HPC clusters with Microsoft Azure cloud resources.
- Integrates BioBERT, a large language model for automated genomic variant annotation, optimized with GPU acceleration and quantization.
- Demonstrates:
  - 162.5% increase in sample throughput
  - 62.4% reduction in processing time
  - 36.5% cost efficiency improvement
- Focus: Intelligent job scheduling, GPU monitoring, MPI optimization, and pipeline orchestration.

### 📄 2. 2. [HPC_BioBERT_Secure_Architecture_Technical_Report.pdf](./HPC_BioBERT%20Secure%20Architecture.Report.pdf)
> **Secure Genomic Computing: Defence-in-Depth in a Hybrid HPC Cloud Environment**

- Implements encryption protocols (AES-256-GCM + RSA-4096), federated identity (OAuth 2.0 + PKCE), and GPU memory protection.
- Applies OWASP and STRIDE threat modeling to secure genomic pipelines.
- Results:
  - 99.8% effectiveness against simulated attacks
  - 3–8% performance overhead
  - 97.8% NIST 800-53 compliance
- Focus: API hardening, container security (CIS benchmarks), GPU isolation, and secure BioBERT API deployment.


## 👨‍💻 Author's Role

**Harihara Sudhan Shanmugam** led and authored both reports as part of a multidisciplinary hpc systems engineering team. His responsibilities included:

- Designing and testing secure and scalable HPC-cloud systems.
- Integrating and optimizing AI LLM models (BioBERT) within genomic workflows.
- Performing security testing and ensuring compliance (NIST, HIPAA, GDPR).
- Developing automation scripts for Slurm, MPI tuning, and containerized job orchestration.
