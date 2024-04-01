# Fine-Tune-LLM
There are two main fine-tuning techniques:

- Supervised Fine-Tuning (SFT): Models are trained on a dataset of instructions and responses. It adjusts the weights in the LLM to minimize the difference between the generated answers and ground-truth responses, acting as labels.
- Reinforcement Learning from Human Feedback (RLHF): Models learn by interacting with their environment and receiving feedback. They are trained to maximize a reward signal (using PPO), which is often derived from human evaluations of model outputs.
