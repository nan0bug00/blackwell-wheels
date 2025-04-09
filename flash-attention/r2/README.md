# Release r2
Binary flash-attention wheel release for NVIDIA Blackwell GPUs (RTX 50-series).

## Changelog
 - Rebuilt with correct TORCH_CUDA_ARCH_LIST arguments to ensure support for Compute Capability 7.5, 8.6, 8.9, and 12.0 (Turing through Blackwell) 

 ## Info
- **Built against:** PyTorch 2.8.0.dev20250406+cu128
- **Source:** [https://github.com/Dao-AILab/flash-attention](https://github.com/Dao-AILab/flash-attention)
- **License:** BSD 3-Clause (see `LICENSE` in this folder)