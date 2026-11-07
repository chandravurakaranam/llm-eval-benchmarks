# 🧠 Automated LLM Evaluation & Inference Observability Harness

*Automated eval run execution timestamp:* **2026-11-07 16:15:17 UTC**

An automated MLOps evaluation and benchmarking engine designed to measure open-weights Large Language Model (LLM) performance, tracking **Inference Latency (ms)**, **Generation Throughput (Tokens/sec)**, and **Eval Accuracy Indices** across major open models.

## 🏆 Open-Source LLM Benchmark Leaderboard

| Model Architecture | Latency (ms) | Throughput (Tokens/s) | Quality Score Index | Success Rate |
| :--- | :--- | :--- | :--- | :--- |
| **Meta Llama 3.2 1B** | `688.72 ms` | `81.31 t/s` | `93.5%` | `100.0%` |
| **Google Gemma 2 2B** | `568.14 ms` | `89.18 t/s` | `97.9%` | `100.0%` |
| **Qwen 2.5 1.5B** | `682.56 ms` | `51.77 t/s` | `94.8%` | `100.0%` |
| **Microsoft Phi 3.5 Mini** | `659.23 ms` | `65.23 t/s` | `98.4%` | `100.0%` |

### 📊 Inference Performance Pareto Curve
![LLM Performance Matrix](llm_performance_matrix.png?v=1794068117)

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
