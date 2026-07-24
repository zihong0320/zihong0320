<div align="center">
  <h1>👋 Hi there, I'm Jihong Kim</h1>
  <h3>Hardware / Embedded AI / Verification Engineer</h3>
  <br>
  <p>💡 <b>하드웨어-소프트웨어 통합 설계(Co-design)</b>와 <b>온디바이스 AI / 아키텍처 최적화</b>에 관심이 많은 개발자입니다.</p>
  <p>🛠 대용량 데이터 처리 병목 해결 및 하드웨어 가속기/임베디드 파이프라인 최적화 과정에서 즐거움을 느낍니다.</p>
</div>

---

## 🚀 Tech Stack

### ⚡ Hardware & Verification
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1F425F?style=for-the-badge) ![Verilog](https://img.shields.io/badge/Verilog-00599C?style=for-the-badge) ![UVM](https://img.shields.io/badge/UVM-002B49?style=for-the-badge)

### 💻 Embedded AI & Software
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

### ⚙️ Edge Boards, Interfaces & Tools
![Jetson Orin Nano](https://img.shields.io/badge/Jetson_Orin_Nano-76B900?style=for-the-badge&logo=nvidia&logoColor=white) ![Vivado](https://img.shields.io/badge/Vivado-FF6F00?style=for-the-badge) ![UART](https://img.shields.io/badge/UART-412991?style=for-the-badge) ![SPI/I2C](https://img.shields.io/badge/SPI%2FI2C-008080?style=for-the-badge) ![AXI4-Lite](https://img.shields.io/badge/AXI4--Lite-D9381E?style=for-the-badge) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📁 Key Projects

### 🚀 4x4 MAC Array Accelerator [![Repo](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/zihong0320/4x4_Mac_Array_Accelerator)
> **행렬 연산 가속을 위한 Systolic Array 구조 MAC 가속기 설계**
* **Tech:** `Verilog` `Pipeline Architecture`
* **Focus:** 4x4 행렬 연산을 위한 데이터패스 설계 및 파이프라이닝을 통한 병렬 연산 최적화.

### 🎮 RHYTHM BEAT (VGA Rhythm Game) [![Repo](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/zihong0320/VGA_RHYTHM_GAME)
> **OV7670 카메라 객체 인식 기반 모션 리듬 게임 및 실시간 통신 시스템**
* **Tech:** `Verilog` `UART` `FIFO` `VGA` `Python`
* **Focus:** FIFO 기반 UART Sender 타이밍 제어 및 1-Byte Event Trigger를 통한 PC-FPGA 간 프레임 동기화(Latency 완화).
* **Result:** 파이프라인 레지스터 설계를 통한 Timing Violation 해결 (WNS +4.1ns 달성).
* 
### 🧠 Multi-cycle RISC-V 32I Core & APB PERIPHERAL [![Repo](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/zihong0320/Multi-cycle_RISC-V_32I_APB_Peripheral)
> **RV32I 명령어 셋 기반 Multi-cycle 프로세서 설계 및 검증**
* **Tech:** `Verilog` `RISC-V` `Harvard Architecture`
* **Focus:** Instruction Fetch부터 Write-Back까지의 Datapath 설계 및 Control Unit FSM 구현. RV32I 기본 명령어 동작 확인, APB Peripheral 설계, C Algorithm 적용.

### 🖥️ SoC AXI4-Lite SPI/I2C Peripheral [![Repo](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/zihong0320/SoC_AXI4-Lite_SPI_I2C_Peripheral)
> **MicroBlaze SoC 기반 AXI4-Lite 통신 IP 설계 및 계층형 SW 구축**
* **Tech:** `SystemVerilog` `AXI4-Lite` `UVM` `SPI/I2C` `C`
* **Focus:** Application ➔ Driver ➔ HAL ➔ HW로 이어지는 계층형 소프트웨어 아키텍처 적용 및 하드웨어 타이밍 최적화.
* **Result:** SystemVerilog UVM을 활용한 Random Test 2,000회 PASS 및 Functional Coverage 100% 달성.

### 🦯 Intelligent Navigation for Visually Impaired [![Repo](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/zihong0320/Intelligent_Navigation_for_the_Visually_Impaired)
> **시각장애인을 위한 Jetson Orin Nano 기반 실시간 온디바이스 보행 보조 안내 시스템**
* **Tech:** `Jetson Orin Nano` `YOLO11` `TensorRT` `Ollama(Local LLM)` `gTTS` `Python`
* **Focus:** 
  * 다중 YOLO 추론 결과 파싱, 코드 총괄 및 로컬 LLM(Ollama) 연동을 통한 상황 맞춤형 안내 문장 생성.
  * 초경량 모델(`Qwen2:0.5b`) 및 TensorRT 가속 적용을 통한 실시간 온디바이스 Latency 극대화.
* **Result:** Gemma3(4b) 대비 5초 이상의 Latency를 수초 이하 실시간 반응 수준으로 최적화.

---

<div align="center">
  <i>📫 How to reach me: <b>your.email@example.com</b></i>
</div>
