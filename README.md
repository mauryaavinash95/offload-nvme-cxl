**Figure 1**
  - Axis: x-axis: model size: 20B, 30B, 40B, 52B, 70B & y-axis: average iteration time (s)
  - Number of GPUs: 4, Number of cores: 56
  - Comparison: DDR-only offload, DDR+CXL offload, NVMe Offload
  - Use-cases: 64GB/128GB (DDR-Only), 64GB+4x256GBCXL (DDR+CXL), NVMe
  - Models:
      - 20B: 64GB DDR Only, (No DDR+CXL), NVMe
      - 30B: 64GB DDR Only, (No DDR+CXL), NVMe
      - 40B: 128GB DDR Only, DDR(64GB)+CXL, NVMe
      - 52B: 128GB DDR Only. DDR(64GB)+CXL, NVMe
      - 70B: 128GB DDR Only, DDR(64GB)+CXL, NVMe

**Figure 2**
  - Axis: x-axis: Model size: 20B, 30B, 40B, 52B, 70B & y-axis: throughput
  - Plot from Figure 1 data

**Figure 3**
  - Axis: x-axis: batch size: 4, 8, 16, 32, 64, 128, 256 & y-axis: average iteration time (s)
  - Models: 70B
  - Use-Case: 128GB (DDR-Only), 64GB+4x256GBCXL (DDR+CXL), NVMe

**Figure 4**
  - Axis: x-axis: batch size: 4, 8, 16, 32, 64, 128, 256 & y-axis: average cpu utilization (%)
  - Plot from Figure 3 data
