# RISC-V for Edge Detection using Sobel Matrix

This repository contains the design, implementation, and tools for a custom RISC-V processor, extended to accelerate parallel matrix multiplication operations used in Sobel edge detection.

📌 Overview
Traditional RISC-V processors execute matrix operations sequentially, limiting performance in computationally intensive applications like image processing. This project enhances the RISC-V architecture by introducing custom M-type instructions:

PMUL – Parallel Multiply: Performs parallel element-wise multiplication of matrices.

SMAT – Store Matrix: Efficiently loads/stores matrices to/from memory.

These instructions directly target Sobel edge detection, a widely used image processing algorithm, and achieve up to 300% speedup compared to unmodified RISC-V processors.

🛠️ Features
✅ Support for R, I, S, and new M-type instructions

✅ Custom assembler to convert extended assembly into binary machine code

✅ Matrix storage and manipulation capabilities at the hardware level

✅ Integration-ready for FPGA-based deployment

✅ Reduced instruction count and power usage

✅ Suitable for real-time applications in image processing and embedded AI

📈 Performance
🔹 3× speed improvement over traditional RISC-V processors for matrix-based operations

🔹 Reduced execution time for Sobel convolution filters

🔹 Lower memory overhead and instruction ROM usage
