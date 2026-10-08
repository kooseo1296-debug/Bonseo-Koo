# Bonseo Koo

**Undergraduate Researcher in Electronic Engineering**  
Sogang University | Seoul, Republic of Korea

**Research Interests:** AI/NPU Accelerator Architecture · Digital VLSI · FPGA/SoC · Low-Precision Computing · Hardware/Software Co-Design

I am an undergraduate researcher interested in designing efficient AI hardware accelerators, with a focus on RTL architecture, FPGA implementation, and hardware/software co-design.

My research explores two complementary aspects of NPU design: **energy-efficient arithmetic architectures** and **system-level inference acceleration**.

---

## Featured Research Projects

### Project 1 — Energy-Efficient Low-Precision NPU
**December 2025 – July 2026**

**Verilog RTL | PYNQ-Z2 | Dynamic Scaling | Zero-Skipping**

Designed and evaluated a low-precision FPGA NPU combining Leading-One Detection (LOD)-based Dynamic Scaling and Switching-Aware Zero-Skipping.

**Key Results**
- Explored **45 NPU configurations** across precision and zero-skipping parameters
- Achieved **92.0% inference fidelity**, compared with 74.0% for the fixed 7-bit baseline
- Reduced LUT utilization by 23.7%, BRAM utilization by 11.1%, and dynamic power by 12.9% relative to the fixed 7-bit baseline
- Implemented an 8×8 weight-stationary systolic-array architecture on PYNQ-Z2 at 100 MHz
- Presented the research at the 2026 ISE Summer Conference

[**Project Repository**](https://github.com/kooseo1296-debug/Project-1.Energy-Efficient-Low-Precision-NPU) · [**Live Demo Video**](https://drive.google.com/file/d/1lzkIqhfIcX4UrQ2W33rvNfDzw1MxMoIF/view)

### Project 2 — End-to-End FPGA CNN Accelerator
**Completed: September 2026**

**Verilog RTL | PYNQ-Z2 | Vitis | AXI4-Lite | HW/SW Co-Design**

Re-architected a CIFAR-10 CNN accelerator to reduce PS–PL communication overhead by moving network-level scheduling and intermediate feature processing into the FPGA programmable logic.

**Key Results**
- **67.55× end-to-end speedup:** 338.03 → 5.004 ms/image
- **99.59% fewer PS–PL payload transactions:** 748,650 → 3,084 per image
- **91.5% CIFAR-10 accuracy**, compared with 91.9% for the PS-managed baseline
- Implemented Conv1–Conv6, GAP, and FC1–FC2 within the PL using a 9×16 weight-stationary systolic array
- Achieved timing closure at 125 MHz with unchanged BRAM and DSP utilization
- Verified on 1,000 CIFAR-10 images and demonstrated USB-camera inference on PYNQ-Z2

The controlled Vitis benchmark measures end-to-end inference latency, while the Jupyter-based camera demonstration achieved approximately 5 FPS at the application/display level.

[**Project Repository**](https://github.com/kooseo1296-debug/Project-2) · [**Live Demo Video**](https://drive.google.com/file/d/1bns6vxbrneyFb1yLkzVsFXlarAnewryC/view)

---

## Publication & Award

**B. Koo**, Y. Lee, T. Jung, and S. Ryu,  
"Maximizing NPU Fidelity and Efficiency with LOD-Based Dynamic Scaling and Switching-Aware Zero-Skipping,"  
*2026 ISE Summer Conference*, First-author Oral Presentation, July 2026.

**Live Demonstration Excellence Award** — 2026 ISE Summer Conference

[**Conference Paper**](https://drive.google.com/file/d/1E2n2r2hTkK8z5EnhQzTTAbOcefPSNtiD/view)

---

## Technical Skills

- **Hardware:** Verilog RTL, Systolic Arrays, FPGA Architecture, Digital VLSI, Fixed-Point Arithmetic
- **FPGA/SoC:** AMD/Xilinx Vivado, Vitis, Zynq PS–PL Integration, AXI4-Lite, BRAM
- **Programming:** C, Python, PyTorch, Jupyter Notebook
- **Research Areas:** Hardware-Efficient AI, Low-Precision Quantization, Sparse Inference, HW/SW Co-Design

---

## Curriculum Vitae & Contact

[**Download CV (PDF)**](https://github.com/kooseo1296-debug/Bonseo-Koo/blob/main/BONSEO_KOO_CV.pdf)

**Email:** kooseo1296@sogang.ac.kr  
**GitHub:** [kooseo1296-debug](https://github.com/kooseo1296-debug)
