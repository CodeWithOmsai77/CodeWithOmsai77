<h1 align="center">Hi 👋, I'm Omsai</h1>

<h3 align="center">
Aspiring ASIC / RTL Design Engineer — Digital Logic to Silicon ⚡
</h3>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=24&duration=2500&pause=1000&color=00F7FF&center=true&vCenter=true&width=800&lines=RTL+Design+%7C+Verilog;Digital+IC+Design;From+Logic+Gates+to+RISC-V;Building%2C+Simulating%2C+Debugging;Every+Waveform+Tells+a+Story" />
</p>

---

## About Me

I'm a 3rd-year engineering student who genuinely loves the moment a waveform finally matches what's in my head. Somewhere between a truth table and a clean simulation, digital logic just *clicked* for me — and now I'm chasing that all the way to silicon.

🔭 Focused on becoming an **ASIC / RTL Design Engineer**
📐 My path: Digital Logic → Verilog → RTL Design → SystemVerilog → RTL Verification → Computer Architecture → RISC-V → ASIC Design Flow
🧩 I don't call a design "done" just because it compiles — every module goes through: understand the spec → derive the logic → write the RTL myself → simulate → debug → verify → understand *why* it works
⚡ Long-term obsession: AI hardware accelerators — systolic arrays, GEMM, the stuff that makes matrix math run in silicon instead of software

<br clear="right"/>

---

## 🧭 Learning Roadmap

| Stage | Topics | Status |
|---|---|---|
| Digital Logic | Gates, truth tables, Boolean derivation | ✅ Done |
| Verilog Fundamentals | MUX/DEMUX (flat + hierarchical, 2:1→16:1) | ✅ Done |
| RTL Design — Combinational | Encoders, decoders, comparators, adders | 🔨 In progress (4:2 Encoder) |
| RTL Design — Sequential | Flip-flops, registers, counters, FSMs | 🔜 Next |
| SystemVerilog & Verification | Assertions, coverage, self-checking TBs | 🔜 |
| Computer Architecture | Datapath, ALU, register file, pipelining | 🔜 |
| RISC-V | CPU design | 🔜 |
| ASIC Flow | Synthesis → STA → P&R → signoff | 🔜 Long-term |

---

## ⚡ Why I'm Doing This

<img align="right" width="260" src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.gif">

Software tells the hardware what to do. RTL design is where you actually *build* the thing that does it — gates, timing, parallelism, real physics underneath the logic. That's the part I can't stop thinking about.

Every design in this repo, I built and broke it myself first. The gates were easy. The MUX/DEMUX hierarchy is where it started feeling like real engineering — routing signals, splitting select lines across stages, watching a 16:1 structure emerge from four small reusable 4:1 blocks. That's the addiction: small verified pieces becoming something bigger.

<br clear="right"/>

---

## 🔨 What I'm Building Right Now

- **Completed:** All 7 basic logic gates (AND/OR/NOT/NAND/NOR/XOR/XNOR) with testbenches
- **Completed:** 2:1 → 4:1 → 8:1 → 16:1 multiplexers, including a 16:1 MUX built hierarchically from 4:1 MUXes
- **Completed:** 1:2 → 1:4 → 1:8 → 1:16 demultiplexers, including hierarchical 1:4-from-1:2 and 1:16-from-1:4 builds
- **In progress:** 4:2 Encoder — first design in the new `RTL_Design/` section, moving from "writing Verilog" to genuine RTL/architecture thinking

---

## 🛠️ Toolchain & Skills

<table border="0">
 <tr>
    <td width="50%">
      <b>🧠 Hardware, RTL & Chip Design (Primary Focus)</b><br />
      <img src="https://img.shields.io/badge/Verilog-RTL_Design-FF4B4B?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/Digital_Design-Combinational_+_Sequential-1E90FF?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/FSM-Control_Logic_Design-6A5ACD?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/Computer_Architecture-CPU_&_Datapath-20B2AA?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/ALU-Arithmetic_Logic_Design-FF8C00?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/Processor-RTL_to_CPU_Path-DC143C?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/Memory-Basic_Register_&_Storage-9370DB?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/Timing-Setup_Hold_Basics-4682B4?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/Clocking-Synchronous_Design-2E8B57?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/RTL_Verification-Testbench_&_Waveform_Debug-8A2BE2?style=flat-square" />
    </td>
    <td width="50%">
      <b>💻 Software, Systems & Toolchain</b><br />
      <img src="https://img.shields.io/badge/Linux-WSL2_Environment-FCC624?style=flat-square&logo=linux&logoColor=black" /><br />
      <img src="https://img.shields.io/badge/Bash-Scripting_&_Automation-4EAA25?style=flat-square&logo=gnubash" /><br />
      <img src="https://img.shields.io/badge/C-Systems_&_Bitwise-A8B9CC?style=flat-square&logo=c" /><br />
      <img src="https://img.shields.io/badge/C++-OOP_&_Performance-00599C?style=flat-square&logo=cplusplus" /><br />
      <img src="https://img.shields.io/badge/Python-Automation_&_Tooling-3776AB?style=flat-square&logo=python" /><br />
      <img src="https://img.shields.io/badge/Git-Version_Control_&_Workflow-F05032?style=flat-square&logo=git" /><br />
      <img src="https://img.shields.io/badge/Debugging-Logs_&_Waveform_Analysis-708090?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/Data_Handling-Parsing_&_Reports-6B7280?style=flat-square" /><br />
      <img src="https://img.shields.io/badge/CLI-Terminal_Productivity-000000?style=flat-square&logo=gnubash" />
    </td>
 </tr>
</table>


```
RTL Design → Testbench → Simulation → Waveform Analysis → Debug → Verify
```

---
## 📊 Engineering Progress

- **Phase I: Foundation (Verilog, C, Linux)** ![Progress](https://geps.dev/progress/70)

- **Phase II: VLSI Core (SystemVerilog, RISC-V)** ![Progress](https://geps.dev/progress/20)

- **Phase III: Embedded (STM32, RTOS, PCB)** ![Progress](https://geps.dev/progress/0)

- **Phase IV: Robotics (ROS2, Computer Vision)** ![Progress](https://geps.dev/progress/0)

- **Phase V: Software (DSA, Advanced C++)** ![Progress](https://geps.dev/progress/55)

- **Phase VI: Future Tech (AI Hardware, Chiplets)** ![Progress](https://geps.dev/progress/5)
---

## 🏆 Featured Repositories

- 📂 [**Verilog-Fundamentals**](https://github.com/CodeWithOmsai77/Verilog-Fundamentals) — Logic gates through hierarchical MUX/DEMUX design, now moving into RTL design with encoders. My main RTL portfolio.
- 📂 [**Progress-Tracker**](https://github.com/CodeWithOmsai77/Progress-Tracker) — Self-paced VLSI & electronics roadmap: logic gates to tapeout, with progress tracking.
- 📂 [**c-data-structures**](https://github.com/CodeWithOmsai77/c-data-structures) — Data structure implementations in C, supporting the systems-programming side of hardware work.
- 📂 [**python-learning**](https://github.com/CodeWithOmsai77/python-learning) — Scripting and automation, chapter-wise.

---

## 💼 Target Roles

ASIC RTL Design Engineer · Digital IC Design Engineer · RTL Verification Engineer

---

## 📬 Connect

<p align="left">
  <a href="https://github.com/CodeWithOmsai77">
    <img src="https://img.shields.io/badge/GitHub-CodeWithOmsai77-181717?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://www.linkedin.com/in/omsai-dasari-b18b55381">
    <img src="https://img.shields.io/badge/LinkedIn-Omsai_Dasari-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  ⭐ <b>Real Skills • Real Projects • Consistent Growth • Long-Term Vision</b>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00d4ff&height=90&section=footer&text=Keep%20Building&fontSize=20&fontColor=ffffff&animation=fadeIn"/>
</p>

