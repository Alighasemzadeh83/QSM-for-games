# Q-Score Matching on RL Benchmarks

This repository extends the official code from the paper:

> **Learning a Diffusion Model Policy from Rewards via Q-Score Matching**  
> Michael Psenka, Alejandro Escontrela, Pieter Abbeel, Yi Ma.  
> [arXiv:2312.11752](https://arxiv.org/abs/2312.11752)

to different classic control and harder environments.

---

## 🚀 Environments Tested
We adapted the QSM implementation to learn policies via diffusion models on the following RL environments:

- **CartPole**
- **MountainCar**
- **BipedalWalker**
- Additional simple continuous control tasks.

This required tuning the Q-score matching loss and sampling procedures for each task.

---

## 📚 Reference

If you use this code or ideas from this implementation, please cite:

```bibtex
@misc{psenka2025learningdiffusionmodelpolicy,
      title={Learning a Diffusion Model Policy from Rewards via Q-Score Matching},
      author={Michael Psenka and Alejandro Escontrela and Pieter Abbeel and Yi Ma},
      year={2025},
      eprint={2312.11752},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2312.11752}
}
