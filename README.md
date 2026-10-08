# Hi, I'm kghggt 👋

**Python 工程方向的开发者** —— 喜欢把想法做成真正能跑起来的完整系统。

目前在做：实时流媒体 · 桌面应用 · 机器学习实验工程化。

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PyQt5](https://img.shields.io/badge/PyQt5-41CD52?logo=qt&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)

---

## 🛠 技术栈

| | |
|---|---|
| **语言** | Python、Java、C++、C（JNI） |
| **框架 / 库** | FastAPI、PyQt5、PyTorch、scikit-learn、OpenCV |
| **工程能力** | 端到端系统设计与部署、模块化重构、异步与多线程、LLM / TTS 应用集成、实验可复现性 |
| **工具** | Git、Linux 服务器部署 |

---

## 🚀 精选项目

### [CamSee](https://github.com/kghggt/CamSee) — 端到端实时视频监控系统
USB 摄像头采集 → 云端服务 → 浏览器实时查看。客户端与服务端分离，通过 WebSocket 推流，带 token 鉴权与一键部署脚本，已在云服务器上完整跑通。
`Python` `OpenCV` `WebSockets` `FastAPI` `Uvicorn`

### [HER — Human Emotion Resonance](https://github.com/kghggt/HER-Human-Emotion-Resonance) — AI 情感陪伴桌面应用
PyQt5 桌面客户端 + 本地 GPT-SoVITS 语音合成 + DeepSeek-V3 大语言模型。v2.0 将 597 行的单体文件重构为 5 个高内聚模块，新增高 DPI 缩放适配，并自研正则过滤让 TTS 跳过括号动作描述。
`PyQt5` `GPT-SoVITS` `LLM API` `信号槽异步`

### [tabpfn-prior-correction](https://github.com/kghggt/tabpfn-prior-correction) — 可复现的表格学习实验流水线
*Pattern Recognition Letters* 在投论文的配套代码。覆盖 19 个对比方法、414 个 run unit 的完整 pipeline，论文里每个数字都能追溯到具体产出脚本，支持断点续跑。
`PyTorch` `TabPFN` `实验工程` `可复现性`

### [UVCcam-](https://github.com/kghggt/UVCcam-) — 多路 USB 摄像头采集
基于 saki4510t/UVCCamera 的二次开发。应用层扩展为 **6 路 UVC 摄像头同时预览、各自独立录制**，并补齐了 Android 11 的存储权限申请链路；native 层基于 libusb / libuvc 的 C 代码，通过 JNI 调用。
`Android` `Java` `C/JNI` `UVC`

---

## 📫 联系我

- **Email**：kghggt8@gmail.com

> 如果你对其中某个项目感兴趣，欢迎提 issue 交流。
