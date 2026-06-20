# ✦ Groq AI Persona Dashboard

A premium, portfolio-grade Conversational AI platform engineered with the **Gradio 6.0** framework and optimized with **Groq Cloud's LPU inference engine**. The application interfaces directly with the **LLaMA 3.3 70B Versatile** model to provide streaming, context-aware responses across custom professional persona presets.

---

## 🚀 Architectural & Design Features

* **Advanced Chat Engine:** Full token-by-token streaming capabilities using Python generators with asynchronous-like responsiveness.
* **Contextual Persona Middleware:** Features specialized system prompt injections for varying workflows including:
  * 🐍 Python Code Auditor (PEP 8 checking)
  * 🌐 Professional Translator (with nuance highlighting)
  * 📊 Data Analyst & 🎓 Academic Advisor presets
* **Dynamic Control Panel:** Exposes model temperature sliders ($0.0 \rightarrow 2.0$) and max completion token bounds directly via the UI layer.
* **Bespoke Cyberpunk Theme:** Beautiful, production-ready custom CSS utilizing an Inter font variant, backdrop blur filters, dark-mode gradients, and sleek interactive element scales.
* **State Management:** Defensive parsing pipelines to ensure robust multi-turn memory utilizing strict object tracking.

## 🛠️ Tech Stack & Services
* **Core Language:** Python 3.10+
* **Framework Layer:** Gradio 6.0
* **API Engine:** Groq Cloud Client
* **Core Model:** `llama-3.3-70b-versatile`

---

## 📦 Production Installation & Local Setup

### 1. Clone the Ecosystem Workspace
\`\`\`bash
git clone https://github.com/shanza54/pro-groq-chatbot.git
cd pro-groq-chatbot
\`\`\`
