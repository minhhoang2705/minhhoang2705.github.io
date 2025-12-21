---
layout: about
title: about
permalink: /
subtitle: <a href='#'>AI Engineer @ Rainscales</a>

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

I'm an **AI Engineer** at Rainscales specializing in Computer Vision and Natural Language Processing, with hands-on experience building production-scale AI systems. Graduated with a B.Sc. in Artificial Intelligence from FPT University (GPA 3.2/4.0), where I developed expertise in deep learning, multimodal ML, and large language models.

My work spans the full ML lifecycle—from research and model optimization to deployment and MLOps. I leverage PyTorch, TensorFlow, and cloud-native technologies to develop AI solutions that drive measurable business impact.

---

## <i class="fas fa-brain"></i> Current Focus

My current research interests lie at the intersection of multimodal AI and production systems:

- **Vision-Language Models (VLMs)** — Developing multimodal systems that bridge visual understanding and natural language reasoning
- **Physical AI & Spatial Intelligence** — Building AI systems with spatial reasoning capabilities for real-world embodied applications
- **Retrieval-Augmented Generation (RAG)** — Architecting production-scale RAG pipelines for enterprise knowledge systems

---

## <i class="fas fa-code"></i> Featured Projects

#### <i class="fas fa-search"></i> IntelliRAG System
Architected cloud-native RAG platform on GKE with FastAPI, Kubernetes, and GPU-accelerated inference (vLLM/KServe), achieving high-throughput document processing and low-latency query response using Qdrant vector database, LangChain, and Sentence Transformers with comprehensive MLOps monitoring via Prometheus/Grafana/Evidently.

#### <i class="fas fa-video"></i> Action Retrieval from CCTV Footage
Evaluated text-video retrieval models (CLIP4Clip, Frozen-in-time, InternVideo) using Recall@k and Precision@k metrics to optimize action retrieval system, building data pipelines to ingest video-caption pairs into Milvus for low-latency retrieval using PyTorch and OpenCV.

#### <i class="fas fa-font"></i> Vietnamese Text Recognition
Built end-to-end Vietnamese OCR system with fine-tuned PaddleOCR models and Tkinter GUI, improving text recognition accuracy by 10% through synthetic data generation with diverse fonts optimized for advertising plates and product packaging.

---
