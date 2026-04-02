---
layout: project
title: ChristAIn
project_url: https://huggingface.co/Emmet-Allen/christAIn
---

<a href="{{ page.project_url }}" class="read-more">View Project</a>

ChristAIn: The Bible-based AI Model

ChristAIn is a trained model on a csv version of the bible, specifically using Low-Rank Adaptation (LoRA) to ensure that the Qwen model specifically highlights certain themes and keywords within the bible, while staying within the confines of my 8GBs of VRAM and optimizing for it's CUDA capabilities. Both models are GGUF enabled so they should be able to work in multiple LLM application formats, and can be hosted locally or within any of the major cloud providers.
