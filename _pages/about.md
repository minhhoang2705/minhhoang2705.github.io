---
layout: about
title: About
permalink: /
subtitle: <a href='#'>AI Engineer</a>

profile:
  align: right
  image: profile_pic.png  # ✏️ TODO - Replace assets/img/profile_pic.png with your headshot
  image_circular: false # Set to true if you want circular profile picture
  more_info: >
    <p>Ho Chi Minh City, Vietnam</p>

selected_papers: true # TEMPORARILY DISABLED - Enable after adding publications to papers.bib
social: true # Shows social icons at the bottom (configured in _data/socials.yml)

# DISABLED - No news/announcements section
announcements:
  enabled: false # DISABLED - no news items
  scrollable: true
  limit: 5

# DISABLED - No blog posts
latest_posts:
  enabled: false # DISABLED - no blog
  scrollable: true
  limit: 3
---

I'm **Tran Hoang Minh** — an AI Engineer who specializes in building end-to-end, production-ready AI systems, leveraging the latest open-source models and frameworks. My expertise spans computer vision and large language models, deploying robust solutions from proof of concept to full-scale production.

**What I do best:** Transforming research-stage models into reliable, scalable AI services. I design model architectures, build MLOps pipelines, automate data flows, and implement monitoring for production stability. My tech stack covers Python, PyTorch, TensorFlow, YOLO, HuggingFace, transformers, LangChain, CI/CD with GitHub Actions, DVC/MLFlow, and infrastructure with Terraform. I utilize AI coding agents to accelerate solution design and system orchestration, ensuring rapid turnaround from prototype to deployment.

---

## <i class="fas fa-brain"></i> Current Focus

My research interests span production-scale multimodal AI and embodied intelligence systems:

- **Vision-Language Models (VLMs) & Vision-Language-Action (VLA)** – Developing multimodal systems that combine visual understanding with language reasoning and actionable outputs for robotic and embodied AI applications

- **Physical AI & Robotics** – Building AI systems with spatial reasoning, perception, and control capabilities for real-world embodied applications, with focus on humanoid robotics infrastructure

- **Production AI Systems** – Architecting end-to-end AI pipelines including multimodal serving, RAG systems, vector database optimization, and GPU-accelerated inference on production infrastructure

- **Infrastructure & Deployment** – Designing robust MLOps systems for production workloads, including containerization, orchestration, monitoring, and cost-optimized compute management

---

## <i class="fas fa-tools"></i> Technical Expertise

<div class="row">
  <div class="col-sm-6">
    <h5><i class="fas fa-terminal"></i> Programming Languages</h5>
    <p>Python • C</p>
  </div>
  <div class="col-sm-6">
    <h5><i class="fas fa-robot"></i> AI/ML Frameworks</h5>
    <p>PyTorch • TensorFlow • YOLO • HuggingFace Transformers • Scikit-learn • LangChain • LangGraph • Pandas • NumPy • OpenCV</p>
  </div>
</div>

<div class="row mt-3">
  <div class="col-sm-6">
    <h5><i class="fas fa-cogs"></i> MLOps & DevOps</h5>
    <p>Docker • Kubernetes (GKE) • Terraform • GitHub Actions • Prometheus • Grafana • Loki • MLFlow • DVC • Helm • KServe • vLLM</p>
  </div>
  <div class="col-sm-6">
    <h5><i class="fas fa-database"></i> Databases & Vector Stores</h5>
    <p>PostgreSQL • Microsoft SQL Server • Milvus • Qdrant</p>
  </div>
</div>

<div class="row mt-3">
  <div class="col-sm-12">
    <h5><i class="fas fa-cloud"></i> Cloud Platforms</h5>
    <p>Google Cloud Platform (GKE, GCS, Compute Engine) • NGINX • FastAPI</p>
  </div>
</div>

---

## <i class="fas fa-code"></i> Featured Projects

#### <i class="fas fa-search"></i> IntelliRAG System
Architected cloud-native RAG platform on GKE with FastAPI, Kubernetes, and GPU-accelerated inference (vLLM/KServe), achieving high-throughput document processing and low-latency query response using Qdrant vector database, LangChain, and Sentence Transformers with comprehensive MLOps monitoring via Prometheus/Grafana/Evidently.

#### <i class="fas fa-video"></i> Action Retrieval from CCTV Footage
Evaluated text-video retrieval models (CLIP4Clip, Frozen-in-time, InternVideo) using Recall@k and Precision@k metrics to optimize action retrieval system, building data pipelines to ingest video-caption pairs into Milvus for low-latency retrieval using PyTorch and OpenCV.

#### <i class="fas fa-font"></i> Vietnamese Text Recognition
Built end-to-end Vietnamese OCR system with fine-tuned PaddleOCR models and Tkinter GUI, improving text recognition accuracy by 10% through synthetic data generation with diverse fonts optimized for advertising plates and product packaging.

---
