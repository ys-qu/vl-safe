# vl-safe
The code will be made available upon acceptance. Stay tuned!

We want to provide a one-sentence explaination of our paper:
We combine a world model, a VLM safety scorer, and safe RL for autonomous driving: the world model imagines rollouts (r: reward, a: action, c: cost, s: state, s': next state, p: safety score), where a CLIP-based VLM assigns per-state safety scores used as supervision so the world model predicts state-wise safety score p, and safe RL then updates the policy, prioritizing reward when p is high and minimizing cost when p is low.
