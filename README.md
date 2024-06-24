# Deep Learning Projects

These projects were done for a graduate course on advanced deep learning at UC Davis.

## nanoGPT Modification

This project involved making several modifications to existing nanoGPT code, requiring a deep understanding of the inner workings of an LLM. These modifications were:
- Reduce the dimensionality of the key, query, and value vectors in the self-attention
- Perform sliding window attention, only using the past n tokens
- Modify the MLP layer
- Add register tokens

## Vision Transformer

This project involved performing knowledge distillation on a vision transformer. I first finetuned (on the CIFAR 10 dataset) a large model that was pretrained on ImageNet, which I used as the ground truth for training a smaller model. The goal is to produce a small model that can run on a small device, but with better performance than just the small model alone. We do in fact see improvement in performance.

## References
- nanoGPT: https://github.com/karpathy/nanoGPT
- Vision Transformer: https://github.com/soroush-abbasi/289L_AdvDL
