# Secure & Scalable Genomic Computing in HPC Environments

This repository hosts final draft of two technical reports authored by Harihara Sudhan Shanmugam.
These documents reflect real-world system architecture, deployment, and security engineering practices implemented to advance genomic research through high-performance computing (HPC), cloud technologies, and secure AI model integration.

## 📁 Repository Contents

### 📄 1. 1. [HPC_BioBERT_LLM_System_Design.pdf](./HPC_BioBERT_LLM_System_Design.pdf)
> **Scalable Genomic Processing through Hybrid HPC-Cloud Integration and AI-Driven Annotation**

- Implements a hybrid architecture combining Slurm-managed HPC clusters with Microsoft Azure cloud resources.
- Integrates BioBERT, a large language model for automated genomic variant annotation, optimized with GPU acceleration and quantization.
- Demonstrates:
  - 162.5% increase in sample throughput
  - 62.4% reduction in processing time
  - 36.5% cost efficiency improvement
- Focus: Intelligent job scheduling, GPU monitoring, MPI optimization, and pipeline orchestration.

### 📄 2. 2. [HPC_BioBERT_Secure_Design.pdf](./HPC_BioBERT_Secure_Design.pdf)
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
- Integrating and optimizing AI models (BioBERT) within genomic workflows.
- Performing security testing and ensuring compliance (NIST, HIPAA, GDPR).
- Developing automation scripts for Slurm, MPI tuning, and containerized job orchestration.
