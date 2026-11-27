## Hi there 👋
## **About Me**
AI/ML engineer with a hybrid background:
- Agentic AI and spec driven development with Claude Code
- Google Cloud Platform professional ML engineer course
- 6+ years in **server-CPU software/hardware engineer** at Intel Corporation (**DevOps**, automation, data pipelines, large-scale debug)  
- M.Sc. **Robotics, Cognition & Intelligence (TUM)** focused on medical imaging, computer vision, and vision–language models  
- B.Sc. **Electrical Engineer (Universidad de Costa Rica)** focused on computer engineering

Current interests: Agentic AI, NLP and Computer Vision.

---

## **Selected Projects**
A mix of independent engineering builds and thesis research in medical vision-language models.

<table>
<tr>
<td><strong>flow: Spec-Driven Development Plugin</strong></td>
<td>
Claude Code plugin that makes AI coding agents reliable on real codebases: scripts and hooks, not the model, decide pass or fail.
<ul>
<li>Spec first: Gherkin acceptance criteria and interface contracts, checked by script</li>
<li>Quality gates: CRAP score, mutation testing and black-box QA</li>
<li>Parallel sub-agents, each held by a hook to the files of its own task</li>
<li>Independent verifier (Claude or Codex) that never sees the author's notes</li>
</ul>
</td>
<td><strong>Node.js, Claude Code (skills, hooks, sub-agents), Codex</strong></td>
<td>
<a href="https://github.com/sebtum/flow">Code</a>
</td>
</tr>

<tr>
<td><strong>MedAI Paper Lens</strong></td>
<td>
Local-first RAG assistant that answers research questions over full-text medical AI papers and cites the paper, section and page behind each claim.
<ul>
<li>LangGraph pipeline: safety filter, query rewriting, vector search with cross-encoder reranking, grounding check</li>
<li>Every retrieval choice backed by measurement: Recall@k, MRR, nDCG and LLM-as-judge, tracked in LangSmith</li>
<li>Runs fully offline on Ollama and streams answers token by token</li>
</ul>
</td>
<td><strong>Python, LangGraph, Ollama, Qdrant, FastAPI, Streamlit, LangSmith</strong></td>
<td>
<a href="https://github.com/sebtum/medai-paperlens">Code</a><br>
<!--<a href="https://LINK-TO-THESIS-PDF">Thesis PDF</a>-->
</td>
</tr>

<tr>
<td><strong>Personal Accountability App</strong></td>
<td>
Full-stack, installable web app (PWA) for planning projects and tracking time: estimated vs. actual hours, live timers with recovery of forgotten ones, and productivity charts.
</td>
<td><strong>TypeScript, Next.js, React, Supabase (PostgreSQL), Tailwind</strong></td>
<td>
<a href="https://github.com/sebtum/personal-accountability-app">Code</a><br>
<!--<a href="https://LINK-TO-THESIS-PDF">Thesis PDF</a>-->
</td>
</tr>

<tr>
<td><strong>Thesis: Diff-VQA Disease Classification (MIMIC-CXR)</strong></td>
<td>
Master's thesis (TUM) on vision-language models that read chest X-rays over time:
<ul>
<li>Context-aware Diff-VQA that explains what changed between a patient's earlier and current X-ray (PLURAL baseline)</li>
<li>Xplainer and BioViL-T adapted as zero-shot disease classifiers</li>
<li>CheXFound foundation model, evaluated zero-shot and fine-tuned</li>
<li>Result: ideal disease hints raise CIDEr (a text-similarity score) from 1.83 to 5.66; automatic hints reach 1.76, slightly below the baseline, so hint precision is the bottleneck</li>
</ul>
</td>
<td><strong>PyTorch · CLIP · BioViL · DINO · VLMs</strong></td>
<td>
<a href="https://github.com/sebtum/context-aware-diffvqa">Context-Aware Diff-VQA</a><br>
<a href="https://github.com/sebtum/Xplainer">Xplainer</a><br>
<a href="https://github.com/sebtum/biovil-t">BioViL-T</a><br>
<a href="https://github.com/sebtum/CheXFound">CheXFound</a>
</td>
</tr>

<tr>
<td><strong>DAC Time-Series Pipeline</strong></td>
<td>
Time-series platform for a Direct Air Capture pilot plant. It ingests messy industrial sensor data (gaps, stuck sensors, duplicates), shows scientists which numbers they can trust instead of silently cleaning them, and compares experiments in Grafana. Fully provisioned as code, with every design decision recorded.
</td>
<td><strong>Python, InfluxDB 3, PostgreSQL, Grafana, Docker</strong></td>
<td>
<a href="https://github.com/sebtum/dac-timeseries-pipeline">Code</a>
</td>
</tr>

<tr>
<td><strong>JobOpsV1</strong></td>
<td>
Agentic pipeline that turns a job posting into a tailored, ATS-ready CV and cover letter as PDFs. The LLM writes the prose; deterministic code checks every number, name and date against a fact base, so nothing is invented. 194 regression tests.
</td>
<td><strong>Python, Claude, Jinja2, WeasyPrint</strong></td>
<td>
<a href="https://github.com/sebtum/JobOpsV1">Code</a>
</td>
</tr>

</table>

<!--
**sebtum/sebtum** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
