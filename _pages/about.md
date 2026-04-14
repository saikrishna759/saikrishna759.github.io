---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an AI Scientist at <a href="https://www.uniphore.com/" style="color: #7289da; text-decoration: none;">Uniphore</a> and a Generative AI Intern at <a href="https://www.microsoft.com/" style="color: #7289da; text-decoration: none;">Microsoft</a>, with a Master's in Computer Science from the University of Illinois Urbana-Champaign (GPA: 4.0/4.0). My work focuses on retrieval-augmented generation, conversational AI, multimodal large language models, LLM evaluation, synthetic data generation, and robust AI systems. I enjoy building practical, production-ready LLM systems while also exploring research problems in trustworthiness, adversarial robustness, and efficient adaptation of foundation models.

My primary research and engineering interests include:
- Retrieval-Augmented Generation (RAG), re-ranking, and evaluation
- Trustworthiness, safety, and robustness of LLM / MLLM systems
- Conversational AI, agents, and workflow-driven reasoning systems
- Parameter-efficient fine-tuning, RL-based optimization, and multimodal learning


# 🔥 News
- *2026*: &nbsp;🎉🎉 Paper accepted to **ACL 2026** on image-based jailbreaking in multimodal RAG systems!
- *2025.07*: &nbsp;🚀 Started as **AI Scientist at Uniphore**, California, USA.
- *2025.01*: &nbsp;🚀 Started **Generative AI Internship at Microsoft**, Redmond, USA.
- *2024.10*: &nbsp;🎤 Presented research at **CIKM 2024 Workshop** (GenAI and RAG Systems for Enterprise) — Oral.
- *2024.05*: &nbsp;🚀 Joined **Novelis Inc.** as AI / Machine Learning Intern, Kennesaw, GA.
- *2023.08*: &nbsp;🎓 Started **Master of Computer Science at UIUC**.


# 📝 Publications

<table style="border-collapse:collapse; border:none; width:100%;">
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/mmpoisonrag_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>Image-Based Jailbreaking in Multimodal RAG Systems</strong><br/>
      <a href="https://arxiv.org/pdf/2502.17832">[paper]</a><br/>
      <strong>Saikrishna Sanniboina</strong> and collaborators<br/>
      <span style="color:purple">ACL 2026</span><br/>
      Developed adversarial image-based attacks that manipulate multimodal retrieval pipelines and steer vision-language models toward targeted incorrect outputs, achieving 43.4% ARM score. Demonstrated how image-based attacks can compromise the knowledge base integrity of multimodal RAG systems.
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/lore_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>Logit-Ranked Retriever Ensemble (LoRE)</strong><br/>
      <a href="https://arxiv.org/pdf/2410.10042">[paper]</a>
      <a href="https://sites.google.com/view/cikm2024-rag/papers?authuser=0#h.l53occc818yv">[workshop]</a><br/>
      <strong>Saikrishna Sanniboina</strong> and collaborators<br/>
      <span style="color:purple">CIKM 2024 Workshop (GenAI and RAG Systems for Enterprise)</span> <span style="color:red">(Oral)</span><br/>
      Engineered LoRE for question answering RAG pipelines, surpassing existing LLM ranking techniques with a 90% cost reduction. Integrates an ensemble of retrievers with logit-based ranking, achieving +14.95% F1 and +22.83% EM on SQuAD and NarrativeQA.
    </td>
  </tr>
</table>


# 📖 Education
- *2023.08 – 2024.12*, M.S. in Computer Science (GPA: 4.0/4.0), <a href="https://illinois.edu/" style="color: #7289da; text-decoration: none;">University of Illinois Urbana-Champaign</a>. Coursework: Using LLMs, Embodied LLMs, ML for Signals, ML Algorithms for LLMs, Software Engineering.
- B.Tech in Computer Science & Engineering (GPA: 3.8/4.0), Jawaharlal Nehru Technological University.


# 💻 Work Experience

<table style="border-collapse:collapse; border:none; width:100%;">
  <tr style="border:none;">
    <td style="width:180px; vertical-align:top; border:none; padding:8px 0;">
      <strong>Uniphore</strong>
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:50%;">
      <strong>AI Scientist</strong>
    </td>
    <td style="vertical-align:top; text-align:right; border:none; width:30%;">
      <em>California, USA</em><br/>
      Jul 2025 – Present
    </td>
  </tr>
</table>

- Designed and productionized RAG evaluation frameworks with standardized metrics (relevance, faithfulness, hallucination rate, context usage) and LLM-as-a-Judge pipelines, enabling safe iteration across enterprise deployments.
- Built and optimized domain-adapted RAG pipelines for customers (PayPal, Banco, Iberia, x-forge), covering document ingestion, embedding/index tuning, retrieval optimization, and domain-aware prompting.
- Developed multi-model benchmarking harnesses comparing open-source and proprietary LLMs (Databricks, Pegasus, GPT OSS 20B) across quality, latency, and cost.
- Investigated and mitigated critical AstraDB vector search failures, introducing fallback and hybrid retrieval strategies to stabilize production systems.
- Built automated prompt optimization pipelines using log signals and feedback loops, improving robustness using GEPA and TextGrad.
- Applied LoRA/PEFT and RL-based optimization to improve factuality, alignment, and robustness of LLMs used for evaluation and summarization.
- Designed intent lifecycle management and intent-to-workflow triggering systems using rule-based and LLM-driven mappings.

<table style="border-collapse:collapse; border:none; width:100%; margin-top:16px;">
  <tr style="border:none;">
    <td style="width:180px; vertical-align:top; border:none; padding:8px 0;">
      <strong>Microsoft</strong>
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:50%;">
      <strong>Generative AI Intern</strong>
    </td>
    <td style="vertical-align:top; text-align:right; border:none; width:30%;">
      <em>Redmond, USA</em><br/>
      Jan 2025 – Present
    </td>
  </tr>
</table>

- Developing advanced conversational AI solutions supporting multi-turn conversations, multi-intent detection, and diverse scenarios (Q&A, chitchat, action intents) leveraging Azure CLU services and Azure orchestration workflows.
- Increased model accuracy by 15% by reducing error rate to under 3% via schema-guided dataset (SGD) refinement.
- Developed a synthetic data generation pipeline to create single-utterance conversation samples with reference-level feedback.
- Leveraged GPT-4o-mini with Chain-of-Thought (CoT) prompting for accurate Q&A pair generation for personalized knowledge bases.
- Fine-tuned SLM Phi 3.5 mini in two iterative phases for action intent detection and entity recognition, achieving an 18% F1 increase with latency optimization via quantization.
- Integrated detected Q&A intents into Azure AI Search Index Retrieval systems to enhance knowledge-based response generation.

<table style="border-collapse:collapse; border:none; width:100%; margin-top:16px;">
  <tr style="border:none;">
    <td style="width:180px; vertical-align:top; border:none; padding:8px 0;">
      <strong>UIUC</strong>
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:50%;">
      <strong>Graduate Research Assistant</strong>, CS Dept.
    </td>
    <td style="vertical-align:top; text-align:right; border:none; width:30%;">
      <em>Urbana, IL, USA</em><br/>
      Sep 2023 – Jan 2025
    </td>
  </tr>
</table>

- Restructured dialogue state data for function-calling LLM agents and fine-tuned QLoRA-based LLMs for Task-Oriented Dialogues (restaurant booking), achieving 32% JGA under guidance from Gokhan Tur and Dilek Hakkani-Tur.
- Conducted comparative studies on DPO vs. traditional LLM fine-tuning, achieving a 5% performance improvement.
- Accelerated 70B LLM training speed by 10x using DeepSpeed, Accelerate, and FSDP in a multi-GPU setup.
- Enhanced Patient Notes Grading using CoT and ReAct techniques, achieving 92% accuracy; reduced latency by 20% through prompt prefilling (under Suma Bhat).
- Deployed RAG solutions for grading Medical Patient Notes using Flask and FastAPI, tested at the University of Chicago Medical College.
- Researched figurative and rhetorical question answering using GPT-4 and Claude-Sonnet with an LLM-as-judge framework.
- Implemented Reinforcement Learning (PPO) within a REALM-based framework for question answering and document retrieval.

<table style="border-collapse:collapse; border:none; width:100%; margin-top:16px;">
  <tr style="border:none;">
    <td style="width:180px; vertical-align:top; border:none; padding:8px 0;">
      <strong>Novelis Inc.</strong>
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:50%;">
      <strong>AI, Machine Learning Intern</strong>
    </td>
    <td style="vertical-align:top; text-align:right; border:none; width:30%;">
      <em>Kennesaw, GA, USA</em><br/>
      May 2024 – Oct 2024
    </td>
  </tr>
</table>

- Fine-tuned Llama3 to structure raw alloy production data, achieving 60% JGA, with efficient scaling deployed on AWS.
- Incorporated Pinecone and Qdrant vector indexes to optimize alloy data retrieval in a RAG setup for materials data.
- Deployed Alloy SEM image segmentation on AWS using UNet, achieving 90% accuracy, effectively replacing a ~$50k machine.
- Trained a stable diffusion model on segmented images, reducing the number of experiments needed for new alloy development.

<table style="border-collapse:collapse; border:none; width:100%; margin-top:16px;">
  <tr style="border:none;">
    <td style="width:180px; vertical-align:top; border:none; padding:8px 0;">
      <strong>VerSe Innovation</strong>
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:50%;">
      <strong>Machine Learning Engineer</strong>
    </td>
    <td style="vertical-align:top; text-align:right; border:none; width:30%;">
      <em>Bangalore, India</em><br/>
      Sep 2020 – Aug 2023
    </td>
  </tr>
</table>

- Enhanced Dailyhunt's recommendation engine via a two-tower model using PySpark and NLP, achieving a 25% improvement in top-k recommendations.
- Deployed a Two-Tower model with Ray for Josh's retrieval architecture, incorporating knowledge distillation from MTL-based ranking — 9% increase in recall@10 and CTR, 3% improvement in content diversity.
- Engineered an end-to-end discriminative face identification pipeline (batch & stream) using Adaptive Marginal Guidance (BRISQUE Algorithm), increasing accuracy by 20% and reducing latency by 200%.
- Engineered a Multi-Modal architecture for Video Captioning integrating ViT, BERT, and an image-grounded text decoder with cross-attention and KL divergence loss.
- Utilized Kafka for real-time data streaming across RecSys pipelines.
- Deployed task-based recommendation systems on AWS using fine-tuned vision-language models, achieving 25% reduction in response time.
- Led adoption of GCP Vertex AI and vision APIs alongside AWS Athena and PySpark, resulting in a 25x increase in system scalability.


# 🔨 Projects

- **[CIKM 24] Logit-Ranked Retriever Ensemble (LoRE)** [[paper]](https://arxiv.org/pdf/2410.10042): Engineered LoRE for RAG-based question answering, surpassing existing LLM ranking techniques with 90% cost reduction. Integrates an ensemble of retrievers with logit-based ranking; +14.95% F1 and +22.83% EM on SQuAD and NarrativeQA.
- **[ACL 26] Image-Based Jailbreaking in Multimodal RAG Systems** [[paper]](https://arxiv.org/pdf/2502.17832): Developed adversarial image attacks exploiting multimodal RAG vulnerabilities, leading VLMs to produce incorrect targeted outputs (43.4% ARM score).
- **WereWolfGPT**: Developed a ChatArena environment for self-play among LLM agents in the Werewolf game. Enhanced agents with reward functions enabling deception-based strategic behavior.
- **ai-research-bot**: Conversational AI platform with LangChain-based orchestration for document retrieval, summarization, and real-time AI research insights. Integrated multimodal features (text, audio, visual).
- **WhatsApp Chat Summarization**: Enhanced Llama2 via QLoRA (4-bit) targeting attention modules, reducing training loss from 2.13 to 0.87, outperforming baseline GPT models for conversational summarization.


# 👩‍💻 Academic Service
- Open to reviewing, collaborating, and contributing to research in LLMs, RAG, multimodal AI, and trustworthy AI systems.
