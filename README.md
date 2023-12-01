# jailbreaking-prompt-injection-detector

The purpose of this project was to explore the results of [Zou et al.](https://llm-attacks.org/) in depth and to practice applying machine learning to cybersecurity datasets.

I generated a dataset using three adversarially-generated malicious LLM prompt suffixes from the above paper. I then trained a logistic regression classifier and a linear support vector classifier to serve as a sort of firewall to prevent malicious prompts from bypassing the safety fine-tuning of an LLM.
