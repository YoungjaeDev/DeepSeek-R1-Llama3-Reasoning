# DeepSeek-R1-Llama3-Reasoning

This repository documents an LLM fine-tuning project focused on enhancing the reasoning capabilities of Llama 3 8B. We leverage the `sequelbox/Celestia3-DeepSeek-R1-0528` dataset for Supervised Fine-Tuning (SFT) and explore Reinforcement Learning (RL) techniques. Our primary objective is to evaluate and compare the performance of SFT and RL approaches on reasoning tasks, using the AIME benchmark for comprehensive assessment.

## Project Milestones

1.  **Data Exploration & SFT Preparation:**
    * Examine the `sequelbox/Celestia3-DeepSeek-R1-0528` dataset.
    * Determine whether to proceed with data augmentation or use the dataset as-is for SFT.

2.  **SFT Performance Measurement:**
    * Conduct Supervised Fine-Tuning (SFT) on Llama 3 8B using the prepared DeepSeek-R1 data.
    * Measure the SFT model's performance on the AIME benchmark.

3.  **RL Data Construction:**
    * Construct data specifically for Reinforcement Learning (RL), potentially leveraging open-source datasets.

4.  **RL Performance Measurement:**
    * Apply Reinforcement Learning to the SFT-tuned model or train an RL model from scratch.
    * Measure the RL model's performance on the AIME benchmark and quantify performance improvement.

5.  **Comparative Analysis & Discussion:**
    * Compare the performance results of SFT and RL.
    * Analyze potential reasons if SFT outperforms RL, leading to discussions on the strengths and weaknesses of each approach for reasoning tasks.

## Goals

* Improve Llama 3 8B's reasoning abilities.
* Understand the effectiveness of SFT and RL for reasoning-focused LLM fine-tuning.
* Provide a clear comparison of SFT vs. RL performance on the AIME benchmark.
* Share insights and challenges encountered during the fine-tuning process.

## Technologies

* **Model:** Llama 3 8B
* **Dataset:** `sequelbox/Celestia3-DeepSeek-R1-0528`
* **Evaluation:** AIME Benchmark
* **Frameworks/Libraries:** (e.g., Transformers, PEFT, TRL, etc. - *추후 확정되는대로 추가*)
