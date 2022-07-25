##  Binary Early-Exit Network for Adaptive Inference on Low-Resource Devices (Interspeeh 2022)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fMFNIg3-Sc3ie12awn4OiO3-y7x_A_Ja?usp=sharing)


### Abstract 
Deep neural networks have significantly improved performance on a range of tasks with the increasing demand for computational resources, leaving deployment on low-resource devices (with limited memory and battery power) infeasible. Binary neural networks (BNNs) tackle the issue to an extent with extreme compression and speed-up gains compared to real-valued models. We propose a simple but effective method to accelerate inference through unifying BNNs with an early-exiting strategy. Our approach allows simple instances to exit early based on a decision threshold and utilizes output layers added to different intermediate layers to avoid executing the entire binary model. We extensively evaluate our method on three audio classification tasks and across four BNNs architectures. Our method demonstrates favorable quality-efficiency trade-offs while being controllable with an entropy-based threshold specified by the system user. It also results in better speed-ups (latency less than 6ms) with a single model based on existing BNN architectures without retraining for different efficiency levels. It also provides a straightforward way to estimate sample difficulty and better understanding of uncertainty around certain classes within the dataset.

### Paper
https://arxiv.org/pdf/2206.09029.pdf

### Reference 
If you use this code, please cite the following paper:

Aaqib Saeed. "Binary Early-Exit Network for Adaptive Inference on Low-Resource Devices." arXiv preprint arXiv:2206.09029 (2022).

```
@article{saeed2022binary,
  title={Binary Early-Exit Network for Adaptive Inference on Low-Resource Devices},
  author={Saeed, Aaqib},
  journal={arXiv preprint arXiv:2206.09029},
  year={2022}
}
```
