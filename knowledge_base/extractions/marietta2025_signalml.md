---
name: marietta2025_signalml
description: SignalML — Raytheon/RTX-sponsored capstone; Nick owned QPSK ML modeling and evaluation end-to-end (LSTM baud-lock, is_on_baud head, hyperparameter tuning, activation inspection, streaming benchmarks); patent disclosure contribution
metadata:
  type: project
---

# SignalML — QPSK Baud-Lock via Recurrent ML (Raytheon/RTX Capstone)

## Metadata
- **Project:** SignalML (capstone repo anchors: QPSK_BAUD_LABELS.ipynb, tensorflow_runner.py, cloud_download.py, README.md)
- **Contributors:** Nicklaus Marietta, Michael, Dylan, Benjamin (4-person capstone team) + RTX/Raytheon engineering guidance
- **Year:** 2025 (capstone engagement, CSUF)
- **Type:** Industry-sponsored capstone (Raytheon/RTX)
- **Status:** Professional — sponsored capstone with patent disclosure contribution
- **Correct framing:** "contributed the ML modeling and evaluation work" — never claim the full Raytheon system or proprietary integration details

## Methods & Tools
- **Languages:** Python
- **ML frameworks:** TensorFlow/Keras, Keras Tuner
- **Model architectures:** Two-layer stateful LSTM (64 units/layer, 3-output head: I, Q, is_on_baud), SimpleRNN (comparison experiments)
- **Signal processing:** NumPy, SciPy signal correlation, raised-cosine/QPSK simulated I/Q signal data
- **Visualization / inspection:** TensorBoard, Matplotlib, internal LSTM activation inspection
- **Data infrastructure:** Google Cloud Storage (GCS) data loading (cloud_download.py)
- **Artifacts:** .weights.h5 model files, streaming prediction pipeline, notebook benchmark UI

## Key Results
1. Final model: two-layer stateful LSTM, 64 units/layer, ~50K trainable parameters, 3-output head (I, Q, is_on_baud)
2. **95.5% baud-mask accuracy** in notebook benchmark
3. **Streaming on-baud MSE: 0.0019**
4. **Best validation loss: 0.08497**
5. Notebook UI benchmark throughput: ~44 samples/sec (visualization benchmark — not optimized production throughput)
6. Contributed the recurrent-model prototype and is_on_baud timing head concept to an RTX/Raytheon patent disclosure process

## Novelty Claims
- is_on_baud timing head: frames baud-lock detection as a jointly-learned sequence output (predicting timing drift/slips alongside I/Q symbol recovery) rather than a post-hoc rule-based correction
- Stateful LSTM for streaming inference: enables sequential baud-lock prediction across a continuous I/Q stream by maintaining hidden state across prediction steps
- Recurrent-model experimental evidence for symbol timing recovery from noisy, rate-drifted QPSK I/Q data — contributed to patent disclosure

## Collaboration & Scope
- **Nick's sole ownership:** QPSK model experiments (LSTM/SimpleRNN/stateful/non-stateful comparisons), is_on_baud timing head design, label alignment/resampling logic, hyperparameter tuning (Keras Tuner), internal LSTM activation inspection, streaming benchmark implementation and performance reporting
- **Contributing (shared):** Training scripts, data loading integration, model comparison framework, integration with team QPSK datasets
- **Teammates owned:** Parts of data pipeline, GCS download flow (cloud_download.py context), resampling/alignment experiments (shared), streaming notebook work (shared)
- **Raytheon/RTX owned:** Proprietary system context, requirements, CNN/baseline direction, signal-processing domain constraints, sensitive integration details, patent/legal process

## Provenance Notes
- **Publication status:** N/A — industry capstone; patent disclosure process managed by Raytheon/RTX
- **Safe to claim (sole ownership):** LSTM/RNN model experiments, is_on_baud head design and framing, label alignment/resampling logic, Keras Tuner hyperparameter tuning, LSTM activation inspection, streaming benchmarks, benchmark metrics (all from notebook)
- **Safe to claim (contributing):** Training scripts, data loading, model comparison, integration with QPSK datasets
- **Safe to claim (patent):** "Contributed to an RTX/Raytheon patent disclosure process" — NOT "filed a patent," NOT "awarded a patent," NOT "my patent"
- **Do NOT claim:** Full Raytheon system, CNN/baseline (Raytheon direction), customer context, proprietary integration details, teammates' portions of data pipeline or GCS download ownership
- **NDA/public-safe scope:** Discuss only at high level — recurrent ML for signal timing recovery, QPSK I/Q streams, prototype/benchmark work. Avoid proprietary claims, customer context, and implementation specifics beyond what is in this extraction.
- **Benchmark caveat:** ~44 samples/sec is a notebook UI visualization benchmark, NOT optimized production throughput. Do not overstate as inference speed.

## Resume Bullet Seeds
1. Built a two-layer stateful LSTM (64 units/layer, ~50K parameters) for QPSK symbol timing recovery in a Raytheon-sponsored capstone, achieving 95.5% baud-mask accuracy and 0.0019 on-baud MSE in streaming benchmarks
2. Designed a 3-output LSTM head (I, Q, is_on_baud) framing baud-lock detection as a jointly-learned sequence prediction task, enabling timing-drift and slip recovery from noisy, rate-drifted I/Q streams
3. Contributed the recurrent-model prototype and is_on_baud timing head concept to an RTX/Raytheon patent disclosure process for ML-based symbol timing recovery
4. Applied Keras Tuner to optimize LSTM/SimpleRNN architecture and training parameters across stateful and non-stateful configurations, identifying the two-layer stateful LSTM as optimal for streaming baud-lock prediction
5. Conducted LSTM activation inspection to validate timing-recovery behavior and characterize learned representations in the is_on_baud head
6. Developed label alignment and resampling logic to synchronize I/Q sample streams with is_on_baud sequence labels for model training on raised-cosine/QPSK simulated data
