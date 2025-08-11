# 🤖 Multi-Agent Coding Assistant with Fine-Tuned Code Model
## 📌 Project Overview
This project creates a **CrewAI-based multi-agent coding assistant** powered by a **fine-tuned Hugging Face code model**.  
Agents collaborate to **create, debug, and review** Python code, with their discussion displayed interactively in **Colab** using `ipywidgets`.

## 🛠 Features
- **Pretrained Model Fine-Tuning**: LoRA fine-tuning on the **CodeAlpaca** dataset for improved code generation.
- **Multi-Agent Workflow**:
  - **Creator** — writes initial code
  - **Debugger** — fixes bugs
  - **Reviewer** — optimizes and documents
- **Interactive Output**: Agent conversation displayed in real-time inside Colab notebooks.
- **Colab-Ready**: Fully optimized for running in free-tier Colab GPUs.

## 📅 Development Timeline
The project was completed in **two phases** (Planning + Execution) with **rest days** in between.  
See [`Weekly report.docx`] for a full day-by-day breakdown.

## 🚀 Quick Start
1. **Clone the repo**  
   ```bash
   git clone https://github.com/SezhiyanP4597/Agentic_.git
   cd Agentic_
2. **Open in Colab**

  -Upload notebook.ipynb to Google Colab
  -Ensure GPU is enabled in Runtime settings
  -Run the Notebook
  -Fine-tune the model
  -Test generation
  -Watch agents collaborate
