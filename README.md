# Computer Use - OOTB

## 🌟 Overview
This is an out-of-the-box (OOTB) solution for Claude's new **Computer Use** APIs designed to streamline and enhance computer usage. This project offers a user-friendly interface based on Gradio. 🎨

![gradio_interface](./assets/gradio_interface.png)

## 🚀 Getting Started

### 1. Clone the Repository 📂
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
python api.py
```
A website will open; follow the prompts to proceed.

## 🖥️ Supported Systems
- **Windows** ✅

## ⚠️ Risks
- **Potential Dangerous Operations by the Model**: Advanced models have the capability to generate unintended or potentially harmful outputs. To mitigate this risk, it is essential to implement strict safety checks, filters, and user constraints on potentially risky actions or prompts.
- **Cost Control Challenges**: Enhanced features and more sophisticated models may lead to increased operational costs. Regular monitoring of API usage and expenses is critical to prevent budget overruns. It is vital to carefully balance improvements and cost-efficiency. 💸

## 📅 Release Plan

- [ ] **Interface Design**
  - [x] **Support for Gradio** ✨
  - [ ] **Simpler Installation**: Streamline the installation process for faster setup.
  - [ ] **More Features**... 🚀
- [ ] **Platform**
  - [x] **Windows** 🖥️
  - [ ] **Mac** 🍎
- [ ] **Support for More MLLMs**
  - [x] **Claude 3.5 Sonnet** 🎵
  - [ ] **GPT-4o**: Integration with GPT-4o for enhanced capabilities.
  - [ ] **Qwen2-VL**: Support for Qwen-2VL to improve visual and multimodal understanding. 📸
  - [ ] ...
- [ ] **Improved Prompting Strategy**
  - [ ] Optimize prompts for cost-efficiency. 💡

