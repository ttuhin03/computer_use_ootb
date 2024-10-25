# Computer Use - OOTB

## 🌟 Overview
This is an out-of-the-box (OOTB) solution for Claude's new Computer Use APIs. 

**No Docker** is required, and it theoretically supports **any platform**, with testing currently done on **Windows**. This project provides a user-friendly interface based on Gradio. 🎨

## Update
10-25: Now you can **remotely control** your Computer through your Mobile.

[![Watch the video](https://img.youtube.com/vi/VH9bEUkdIAY/maxresdefault.jpg)](https://youtu.be/VH9bEUkdIAY)

## 🚀 Getting Started

### 0. Prerequisites
- Instal Miniconda on your system through this [link](https://www.anaconda.com/download?utm_source=anacondadocs&utm_medium=documentation&utm_campaign=download&utm_content=topnavalldocs). (Recommand Python Version: >= **3.11**).

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

### 3. Run the API ▶️
```bash
python app.py
```
A website will open at http://localhost:7860/. Enter the Anthropic API key (you can obtain it through this [website](https://console.anthropic.com/settings/keys)), then give commands to let the AI perform your tasks."

![gradio_interface](./assets/gradio_interface.png)

## 🖥️ Supported Systems
- **Windows** ✅

## ⚠️ Risks
- **Potential Dangerous Operations by the Model**: The models' performance is still limited and may generate unintended or potentially harmful outputs. Recommend continuously monitoring the AI's actions. 
- **Cost Control Challenges**: Each task may cost a few dollars. We'll optimize this in the future. 💸

## 📅 Roadmap

- [ ] **Interface Design**
  - [x] **Support for Gradio** ✨
  - [ ] **Simpler Installation**
  - [ ] **More Features**... 🚀
- [ ] **Platform**
  - [x] **Windows** 🖥️
  - [ ] **Mac** 🍎
- [ ] **Support for More MLLMs**
  - [x] **Claude 3.5 Sonnet** 🎵
  - [ ] **GPT-4o**
  - [ ] **Qwen2-VL**
  - [ ] ...
- [ ] **Improved Prompting Strategy**
  - [ ] Optimize prompts for cost-efficiency. 💡

