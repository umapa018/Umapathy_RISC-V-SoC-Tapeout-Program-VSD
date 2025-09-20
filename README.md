# 🖥️ RISC-V Reference SoC Tapeout Program VSD
<div align="center">

[![RISC-V](https://img.shields.io/badge/RISC--V-SoC%20Tapeout-blue?style=for-the-badge&logo=riscv)](https://riscv.org/)
[![VSD](https://img.shields.io/badge/VSD-Program-orange?style=for-the-badge)](https://vsdiat.vlsisystemdesign.com/)
![India](https://img.shields.io/badge/Made%20in-India-saffron?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHJlY3Qgd2lkdGg9IjI0IiBoZWlnaHQ9IjgiIGZpbGw9IiNGRjk5MzMiLz4KPHJlY3QgeT0iOCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjgiIGZpbGw9IiNGRkZGRkYiLz4KPHJlY3QgeT0iMTYiIHdpZHRoPSIyNCIgaGVpZ2h0PSI4IiBmaWxsPSIjMTM4ODA4Ii8+Cjwvc3ZnPgo=)

</div>

Welcome to my journey through the **SoC Tapeout Program VSD**!  
This repository documents my **week-by-week progress** with tasks inside each week.  

> "In this program, we learn to design a System-on-Chip (SoC) from basic RTL to GDSII using open-source tools.  
> Part of India’s largest collaborative RISC-V tapeout initiative, empowering 3500+ participants to build silicon and advance the nation’s semiconductor ecosystem.
> Also all the assigned task is been done by me in Oracle Virtual Box under Ubuntu"

---

## 📅 Week 0 — Setup & Tools

| Task | Description | Status |
|------|-------------|--------|
| [**Task 0**](Task0/README.md) | 🛠️ Tools Installation — Installed **Icarus Verilog**, **Yosys**, and **GTKWave** | ✅ Done |

---

### 📺 Resizing Ubuntu VM for Better Display

```bash
sudo apt update
sudo apt install build-essential dkms linux-headers-$(uname -r)
cd /media/<username>/VBox_GAs_7.1.8/
./autorun.sh
```

## 🔧 Tool Installation & Verification  

#### 1️⃣ <ins>Yosys (Synthesis Tool) </ins> 

```bash
sudo apt-get update
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
git submodule update --init --recursive
make
sudo make install
```



### 2️⃣ <ins>Icarus Verilog (Simulation Tool)</ins>

```bash
sudo apt-get update
sudo apt-get install iverilog
```

### 3️⃣ <ins>GTKWave (Waveform Viewer)</ins>

```bash
sudo apt-get update
sudo apt install gtkwave
```

### 🌟 Learnings from Week 0
- Exposure in installing **open-source EDA tools**: Yosys, Icarus Verilog, GTKWave.  
- Implementation on **Ubuntu VM** inside Oracle VirtualBox.  


## Acknowledgment  

I am sincerely thankful to [**Kunal Ghosh**](https://github.com/kunalg123) and **[VLSI System Design (VSD)](https://vsdiat.vlsisystemdesign.com/)** for the invaluable opportunity to participate in the RISC-V SoC Tapeout Program, which has been a tremendous learning experience.

I also acknowledge the support of **RISC-V International**, India Semiconductor Mission (ISM), VLSI Society of India (VSI), and Efabless for making this initiative possible and for empowering students and enthusiasts across India to gain hands-on experience in semiconductor design.

A special note of appreciation goes to [**ChatGPT (OpenAI)**](https://chatgpt.com/) 🤖 for assisting in structuring and refining this entire progress. Its guidance helped me present complex technical steps, code blocks, and workflow descriptions clearly and professionally, making this repository more organized and reader-friendly.

## 📈 **Weekly Progress Tracker**

[![Week 0](https://img.shields.io/badge/Week%200-Tools%20Setup-green?style=flat-square)](Task0)
![Week 1](https://img.shields.io/badge/Week%201-Up%20coming-lightgrey?style=flat-square)
![Week 2](https://img.shields.io/badge/Week%202-Upcoming-lightgrey?style=flat-square)



**🔗 Program Links:**
[![VSD Website](https://img.shields.io/badge/VSD-Official%20Website-blue?style=flat-square)](https://vsdiat.vlsisystemdesign.com/)
[![RISC-V](https://img.shields.io/badge/RISC--V-International-green?style=flat-square)](https://riscv.org/)
[![Efabless](https://img.shields.io/badge/Efabless-Platform-orange?style=flat-square)](https://efabless.com/)



---

