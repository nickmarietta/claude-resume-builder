---
name: experience_signalml
description: SignalML Raytheon/RTX capstone — Nick owned LSTM QPSK baud-lock modeling end-to-end; is_on_baud timing head; 95.5% baud-mask accuracy; patent disclosure contribution; team of 4 + RTX guidance
metadata:
  type: experience
---

# Experience: SignalML — QPSK Baud-Lock via Recurrent ML
## 2025 — Raytheon/RTX-Sponsored Senior Capstone, CSUF (Team of 4)

### Cross-Project Section
SignalML is Nick's only professional, industry-sponsored credential — a Raytheon/RTX-funded capstone applying recurrent ML to a real signal-processing problem (QPSK symbol timing recovery / baud-lock). It is also the only project with a patent-adjacent contribution. Nick owned the entire ML modeling and evaluation layer: model design, hyperparameter tuning, activation inspection, and streaming benchmarks. This project is the strongest evidence of ML depth, signal processing exposure, and ability to work within professional engineering constraints.

**CL framing:** Use SignalML to establish defense/signals credibility and ML engineering depth. Frame it as applied ML for a real-world signals problem under Raytheon/RTX guidance — not as a class project. The patent disclosure contribution is a differentiator; handle with care per provenance guardrails.

**Public-safe scope:** Discuss only at high level — recurrent ML for signal timing recovery, QPSK I/Q streams, prototype/benchmark work. Do not disclose proprietary system context, customer requirements, or CNN/baseline direction.

---

### Achievement SM-01: Two-Layer Stateful LSTM for QPSK Baud-Lock
**Source:** marietta2025_signalml.md
**Paper:** N/A — industry capstone
**User's role:** Sole ML modeling contributor
**Status:** Professional — Raytheon/RTX-sponsored capstone

**Context:** Symbol timing recovery (baud-lock) is a core signal-processing problem — without it, a receiver can't reliably decode transmitted symbols. Nick's approach replaced rule-based timing recovery with a stateful recurrent model that learns baud-lock directly from streaming I/Q samples.

**Bullet variants:**
- **2L:** Built a two-layer stateful LSTM (64 units/layer, ~50K parameters) for QPSK symbol timing recovery in a Raytheon/RTX-sponsored capstone, achieving 95.5% baud-mask accuracy and 0.0019 on-baud MSE in streaming benchmarks.
- **3L:** Designed and trained a two-layer stateful LSTM architecture (64 units/layer, ~50K trainable parameters) for QPSK symbol timing recovery and baud-lock prediction for a Raytheon/RTX-sponsored capstone, achieving 95.5% baud-mask accuracy and 0.0019 streaming on-baud MSE in notebook benchmark evaluation on simulated raised-cosine/QPSK I/Q data.
- **1L:** Built two-layer stateful LSTM for QPSK baud-lock; 95.5% baud-mask accuracy, 0.0019 on-baud MSE (Raytheon capstone).

**Key skills:** TensorFlow/Keras, LSTM, stateful RNN, signal processing, QPSK, Python
**ATS keywords:** LSTM, TensorFlow, recurrent neural network, signal processing, QPSK, baud-lock, symbol timing recovery, Keras
**Reframing notes:** Defense — HIGH, lead bullet. ML/AI — HIGH, strongest quantified ML result in portfolio. Full Stack — LOW, omit.

---

### Achievement SM-02: is_on_baud Timing Head Design
**Source:** marietta2025_signalml.md
**Paper:** N/A — industry capstone
**User's role:** Sole designer
**Status:** Professional — Raytheon/RTX-sponsored capstone

**Context:** Traditional baud-lock uses rule-based timing correction. The is_on_baud head reframes it as a sequence prediction problem: the model simultaneously recovers I/Q symbol values and predicts whether each sample is on-baud, representing timing drift and slips as learnable sequence outputs. This design is the core contribution to the patent disclosure.

**Bullet variants:**
- **2L:** Designed a 3-output LSTM prediction head (I, Q, is_on_baud) that frames baud-lock detection as a jointly-learned sequence task, enabling timing-drift and slip recovery from noisy, rate-drifted I/Q streams.
- **3L:** Designed a 3-output LSTM head jointly predicting recovered I and Q symbol values and an is_on_baud timing flag from streaming QPSK I/Q samples, representing timing drift and baud slips as a learnable sequence prediction problem rather than a post-hoc rule-based correction — the core innovation contributed to the RTX patent disclosure.
- **1L:** Designed 3-output LSTM head (I, Q, is_on_baud) framing baud-lock as a jointly-learned sequence prediction task.

**Key skills:** LSTM architecture design, sequence modeling, QPSK, TensorFlow/Keras, signal timing
**ATS keywords:** LSTM, sequence modeling, timing recovery, baud-lock, signal processing, recurrent neural network
**Reframing notes:** Defense — HIGH (the innovation). ML/AI — HIGH (model design claim). Full Stack — omit.

---

### Achievement SM-03: Hyperparameter Tuning with Keras Tuner
**Source:** marietta2025_signalml.md
**Paper:** N/A — industry capstone
**User's role:** Sole contributor
**Status:** Professional — Raytheon/RTX-sponsored capstone

**Context:** Identifying the optimal model configuration (stateful vs. non-stateful, LSTM vs. SimpleRNN, depth, units) required systematic search rather than manual guessing. Nick applied Keras Tuner to run structured model comparison experiments.

**Bullet variants:**
- **2L:** Applied Keras Tuner to systematically optimize LSTM architecture and training parameters, running model comparison experiments across LSTM/SimpleRNN and stateful/non-stateful configurations to identify optimal baud-lock performance.
- **3L:** Applied Keras Tuner for systematic hyperparameter search across LSTM and SimpleRNN architectures in both stateful and non-stateful configurations, identifying the optimal two-layer stateful LSTM design for streaming QPSK timing recovery through structured model comparison experiments on simulated I/Q data.
- **1L:** Applied Keras Tuner to optimize LSTM/RNN hyperparameters across stateful and non-stateful configurations for baud-lock prediction.

**Key skills:** Keras Tuner, hyperparameter optimization, LSTM, model selection, Python
**ATS keywords:** Keras Tuner, hyperparameter tuning, model selection, LSTM, TensorFlow
**Reframing notes:** ML/AI — MED (supporting methodology). Defense — MED (rigorous methodology evidence). Full Stack — omit.

---

### Achievement SM-04: Internal LSTM Activation Inspection
**Source:** marietta2025_signalml.md
**Paper:** N/A — industry capstone
**User's role:** Sole contributor
**Status:** Professional — Raytheon/RTX-sponsored capstone

**Context:** For a defense application, understanding what the model has learned matters — not just whether it achieves target metrics. LSTM activation inspection validated that the is_on_baud head was learning timing-recovery behavior, not spurious correlations.

**Bullet variants:**
- **2L:** Conducted internal LSTM activation inspection to validate timing-recovery behavior, characterizing learned representations in the is_on_baud classification head and verifying model internals for the baud-lock task.
- **3L:** Conducted internal LSTM activation analysis to validate timing-recovery behavior and characterize learned sequence representations within the is_on_baud classification head, providing interpretability evidence for the model's baud-lock predictions on noisy QPSK I/Q streams.
- **1L:** Conducted LSTM activation inspection to validate is_on_baud timing-recovery behavior and characterize model internals.

**Key skills:** Model interpretability, LSTM, TensorBoard, Matplotlib, Python
**ATS keywords:** model interpretability, LSTM, activation analysis, TensorBoard, model validation
**Reframing notes:** Defense — MED (model validation for high-stakes application is valued). ML/AI — MED (interpretability signal). Full Stack — omit.

---

### Achievement SM-05: Streaming Prediction Pipeline + Benchmarks
**Source:** marietta2025_signalml.md
**Paper:** N/A — industry capstone
**User's role:** Sole contributor
**Status:** Professional — Raytheon/RTX-sponsored capstone

**Context:** The final deliverable required a streaming inference pipeline and documented performance benchmarks. Nick implemented the pipeline and produced the final metrics (validation loss, baud-mask accuracy, on-baud MSE, throughput) for the capstone evaluation.

**Bullet variants:**
- **2L:** Implemented streaming LSTM prediction pipeline and final notebook benchmarks, validating model performance at 0.08497 validation loss and 95.5% baud-mask accuracy on simulated QPSK I/Q data for the capstone evaluation.
- **3L:** Implemented and benchmarked a streaming LSTM prediction pipeline on simulated QPSK I/Q data, producing final capstone performance artifacts: 0.08497 validation loss, 0.0019 on-baud MSE, 95.5% baud-mask accuracy, and ~44 samples/sec notebook UI throughput — documenting deliverable performance for the Raytheon/RTX engagement.
- **1L:** Implemented streaming LSTM pipeline and final benchmarks: 0.08497 val loss, 95.5% baud-mask accuracy, 0.0019 on-baud MSE.

**Key skills:** Streaming inference, Python, TensorFlow/Keras, performance benchmarking, Matplotlib
**ATS keywords:** streaming inference, model benchmarking, performance evaluation, LSTM, TensorFlow
**Reframing notes:** Defense — HIGH as deliverable evidence. ML/AI — MED. Always include the benchmark caveat: ~44 samples/sec is notebook visualization, not production throughput. Full Stack — omit.

**Benchmark caveat:** NEVER describe ~44 samples/sec as optimized inference speed or production throughput. Correct framing: "notebook UI benchmark" or "visualization benchmark."

---

### Achievement SM-06: Label Alignment and Resampling Logic
**Source:** marietta2025_signalml.md
**Paper:** N/A — industry capstone
**User's role:** Sole contributor (owned this component; some shared resampling experiments with team)
**Status:** Professional — Raytheon/RTX-sponsored capstone

**Context:** Aligning I/Q sample labels with is_on_baud ground truth requires careful handling of timing offsets between raw samples and baud positions in simulated data. Without correct alignment, the model trains on mismatched inputs and targets.

**Bullet variants:**
- **2L:** Developed label alignment and resampling logic to synchronize I/Q sample streams with is_on_baud sequence labels for model training, resolving timing offsets in raised-cosine/QPSK simulated signal data.
- **3L:** Developed label alignment and resampling preprocessing logic to synchronize I/Q sample streams with is_on_baud sequence labels for model training, resolving timing offsets between raw samples and ground-truth baud positions in raised-cosine/QPSK simulated signal data to enable accurate sequence prediction.
- **1L:** Built label alignment/resampling logic to synchronize I/Q samples with is_on_baud sequence labels for training.

**Key skills:** Signal processing, NumPy, SciPy, data preprocessing, Python
**ATS keywords:** signal processing, data preprocessing, I/Q data, NumPy, SciPy, resampling
**Reframing notes:** Defense — MED (signal data expertise). ML/AI — MED (data pipeline for time-series ML). Full Stack — omit.

---

### Achievement SM-07: Patent Disclosure Contribution
**Source:** marietta2025_signalml.md
**Paper:** N/A — industry capstone; patent process managed by Raytheon/RTX
**User's role:** Technical contributor (recurrent-model prototype + is_on_baud timing head concept)
**Status:** Patent disclosure/application process managed by Raytheon/RTX — do not state filing or award status

**Context:** Nick's recurrent-model approach and is_on_baud timing head concept were contributed to an RTX/Raytheon patent disclosure process for ML-based symbol timing recovery. The patent filing and legal process are Raytheon/RTX's responsibility.

**Bullet variants:**
- **2L:** Contributed the recurrent-model prototype and is_on_baud timing head concept to an RTX/Raytheon patent disclosure process for ML-based symbol timing recovery from noisy, rate-drifted I/Q streams.
- **3L:** Contributed the recurrent-model prototype, experimental results, and is_on_baud timing head design to an RTX/Raytheon patent disclosure process for ML-based symbol timing recovery, providing technical invention evidence for a learnable baud-lock approach from streaming QPSK I/Q data; patent process managed by Raytheon/RTX.
- **1L:** Contributed recurrent-model prototype and is_on_baud timing head to an RTX/Raytheon patent disclosure process.

**Key skills:** Applied ML research, invention disclosure, LSTM, signal processing
**ATS keywords:** patent, invention disclosure, RTX, Raytheon, signal processing, ML research
**Reframing notes:** Defense — HIGH (patent in defense signals domain is a strong credential for defense employers). ML/AI — MED. ALWAYS use "patent disclosure process" not "filed a patent" or "awarded a patent."

**Overclaiming warning:** Do NOT say "filed a patent," "awarded a patent," or "my patent." Correct framing: "contributed to an RTX patent disclosure process" or "contributed to a Raytheon-sponsored invention disclosure." Patent status is Raytheon/RTX's to disclose.

---

### Provenance Guardrails (All SM Achievements)
- Nick's sole ownership: LSTM/RNN model experiments, is_on_baud head design, label alignment/resampling, Keras Tuner tuning, LSTM activation inspection, streaming benchmarks
- Do NOT claim: full Raytheon system, CNN/baseline direction, customer context, teammates' data pipeline portions, GCS download ownership, proprietary integration details
- Patent: "contributed to RTX patent disclosure process" — never "filed" or "awarded"
- Benchmark: ~44 samples/sec = notebook visualization, not production throughput
- Public-safe scope: discuss at high level only — recurrent ML for timing recovery, QPSK I/Q streams, prototype/benchmark. No proprietary claims.
