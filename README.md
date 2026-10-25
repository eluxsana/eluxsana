<p align="center">
  <img src="assets/orbit-header.svg" alt="Eluxsana Subenderan. Curious about the model. Careful about the evidence." width="100%" />
</p>

<p align="center">
  <a href="https://github.com/eluxsana/RunLedger">Explore RunLedger</a> &nbsp; / &nbsp;
  <a href="https://github.com/eluxsana/RunLedger/blob/main/docs/EXPERIMENTS.md">Read the experiments</a> &nbsp; / &nbsp;
  <a href="https://www.linkedin.com/in/eluxsana">Say hello</a>
</p>

### Hi, I'm Eluxsana.

I'm a machine learning engineer with a statistics background from Waterloo. I work across model training, evaluation, and the systems around them. I like the part where an experiment turns into something another person can run, inspect, and trust.

Python and PyTorch are my main tools. Spark, Ray, SQL, and Parquet show up when the data or the training job gets bigger.

---

### 01 / RunLedger

**An evaluation worker dies halfway through saving results. What can you still trust?**

That's the question behind my small, CPU-first evaluation project. RunLedger combines versioned datasets, resumable jobs, pinned model configurations, and evidence reports you can inspect. I care about the failure cases as much as the final accuracy number.

- **Break it:** kill a worker at three commit boundaries and check the recovered predictions.
- **Trace it:** follow a result back to its dataset, model revision, and scoring configuration.
- **Measure it:** inspect the 128-question ARC-Easy diagnostic and the raw loading-study results.
- **Compare it:** explore prediction drift, including answer flips that the headline score hides.

[Code](https://github.com/eluxsana/RunLedger) · [Experiments & limitations](https://github.com/eluxsana/RunLedger/blob/main/docs/EXPERIMENTS.md) · [Design decisions](https://github.com/eluxsana/RunLedger/blob/main/docs/ARCHITECTURE.md)

### 02 / Questions I want to work on

What changes between two model versions, beyond the headline score? Which evaluation failures come from the model, and which come from the pipeline? How much infrastructure is enough to make a small experiment reliable?

I'm exploring these through RunLedger and contributions to tools I use.

### 03 / In the open

[Hugging Face Hub: cache lookup verification](https://github.com/huggingface/huggingface_hub/pull/5243#issuecomment-6401982920)

I tested an existing contributor's fix with extra offline cases for string and Path cache directories, branch refs, and missing-file markers. Shared the results upstream. This is verification work on an open PR, not a merged code contribution.

---

<sub>Older repositories include university and early learning projects. This page is where I keep my current work and the questions behind it.</sub>
