# MA-RAG Short Story – CMPE 297 Special Topics in AI

This repository contains my **short story project** for  
**CMPE 297: Special Topics in AI – Agents, RAG & Beyond**.

The project is based on the research paper:

> **MA-RAG: Multi-Agent Retrieval-Augmented Generation via Collaborative Chain-of-Thought Reasoning**  

---

## 📺 Project Walkthrough Video

Full video walkthrough (slides + Medium article explanation):

👉 **YouTube:** https://youtu.be/69lYHCaMxtk

In the video, I:

- Explain the motivation behind MA-RAG and limitations of vanilla RAG  
- Walk through my presentation slide-by-slide  
- Summarize my Medium article and key insights from the paper  

---

## 📄 Research Paper

Original paper:

- **Title:** MA-RAG: Multi-Agent Retrieval-Augmented Generation via Collaborative Chain-of-Thought Reasoning  
- **Authors:** Thang Nguyen, Peter Chin, Yu-Wing Tai  
- **arXiv PDF:** https://arxiv.org/pdf/2505.20096  

The paper proposes a training-free, modular multi-agent RAG framework that:

- Decomposes complex questions into subtasks (planning, disambiguation, evidence extraction, answer synthesis)  
- Assigns each stage to a specialized agent communicating via chain-of-thought  
- Achieves state-of-the-art or highly competitive results on benchmarks like NQ, HotpotQA, 2WikimQA, and TriviaQA across different base LLMs.  

---

## ✍️ Medium Article

I wrote a Medium article that re-tells the MA-RAG paper in an accessible, story-driven way:

👉 **Medium:**  
https://medium.com/@rishikeshavlal.patel/when-one-llm-isnt-enough-how-ma-rag-uses-a-team-of-agents-to-fix-rag-s-biggest-problems-1ed535baa36d?postPublishedType=initial

The article covers:

- Why traditional RAG still fails on ambiguous and multi-hop questions  
- How MA-RAG turns RAG into a **team sport** with four agents  
- A concrete example (the Jupp Heynckes European Cup Final question)  
- Benchmark results and ablation studies showing why each agent matters  
- Why this multi-agent approach is important for the future of agentic AI  

---

## 🖼️ Slides (Presentation PDF)

This repo also contains the PDF version of my presentation:

- `Short-Story-Presentation.pdf`

The slide deck includes:

- Motivation and problem setup  
- Visual comparison: **Vanilla RAG vs MA-RAG**  
- Architecture diagram of the four-agent pipeline  
- Step-by-step reasoning example  
- Key quantitative results and ablations  
- Takeaways for agentic RAG and future directions  

---

## 📂 Repository Structure

```text
.
├── Short-Story-Presentation.pdf   # Slide deck used in the video
├── Medium_article.pdf             # Export of the Medium article (optional)
├── README.md                      # This file
└── Research_paper.pdf             # arxiv paper
```

> Note: The actual MA-RAG implementation and experimental code are provided by the original authors in their own repository.  

---

## 🙌 Acknowledgements

- Authors of MA-RAG for the research and open-source implementation  
- Course: **CMPE 297 – Special Topics in AI**  
- Tools used: Large Language Models, RAG/agentic literature, and standard presentation + video editing tools

If you have questions, suggestions, or feedback about this project, feel free to open an issue or reach out!
