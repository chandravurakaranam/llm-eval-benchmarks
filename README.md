# 🧠 Automated LLM Evaluation & Inference Observability Harness

*Automated eval run execution timestamp:* **2026-11-18 18:45:46 UTC**

An automated MLOps evaluation and benchmarking engine designed to measure open-weights Large Language Model (LLM) performance, tracking **Inference Latency (ms)**, **Generation Throughput (Tokens/sec)**, and **Eval Accuracy Indices** across major open models.

## 🏆 Open-Source LLM Benchmark Leaderboard

| Model Architecture | Latency (ms) | Throughput (Tokens/s) | Quality Score Index | Success Rate |
| :--- | :--- | :--- | :--- | :--- |
| **Meta Llama 3.2 1B** | `708.8 ms` | `91.7 t/s` | `95.0%` | `100.0%` |
| **Google Gemma 2 2B** | `811.12 ms` | `62.05 t/s` | `91.4%` | `100.0%` |
| **Qwen 2.5 1.5B** | `700.49 ms` | `80.9 t/s` | `88.1%` | `100.0%` |
| **Microsoft Phi 3.5 Mini** | `807.65 ms` | `51.18 t/s` | `95.0%` | `100.0%` |

### 📊 Inference Performance Pareto Curve
![LLM Performance Matrix](llm_performance_matrix.png?v=1795027546)

---

### 🧪 Evaluation Methodology & Benchmark Tasks
1. **Logic Reasoning:** Zero-shot math and word problem validation.
2. **Code Generation:** Algorithm writing and complexity analysis.
3. **Structured Output:** Schema compliance and JSON verification.

---

### 🗄️ Historical Benchmark Dataset
All raw metrics are logged continuously to [`llm_eval_history.csv`](./llm_eval_history.csv).

---
*Built with Python (`requests`, `pandas`, `matplotlib`) and GitHub Actions.*
