<img src="banner.svg" alt="Suning Hong — Computer Science + Mathematics, Hamilton College" width="100%"/>

### Hi, I'm Suning!

I build AI systems that know when they might be wrong: agent pipelines where a model does the reading, deterministic code makes the final call, and every result comes with the reason behind it.

I'm finishing a double major in Computer Science and Mathematics at Hamilton College in 3.5 years, graduating December 2026, and moving to San Francisco in 2027. I like building products people can actually use and trust.

### What I am working on

- **GiSuN** (CS senior seminar, team of two): a Chrome extension and multi-agent pipeline that reads ChatGPT answers and flags claims a reader should question
  - Checks six kinds of problems: unsourced statistics, wrong numbers, loaded wording, overgeneralizations, vague attributions and unsupported cause-and-effect claims
  - I built the number-checking part: it looks up the official figure from BLS, Census, FRED, CDC, World Bank and Data Commons, and **code, not the model, decides** whether the claim matches
  - Runs a self-hosted Qwen2.5-32B model on Hamilton's GPU cluster, with a Plan → Task → Check → Judge agent loop that rejects and retries decisions that aren't backed by evidence
  - Designed the evaluation: a 180-claim test set with known answers (**F1 0.98**, zero false alarms), plus error analysis that raised unsourced-statistic detection from **F1 0.65 to 0.81**

### What I have worked on
- **AI for scientific research**: summer research on LLM agents for interpreting genetic variants, supported by a research grant
- **Data Intern, Hamilton College Health Center** (2024–2026): working with real campus health data

Outside of code, I work comfortably in both English and Mandarin.

---

### 🔍 Featured work

<table>
<tr>
<td width="50%" valign="top">

#### [GiSuN](https://github.com/gka-90/GiSuN)
**Fact-checking for chatbot answers**

A Chrome extension and multi-agent pipeline (Plan → Task → Check → Judge) that flags unsourced, wrong or slanted statements in ChatGPT answers.

- Checks numbers against **6 official data sources** (BLS, Census, FRED, CDC, World Bank, Data Commons)
- The model reads the claim; **code decides the verdict**
- Built my own 180-claim test set: **F1 0.98**, zero false alarms
- Raised unsourced-statistic detection from **F1 0.65 → 0.81** on a public benchmark

`Python` `FastAPI` `vLLM` `Qwen2.5-32B` `JavaScript` `Slurm`

</td>
<td width="50%" valign="top">

#### [AI Agents for Scientific Research](https://github.com/ashkankhilwatgar/AI-Agents-for-Scientific-Research)
**LLMs for gene variant interpretation**

Summer research project: a framework for using LLM agents to help interpret genetic variants.

`Python` `LLM agents`

</td>
</tr>
</table>

---

### 🧰 Toolbox

### 🧰 Toolbox

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Assembly](https://img.shields.io/badge/Assembly-6E4C13?style=flat-square)

**AI / LLMs**
![LLM agents](https://img.shields.io/badge/LLM_agents-0F1B3D?style=flat-square) ![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=flat-square) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![Qwen2.5](https://img.shields.io/badge/Qwen2.5-615CED?style=flat-square)

**Backend & infrastructure**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST_APIs-0F1B3D?style=flat-square) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Slurm HPC](https://img.shields.io/badge/Slurm_HPC-0F1B3D?style=flat-square) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Data & analysis**
![R Markdown](https://img.shields.io/badge/R_Markdown-2C3E50?style=flat-square&logo=rstudioide&logoColor=white) ![Statistical modeling](https://img.shields.io/badge/Statistical_modeling-0F1B3D?style=flat-square) ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

---

### 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suning-hong-a97356282/)
[![Email](https://img.shields.io/badge/Email-0F1B3D?style=flat-square&logo=gmail&logoColor=white)](mailto:hongsuning293@gmail.com)
