## Learning Rates and Schedules — Essential Papers

Scheduling and scaling rules that most impact convergence and final accuracy.

### Schedules and policies
- **Cyclical Learning Rates (2017)** — Smith [Paper](https://arxiv.org/abs/1506.01186)
- **SGDR: Cosine Annealing with Warm Restarts (2017)** — Loshchilov & Hutter [Paper](https://arxiv.org/abs/1608.03983)
- **Warmup + Linear/Cosine Decay (2017)**: Large-batch training — Goyal et al. [Paper](https://arxiv.org/abs/1706.02677)
- **One-Cycle Policy (2019)** — Smith & Topin [Paper](https://arxiv.org/abs/1803.09820)
- **Polynomial Decay (common in segmentation)**

### Scaling laws and batch size
- **Accurate, Large Minibatch SGD (2017)** — Goyal et al. [Paper](https://arxiv.org/abs/1706.02677)
- **Training Deep Nets with Large Batch (2018)** — You et al. [Paper](https://arxiv.org/abs/1708.03888)

Suggested path: CLR → SGDR → Warmup + Linear Scaling → One-Cycle.


