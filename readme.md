# 🧪 LLM Prompt Evaluation Lab

This is my first hands-on project to benchmark local LLMs using zero-shot and one-shot prompts across a variety of real-world tasks.

I scored 31 different models on a 0–5 scale in categories like:

- 🧠 Logic
- 🧮 Math
- 👨‍💻 Coding
- 🎨 Creativity
- 🩺 Medical terminology
- 🤖 Ambiguity handling
- 🛠️ Error resolution

## 📁 Contents

- `LLM_analysis.ipynb` – My Jupyter notebook using pandas + matplotlib
- `LLM-zero-one-shot.csv` – Raw scoring results
- `llm-accuracy-chart.png` – (Optional) output chart

## 📖 Related Blog Post

I wrote about this experiment and what I learned:
👉 [Read the blog post](https://chicanoinparis.github.io/Prompt-Engineer-Portfolio/2025/06/19/my-first-dive.html)

## 🧪 Try It Yourself

You can preview the notebook in your browser using nbviewer:

👉 [View notebook on nbviewer](https://nbviewer.org/github/ChicanoInParis/LLM-Prompt-Evauation-Lab/blob/main/LLM_analysis.ipynb)

Or clone the repo and run locally:

```bash
git clone https://github.com/ChicanoInParis/LLM-Prompt-Evauation-Lab.git
cd LLM-Prompt-Evauation-Lab
pip install pandas matplotlib
jupyter notebook
