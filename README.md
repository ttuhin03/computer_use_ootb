<h2 align="center"> <a href="https://computer-use-ootb.github.io">The Dawn of GUI Agent: A Preliminary Case Study with Claude 3.5 Computer Use</a></h2>
<h5 align="center"> If you like our project, please give us a star ⭐ on GitHub for the latest update.</h5>

<h5 align=center>

[![arXiv](https://img.shields.io/badge/Arxiv-2411.10323-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2411.10323)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fshowlab%2Fcomputer_use_ootb&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fshowlab%2Fcomputer_use_ootb&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)

</h5>

## 🌟 Overview
This is an out-of-the-box (OOTB) solution for Claude's new Computer Use APIs. 

**No Docker** is required, and it supports both **Windows** and **macOS**. This project provides a user-friendly interface based on Gradio. 🎨

For more information, you can visit our [project page](https://computer-use-ootb.github.io). 🌐

## Update
- **[2024/11/18]** We've released a deep analysis of Claude 3.5 Computer Use: [https://arxiv.org/abs/2411.10323](https://arxiv.org/abs/2411.10323).
- **[2024/11/11]** Forget about the low-resolution display limit set by Anthropic — you can now use *any resolution you like* and still keep the **screenshot token cost low** 🎉!
- **[2024/11/11]** Now both **Windows** and **macOS** platforms are supported 🎉!
- **[2024/10/25]** Now you can **Remotely Control** your computer 💻 through your mobile device 📱 — **No Mobile App Installation** required! Give it a try and have fun 🎉.

## Demo Video

<a href="https://youtu.be/0bcYVrV_c3g" target="_blank">
    <img src="https://img.youtube.com/vi/0bcYVrV_c3g/maxresdefault.jpg" alt="Watch the video">
</a>

[![Watch the video](https://img.youtube.com/vi/Ychd-t24HZw/maxresdefault.jpg)](https://youtu.be/Ychd-t24HZw)

[![Watch the video](https://img.youtube.com/vi/cvgPBazxLFM/maxresdefault.jpg)](https://youtu.be/cvgPBazxLFM)

## 🚀 Getting Started

### 0. Prerequisites
- Instal Miniconda on your system through this [link](https://www.anaconda.com/download?utm_source=anacondadocs&utm_medium=documentation&utm_campaign=download&utm_content=topnavalldocs). (**Python Version: >= 3.11**).

### 1. Clone the Repository 📂
Open the Conda Terminal. (After installation Of Miniconda, it will appear in the Start menu.)
Run the following command on **Conda Terminal**.
```bash
git clone https://github.com/showlab/computer_use_ootb.git
cd computer_use_ootb
```

### 2. Install Dependencies 🔧
```bash
pip install -r dev-requirements.txt
```

### 3. Start the Interface ▶️
```bash
python app.py
```
If you successfully start the interface, you will see two URLs in the terminal:
```bash
* Running on local URL:  http://127.0.0.1:7860
* Running on public URL: https://xxxxxxxxxxxxxxxx.gradio.live (Do not share this link with others, or they will be able to control your computer.)
```

### 4. Control Your Computer with Any Device can Access the Internet
- **Computer to be controlled**: The one installed software.
- **Device Send Command**: The one opens the website.
  
Open the website at http://localhost:7860/ (if you're controlling the computer itself) or https://xxxxxxxxxxxxxxxxx.gradio.live in your mobile browser for remote control.

Enter the Anthropic API key (you can obtain it through this [website](https://console.anthropic.com/settings/keys)), then give commands to let the AI perform your tasks.

Mobile Interface

<img src="./assets/gradio_mobile.jpg" alt="gradio_interface" width="30%">

Desktop Interface
![gradio_interface](./assets/gradio_interface.png)

## 🖥️ Supported Systems
- **Windows** ✅
- **macOS** ✅

## ⚠️ Risks
- **Potential Dangerous Operations by the Model**: The models' performance is still limited and may generate unintended or potentially harmful outputs. Recommend continuously monitoring the AI's actions. 
- **Cost Control Challenges**: Each task may cost a few dollars. We'll optimize this in the future. 💸

## 📅 Roadmap
- [ ] **Explore available features**
  - [ ] The Claude API seems to be unstable when solving tasks. We are investigating the reasons: resolutions, types of actions required, os platforms, or planning mechanisms. Welcome any thoughts or comments on it.
- [ ] **Interface Design**
  - [x] **Support for Gradio** ✨
  - [ ] **Simpler Installation**
  - [ ] **More Features**... 🚀
- [ ] **Platform**
  - [x] **Windows** 
  - [x] **Mobile** (Send command)
  - [x] **macOS**
  - [ ] **Mobile** (Be controlled)
- [ ] **Support for More MLLMs**
  - [x] **Claude 3.5 Sonnet** 🎵
  - [ ] **GPT-4o**
  - [ ] **Qwen2-VL**
  - [ ] ...
- [ ] **Improved Prompting Strategy**
  - [ ] Optimize prompts for cost-efficiency. 💡

## Join Discussion
Welcome to discuss with us and continuously improve the user experience of Computer Use - OOTB. Reach us using this [Discord Channel](https://discord.gg/9GQkyWer) or the WeChat QR code below!

<img src="./assets/group_chat_1113.jpg" alt="gradio_interface" width="30%">





