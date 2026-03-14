Builder and ML Research Engineer at the ELLIS Institute Tübingen, working on post-training of multilingual LLMs. Previously, I was a PhD student at Frank Hutter's [Machine Learning Group in Freiburg](https://ml.informatik.uni-freiburg.de/profile/ferreira/).<BR><BR>

Current projects / research interests:
- OLMo 3 post-training analysis: how does think/instruct capability evolve over sft training time? See [this report](https://github.com/OpenEuroLLM/Taskboard/issues/168#issuecomment-3974681146)
- What dataset mixtures allow LLMs to improve multilingual support (without curbing English language support)? See [this report](https://github.com/OpenEuroLLM/Taskboard/issues/186#issue-4051327047)


Past projects:
- [Improving LLM-based Global Optimization with Search Space Partitioning](https://arxiv.org/abs/2505.21372) (4th author, ICLR 2026)
- [Beyond Random Augmentations: Pretraining with Hard Views](https://arxiv.org/abs/2310.03940) (1st author, ICLR 2025) [[code]](https://github.com/automl/hvp)
- [Quick-Tune: Quickly Learning Which Pretrained Model to Finetune and How](https://openreview.net/forum?id=tqh1zdXIra) (2nd author, ICLR 2024, oral) [[code]](https://github.com/automl/quicktunetool)
- [Zero-Shot AutoML with Pretrained Models](https://github.com/automl/zero-shot-automl-with-pretrained-models) (1st author, ICML 2022, spotlight) [[code]](https://github.com/automl/zero-shot-automl-with-pretrained-models)
- [Learning Environments for Reinforcement Learning](https://github.com/automl/learning_environments) (1st author, ICLR 2022) [[code]](https://github.com/automl/learning_environments)

My PhD thesis: [Meta-Learning and Synthetic Data for Automated Pretraining and Finetuning](https://arxiv.org/abs/2506.12161) (supervised by Prof. Frank Hutter)

[![Scholar Badge](https://img.shields.io/badge/-Scholar-4285F4?style=for-the-badge&labelColor=4285F4&logo=google-scholar&logoColor=white&link=https://scholar.google.com/citations?user=LFtEAeYAAAAJ&hl=en)](https://scholar.google.com/citations?user=LFtEAeYAAAAJ&hl=en)
<!--
Some projects I maintain or co-maintain:

| Project | Total Downloads | Stars |
|:---|:---|:---|
| [Conditional Density Estimation](https://github.com/freelunchtheorem/Conditional_Density_Estimation) | [![Total Downloads](https://img.shields.io/pepy/dt/cde)](https://pepy.tech/project/cde) | [![GitHub stars](https://img.shields.io/github/stars/freelunchtheorem/Conditional_Density_Estimation)](https://github.com/freelunchtheorem/Conditional_Density_Estimation/stargazers) |
| [video2tfrecord](https://github.com/ferreirafabio/video2tfrecord) | [![Total Downloads](https://img.shields.io/pepy/dt/video2tfrecord)](https://pepy.tech/project/video2tfrecord) | [![GitHub stars](https://img.shields.io/github/stars/ferreirafabio/video2tfrecord)](https://github.com/ferreirafabio/video2tfrecord/stargazers) |
| [tailgrid](https://github.com/ferreirafabio/tailgrid) | [![Total Downloads](https://img.shields.io/pepy/dt/tailgrid)](https://pepy.tech/project/tailgrid) | [![GitHub stars](https://img.shields.io/github/stars/ferreirafabio/tailgrid)](https://github.com/ferreirafabio/tailgrid/stargazers) |
| [mppi_pendulum](https://github.com/ferreirafabio/mppi_pendulum) | N/A | [![GitHub stars](https://img.shields.io/github/stars/ferreirafabio/mppi_pendulum)](https://github.com/ferreirafabio/mppi_pendulum/stargazers) |
-->
## 🔧 Open Source Contributions
- [allenai/open-instruct](https://github.com/allenai/open-instruct)
  - Post-training recipes for language model (see [this PR](https://github.com/allenai/open-instruct/pull/1368))
- [OpenEuroLLM/llm-judge-eval](https://github.com/OpenEuroLLM/llm-judge-eval) – LLM-as-judge evaluation framework
  
## 🧩 Selected Projects

 🔬 [autoresearch-automl](https://github.com/ferreirafabio/autoresearch-automl) – Karpathy's autoresearch lets an LLM agent tweak training code through trial and error. Another user [showed](https://www.linkedin.com/posts/ravid-shwartz-ziv-8bb18761_do-llm-coding-agents-fool-us-karpathys-activity-7437556522240536576-ygrQ) that model-based optimization (Optuna TPE + expert-picked hyperparameter search sapce) already beats it. We fill the gap by integrating [LLAMBO](https://arxiv.org/abs/2402.03921) into autoresearch, an approach that puts the LLM inside model-based optimization, using it as both surrogate model and candidate generator.
 
 . We fill the gap by combining both: LLAMBO replaces the GP in Bayesian optimization with an LLM, bringing the structured search of classical HPO together with the LLM's general knowledge of ML training dynamics — no expert curation needed.

🔍 **[aretheyinvolved.com](https://aretheyinvolved.com)** - Search + analyse names across all Epstein files (NER, OCR, co-occurrences, AI summaries+role classification).

🌸 **[myperfumeai.com](https://myperfumeai.com)** – ChatGPT for perfumes / personal perfume recommendation AI assistant based on 120k+ perfumes dataset.

🧠 **[Conditional Density Estimation (CDE)](https://github.com/freelunchtheorem/Conditional_Density_Estimation)** – Reference package (cde) for conditional density estimation.

🧩 **[slurmfrag](https://github.com/ferreirafabio/slurmfrag)** – Fine-grained experiment fragmentation and management for SLURM clusters.

📊 **[tailgrid](https://github.com/ferreirafabio/tailgrid)** – Terminal-based and LLM-assisted monitoring and visualization of log files.

🧮 **[Generative Symbolic Regression](https://github.com/ferreirafabio/symbolic_regression)** – Neural translation from tabular data to concise LaTeX equations. *(private / research code)*

🤖 **[mppi_pendulum](https://github.com/ferreirafabio/mppi_pendulum)** – Minimal MPPI control implementation for the classic pendulum task.

🎯 **[Zero-Shot AutoML with Pretrained Models](https://github.com/automl/zero-shot-automl-with-pretrained-models)** – Zero-shot selection of strong pretrained models without training.

🎥 **[video2tfrecord](https://github.com/ferreirafabio/video2tfrecord)** – Convert raw video datasets into scalable TFRecord pipelines.


