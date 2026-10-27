# 🧠 Automated LLM Evaluation & Inference Observability Harness

*Automated eval run execution timestamp:* **2026-10-27 15:49:27 UTC**

An automated MLOps evaluation and benchmarking engine designed to measure open-weights Large Language Model (LLM) performance, tracking **Inference Latency (ms)**, **Generation Throughput (Tokens/sec)**, and **Eval Accuracy Indices** across major open models.

## 🏆 Open-Source LLM Benchmark Leaderboard

| Model Architecture | Latency (ms) | Throughput (Tokens/s) | Quality Score Index | Success Rate |
| :--- | :--- | :--- | :--- | :--- |
| **Meta Llama 3.2 1B** | `734.8 ms` | `88.46 t/s` | `96.1%` | `100.0%` |
| **Google Gemma 2 2B** | `657.33 ms` | `93.31 t/s` | `93.4%` | `100.0%` |
| **Qwen 2.5 1.5B** | `767.84 ms` | `66.85 t/s` | `90.4%` | `100.0%` |
| **Microsoft Phi 3.5 Mini** | `469.63 ms` | `115.69 t/s` | `92.6%` | `100.0%` |

### 📊 Inference Performance Pareto Curve
![LLM Performance Matrix](llm_performance_matrix.png?v=1793116167)

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
