🚀 Week 0: VLSI System Design (VSD) Program – Foundation & Tool Setup

Welcome to my RISC‑V Reference SoC Tapeout Program repository!
Week 0 was all about setting up the environment and essential open-source tools for the upcoming RTL-to-GDS design journey.
The focus was on ensuring a stable workspace to handle synthesis, simulation, circuit analysis, and layout tasks.

🎯 System & Virtual Machine Setup

| Specification 💻        | Details 📋    |
| ----------------------- | ------------- |
| **Operating System 🐧** | Ubuntu 20.04+ |
| **RAM 💾**              | 6 GB          |
| **Storage 💿**          | 50 GB HDD     |
| **vCPUs ⚡**             | 4             |

💡 This configuration ensures smooth performance for toolchains, synthesis, and simulation.

⚙️ Tools Installed

The following open-source VLSI tools were installed & verified:

| Tool                             | Status     | Purpose             |
| -------------------------------- | ---------- | ------------------- |
| 🧠 Yosys                     | ✅ Complete | RTL Synthesis       |
| 📟 Icarus Verilog (Iverilog) | ✅ Complete | Verilog Simulation  |
| 📊 GTKWave                  | ✅ Complete | Waveform Debugging  |
| ⚡ Ngspice                   | ✅ Complete | Circuit Simulation  |
| 🎨 Magic VLSI                | ✅ Complete | Layout Design & DRC |

🧠 Yosys – RTL Synthesis Tool

Installation
```bash
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make build-essential clang bison flex \
libreadline-dev gawk tcl-dev libffi-dev git graphviz \
xdot pkg-config python3 libboost-system-dev \
libboost-python-dev libboost-filesystem-dev zlib1g-dev
make
sudo make install
```

✅ Verified with `yosys` command
<img width="871" height="656" alt="image" src="https://github.com/user-attachments/assets/691698d8-b287-42b6-bfff-f4760b385bef" />

📟 Iverilog – Verilog Simulator

Installation

```bash
sudo apt-get install iverilog
```

✅ Verified with `iverilog -v`
<img width="797" height="658" alt="image" src="https://github.com/user-attachments/assets/353f9567-e2ef-4448-a52d-9e8ffeeb6e08" />

📊 GTKWave – Waveform Viewer

**Installation**

```bash
sudo apt-get install gtkwave
```

✅ Verified with `gtkwave`
<img width="1180" height="663" alt="image" src="https://github.com/user-attachments/assets/24cd9fa2-cc88-4ceb-8ed6-91be2593b6dd" />

---

### ⚡ Ngspice – Circuit Simulator

**Installation**

```bash
sudo apt-get install ngspice
```

✅ Verified with `ngspice -v`
<img width="808" height="242" alt="image" src="https://github.com/user-attachments/assets/7c65397b-56b1-4670-8fb2-4ae20d74b395" />

---

### 🎨 Magic VLSI – Layout Tool

**Installation**

```bash
# Install dependencies
sudo apt-get install m4 tcsh csh libx11-dev tcl-dev tk-dev \
libcairo2-dev mesa-common-dev libglu1-mesa-dev libncurses-dev

# Clone Magic repo
git clone https://github.com/RTimothyEdwards/magic
cd magic

# Configure, build, install
./configure
make
sudo make install
```

✅ Verified with `magic`
<img width="1226" height="720" alt="image" src="https://github.com/user-attachments/assets/5f9d6062-99af-43d4-80ec-21015280c80c" />

---

## 🎉 Summary

* ✅ Environment setup complete
* ✅ All required tools installed & verified
* 🛠️ Workspace ready for **RTL-to-GDS design flow**

📂 **Repository**: `madesh_varadhan_RISCV_Tapeout_Program`
👨‍💻 **Author**: *madesh varadhan*
📚 **Program**: RISC‑V Reference SoC Tapeout Program


