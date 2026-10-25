# Hi, I'm Eluxsana

I'm a machine learning engineer with a statistics background from the University of Waterloo. I work on model training, evaluation, and the tools that make experiments easier to run and understand.

I'm especially interested in the gap between an experiment that works once and one that someone else can reproduce.

## What I'm building

### [RunLedger](https://github.com/eluxsana/RunLedger)

A small, CPU-first project for resumable LLM evaluation. The question behind it: if a worker dies halfway through saving results, can the run recover without changing its predictions or scores?

It brings together versioned Parquet datasets, a SQLite job ledger, a pinned Hugging Face model, and inspectable evaluation reports. The repo includes crash-recovery experiments, a 128-question ARC-Easy diagnostic, and the limitations behind the results.

[Read the code](https://github.com/eluxsana/RunLedger) · [Experiments](https://github.com/eluxsana/RunLedger/blob/main/docs/EXPERIMENTS.md) · [Design decisions](https://github.com/eluxsana/RunLedger/blob/main/docs/ARCHITECTURE.md)

## A little more about me

- I like working across the model and systems sides of ML.
- Python and PyTorch are my main tools; I also work with Spark, Ray, SQL, and Parquet.
- My older repositories include university and early learning projects. They show where I started; RunLedger is a better place to see my current interests.

[LinkedIn](https://www.linkedin.com/in/eluxsana)
