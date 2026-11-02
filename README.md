# 🧠 Automated LLM Evaluation & Inference Observability Harness

*Automated eval run execution timestamp:* **2026-11-02 20:10:45 UTC**

An automated MLOps evaluation and benchmarking engine designed to measure open-weights Large Language Model (LLM) performance, tracking **Inference Latency (ms)**, **Generation Throughput (Tokens/sec)**, and **Eval Accuracy Indices** across major open models.

## 🏆 Open-Source LLM Benchmark Leaderboard

| Model Architecture | Latency (ms) | Throughput (Tokens/s) | Quality Score Index | Success Rate |
| :--- | :--- | :--- | :--- | :--- |
| **Meta Llama 3.2 1B** | `654.71 ms` | `87.57 t/s` | `90.2%` | `100.0%` |
| **Google Gemma 2 2B** | `686.84 ms` | `84.93 t/s` | `95.8%` | `100.0%` |
| **Qwen 2.5 1.5B** | `692.91 ms` | `100.06 t/s` | `90.1%` | `100.0%` |
| **Microsoft Phi 3.5 Mini** | `652.78 ms` | `60.77 t/s` | `95.9%` | `100.0%` |

### 📊 Inference Performance Pareto Curve
![LLM Performance Matrix](llm_performance_matrix.png?v=1793650246)

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
