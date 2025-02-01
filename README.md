**The final version of the code is in `AI_AL_RedTeam_short_evo_0_2.ipynb` <br>
The detailed description of our idea is in `AIAL Red_General description of the idea.pdf`**

Our goal is to create a dataset of adversarial prompts that can bypass LLM safety mechanisms and expose weaknesses in model alignment. These prompts are engineered using techniques like hypothetical framing, role-playing, and reverse psychology to evade detection.
We start with the dataset from "Fine-Tuning Aligned Language Models Compromises Safety" and enhance it.
We refine prompts by adding misleading context inspired by the "Human-Interpretable Adversarial Prompt Attack" paper.
We evaluate the dataset on multiple LLMs using SALAD-Bench to measure attack success.
