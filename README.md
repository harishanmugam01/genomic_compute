# Secure & Scalable Genomic Computing System in HPC Infrastructure

This repository presents two co-authored technical research documentation reports, authored by Harihara Sudhan Shanmugam (Computational Research Technician) in collaboration with Chamodi Korala Hewage (Research System Developer) at Buckinghamshire New University. The work was carried out within the Pathogen Genomics Unit and addresses real-world system design challenges in high-performance computing (HPC) environments tailored to biomedical research.

These reports document the secure architectural design and deployment of hybrid HPC infrastructures and AI-powered bioinformatics systems, developed to support sensitive genomic variant analysis. The project integrates container security, cloud-native orchestration, and model optimization techniques to deliver both high computational performance and robust data protection, ensuring compliance and scalability in research-intensive environments.

This page serves as a **summary portal** for both projects. Interested reviewers, supervisors, or evaluators may directly access the **technical research documentation reports** by clicking the PDF links below.

## 📁 Repository Contents

### 📄 1. 1. [HPC_BioBERT_ScalableCompute_Technical_Report.pdf](./hpc_biobert_scalablecompute.pdf)
> **Scalable Genomic Processing through Hybrid HPC-Cloud Integration and AI-Driven Annotation**

- Implements a hybrid architecture combining Slurm-managed HPC clusters with Microsoft Azure cloud resources.
- Integrates BioBERT, a large language model for automated genomic variant annotation, optimized with GPU acceleration and quantization.
- Designed GPU-aware batching algorithm for efficient BioBERT inference based on real-time memory estimation.
- Demonstrates:
  - 162.5% increase in sample throughput
  - 62.4% reduction in processing time
  - 36.5% cost efficiency improvement
- Focus: Intelligent Job Scheduling, Algorithm Development, GPU monitoring, MPI optimization, and Pipeline Orchestration.

### 📄 2. 2. [HPC_BioBERT_SystemSecurity_Technical_Report.pdf](./hpc_biobert_systemsecurity.pdf)
> **Secure Genomic Computing: Defence-in-Depth in a Hybrid HPC Cloud Environment**

- Implements encryption protocols (AES-256-GCM + RSA-4096), federated identity (OAuth 2.0 + PKCE), and GPU memory protection.
- Implemented secure annotation algorithm with encrypted model loading and input/output validation logic.
- Applies OWASP and STRIDE threat modeling to secure genomic pipelines.
- Results:
  - 99.8% effectiveness against simulated attacks
  - 3–8% performance overhead
  - 97.8% NIST 800-53 compliance
- Focus: API Hardening, Security Algorithm Design, Container Security, GPU isolation, and Secure BioBERT API deployment.

- ### 📄 2. 3. [Letter_of_Reference_Secure_GenomicCompute_Development.pdf](./referenceletter_secure_system_development.pdf)
> **Reference Letter on Collaborative System Development**

- Documents the collaborative work between Harihara Sudhan Shanmugam and Chamodi Korala Hewage.
- Highlights specific contributions to system architecture, algorithm design, and security implementation.
- Details the cross-functional development approach that led to successful project outcomes.

## 👨‍💻 Author's Role

**Harihara Sudhan Shanmugam** led and authored both reports as part of a multidisciplinary hpc systems engineering team. His responsibilities included:

- Designing and testing secure and scalable HPC-cloud systems.
- Integrating and optimizing AI LLM models (BioBERT) within genomic workflows.
- Performing security testing and ensuring compliance (NIST, HIPAA, GDPR).
- Developing automation scripts for Slurm, MPI tuning, and containerized job orchestration.
- Developing algorithmic logic for secure variant annotation and GPU-optimized BioBERT inference.
