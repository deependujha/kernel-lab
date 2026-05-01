# Introduction to CUDA programming

## Terminologies:

- **Heterogeneous Systems**: system that includes both GPUs and CPUs
- **CPU & connected memory**: host & host memory
- **GPU & connected memory**: device & device memory

> - A **`System on a Chip (SoC)`** is an integrated circuit that consolidates all essential computer components—including CPU, GPU, memory, and I/O ports—onto a single silicon die.
> - By replacing multiple discrete chips, SoCs offer higher power efficiency, smaller physical size, and increased processing speed, making them ideal for mobile devices, IoT appliances, and laptops.
> - e.g., apple silicon M1, M2, etc. are SoCs that integrate both CPU and GPU cores on a single chip, enabling efficient performance and power management for a wide range of applications.

- **device code**: code that runs on the GPU
- **host code**: code that runs on the CPU
- **kernel**: a function that is invoked for execution on the GPU is called a kernel. Kernels are executed in parallel by multiple threads on the GPU, allowing for efficient processing of large data sets.