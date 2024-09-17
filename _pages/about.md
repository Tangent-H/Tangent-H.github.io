---
permalink: /
title: "Tingjun's Homepage"
excerpt: "Welcome to my personal webpage! 🥰"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


# About Me 👋
Hello! I'm **Tingjun Huang**, a senior undergraduate majoring in **Information Engineering** at the [**Southern University of Science and Technology (SUSTech)**](https://www.sustech.edu.cn/en/). My academic interests span **robotics**, **human-computer interaction**, **large models**, **machine learning**, **signal processing**, and **circuit design**. I’m passionate about pushing the boundaries of technology to create systems that can perceive, plan, and interact with the real world 🌍.

Throughout my academic journey, I’ve been fortunate to work on exciting research projects. At the [**National University of Singapore (NUS)**](https://nus.edu.sg/), I collaborated with Prof. [Lin Shao](https://linsats.github.io/) to implement **social navigation on robots** using Vision Language Models (VLM). At SUSTech, I’m working with Prof. [Hong Zhang](https://scholar.google.com/citations?hl=en&user=J7UkpAIAAAAJ) on **Visual Place Recognition (VPR)**, enhancing mobile robots' ability to recognize and navigate their surroundings with greater accuracy.

I’m also actively involved in robotics competitions like [**RoboMaster**](https://www.robomaster.com/en-US). As part of Team [ARTINX](https://artinx.club/), we proudly reached the national top 16 in 2023 🏆.

🚀 **My Short-term Goals:**

- Leverage large foundation models to enhance robot planning abilities 🤖
- Develop reliable, explainable tools for large models to utilize 🔧
- Build a versatile robot embodiment for real-world applications 🌟

🌱 **My Long-term Vision:**

I aim to contribute to the fields of **robotics**, **AI**, and **engineering** by developing innovative solutions that benefit both technology and humankind.


# Education 🎓
- **Southern University of Science and Technology (SUSTech)**  
  *Undergraduate in Information Engineering (2021-Present)*  
  **GPA**: 3.92/4.0 (Rank: 1/25)

<span class='anchor' id='experience-'></span>
# Experience 🛠️
- **National University of Singapore (NUS)**

  *Visiting Scholar (Jun 2024 - Sept 2024)*
  
  I researched and implemented a pipeline for task-oriented social navigation, allowing robots to interact with human environments based on natural language instructions. Key tasks included:
  - Researched current implementation strategies, datasets, and simulation environments related to social navigation.
  - Proposed a task‑oriented social navigation pipeline capable of receiving natural language task descriptions and adopting appropriate social strategies based on the task content and social entities involved. For instance, when deployed on a medication delivery robot, this pipeline enables the robot to navigate through crowds, follow doctors in a socially compliant manner, and avoid potential social entities, such as open doors.
  - Keywords: Social Navigation, Vision Language Model(VLM) Planning, Fast‑slow System, RLHF

# Projects 🚀

<!-- Fynthesizer -->
<div class='paper-box'><div class='paper-box-image'><div><img src='images/projects/fynthesizer_project.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**FPGA Digital Synthesizer (Fynthesizer)**:

**Description**: Fynthesizer is an FPGA-based 3-oscillator synthesizer that generates customizable waveforms, supporting up to 12 simultaneous key presses. It allows fine-tuning parameters like ADSR, pitch offset, and volume, and can be controlled via a MIDI controller or a virtual MIDI keyboard. The project provides a GUI for adjusting settings and supports various waveform modules. It is built using the Nexys DDR4 FPGA board and Vivado 2020.2, and includes Python scripts for GUI control and MIDI playback.

**Highlights**: Real-time synthesizer on an FPGA board, supporting multi-oscillator control and customizable GUI integration. Integrated MIDI controller for dynamic control.

[**Project**](https://github.com/TangentH/Fynthesizer)
</div>
</div>  

<!-- Robomaster -->
<div class='paper-box'><div class='paper-box-image'><div><img src='images/projects/energy_mechanism.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Robomaster Energy Mechanism**:

**Description**: The energy mechanism system controls LED lighting, while simulating impact detection using infrared signals, with customizable patterns and future sensor integration capabilities.

**Highlights**: Modularity, Memory Efficiency, Infrared Control, Low Cost

[**Project**](https://github.com/TangentH/RM2023_Energy_Mechanism?tab=readme-ov-file)
</div>
</div>  

<!-- ART -->
<div class='paper-box'><div class='paper-box-image'><div><img src='images/projects/ART.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Augmented Reality Tapestry (ART)**:

**Description**: ART (Augmented Reality Tapestry) is an AR system that enhances gallery experiences using ArUco marker detection and Poisson blending. The system accurately detects ArUco markers for marker-based AR interactions and seamlessly blends images using Poisson techniques for a coherent visual experience. Users can run demos with their camera or pre-recorded videos, compare detection methods (custom vs OpenCV), and test image fusion via Poisson blending. The implementation supports benchmarking and adjusting fusion techniques for optimal results in both images and videos.

**Highlights**: Seamless Blending, Handcrafted Real-time Detection, Customizable Fusion

[**Project**](https://github.com/TangentH/AR-Gallery)
</div>
</div>  

# Awards 🏆
- **First Prize**, RoboMaster University Championship (2023) – National level  
- **Second Prize**, National College Students’ Mathematics Modeling Contest (2022)

# Skills 💡
- **Programming**: Python (PyTorch, NumPy, Matplotlib), C/C++, MATLAB, VHDL  
- **Tools**: ROS, Ubuntu, Git, AI Habitat, Unity, Vivado  
- **In-Lab Skills**: PCB Design, SMT Soldering, STM32 Embedded Systems

# Interests 🌟
When I’m not working on robotics, I enjoy **long-distance running** 🏃‍♂️. I also play **badminton** regularly 🏸, and have trained under world champion [Sun Yu](https://en.wikipedia.org/wiki/Sun_Yu_(badminton)). As a creative outlet, I play the **piano** 🎹, and have performed at the Mid‑Autumn Festival party in the college

