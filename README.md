<h1 align="center">Iva Antonin</h1>

<p align="center">
  <b>AI Master's student · Machine learning, brain-computer interfaces and Python backends</b><br>
  Iasi, Romania
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/iva-antonin-b524a9307"><img src="https://img.shields.io/badge/LinkedIn-Iva%20Antonin-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:antonin.iva@protonmail.com"><img src="https://img.shields.io/badge/Email-antonin.iva%40protonmail.com-6D4AFF?style=flat-square&logo=protonmail&logoColor=white" alt="Email"></a>
  <a href="https://doi.org/10.1016/j.procs.2026.10.265"><img src="https://img.shields.io/badge/Paper-KES%202026-555555?style=flat-square" alt="KES 2026 paper"></a>
  <a href="https://doi.org/10.1109/ICSTCC66753.2025.11240280"><img src="https://img.shields.io/badge/Paper-ICSTCC%202025-555555?style=flat-square" alt="ICSTCC 2025 paper"></a>
</p>

---

I'm studying for a Master's in Artificial Intelligence at Gheorghe Asachi Technical University of Iasi, where I also teach Parallel and Distributed Algorithms as a teaching assistant.

I like building things that run outside a notebook: EEG models that drive real rehabilitation sessions, backends that turn a phone's LiDAR scan into body measurements, and the occasional Linux kernel driver.

- 🧠 **Now:** cross-subject EEG motor imagery classification and real-time brain-computer interfaces
- 🛠️ **Building:** Python backends with FastAPI and Django, containerized with Docker
- 🤖 **Tooling:** [context-kit](https://github.com/anton1n/context-kit), my open-source Claude Code plugin for AI-assisted development
- 📄 **Published:** two first-author conference papers on deep learning for EEG and edge AI
- 🎯 **Looking for:** internships and junior roles in ML engineering or Python backend development

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**EEGTCNet**](https://github.com/anton1n/cnn-transformer-eeg) | CNN-Transformer for cross-subject EEG motor imagery classification. **80.8% leave-one-subject-out accuracy** on PhysioNet (109 subjects), with layer-wise fine-tuning to adapt to new users. Published at KES 2026. | PyTorch, MNE, scikit-learn, Braindecode |
| [**TraViMo BCI platform**](https://github.com/anton1n/Licenta_Iva_Antonin) | My Bachelor's thesis, part of the [TraViMo / TRAVEE](https://travee.upb.ro/en/home-page/) post-stroke rehabilitation project. OpenVibe plugins for motor-imagery sessions and EEG streaming, plus a real-time classifier served over TCP. | C++, CMake, Python, OpenVibe |
| [**context-kit**](https://github.com/anton1n/context-kit) | Claude Code plugin (MIT). Sets up 5 AI developer tools in one command, including an MCP server; exports and imports a project's agent context (sessions, memory, plans) across machines with secret redaction; keeps agent memory inside the repo through a SessionStart hook. | Bash, Claude Code plugins, MCP |
| [**Events platform with RBAC**](https://github.com/anton1n/rails_events_rbac_webapp) | Microservices system with an identity server, JWT authentication and role-based access control. Services communicate over gRPC. | Ruby on Rails, gRPC, MongoDB, TypeScript, Docker Compose |
| [**MacBook SPI / Touch Bar driver**](https://github.com/anton1n/macbook12-spi-driver) | Fork of the Linux input driver for 2015–2018 MacBooks. Adds Linux 6.18 and clang/LTO kernel support and fixes the Touch Bar after suspend. | C, Linux kernel |
| [**ATV630 Modbus controller**](https://github.com/anton1n/practicaFulminis) | Modbus TCP controller and web interface for a Schneider ATV630 industrial drive, with MkDocs documentation. | Python, Modbus TCP |
| **Metasensys** *(private)* | Cloud backend for an EU co-funded body-scanning app: receives a LiDAR scan from iOS and returns body measurements with about 2 cm error. [Project site](https://www.metasensys.io/despre-proiect/) | FastAPI, Open3D, Firebase, Docker |

## Publications

- **EEGTCNet: A CNN-Transformer Architecture with Layer-wise Fine-Tuning for Cross-Subject EEG Motor Imagery Classification**<br>
  Iva Antonin, Stefan-Daniel Achirei · *KES 2026, Procedia Computer Science 292* · [DOI](https://doi.org/10.1016/j.procs.2026.10.265)
- **Edge AI on Obsolete Hardware: Fully Local Emotion Recognition on the NAO Robot**<br>
  Antonin Iva, Otilia Zvoristeanu, Stefan-Daniel Achirei · *ICSTCC 2025, IEEE* · [DOI](https://doi.org/10.1109/ICSTCC66753.2025.11240280)

## Tech I use

**Machine learning**<br>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">

**AI tooling**<br>
<img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code">
<img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol">
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">

**Backend**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
<img src="https://img.shields.io/badge/Ruby%20on%20Rails-D30001?style=flat-square&logo=rubyonrails&logoColor=white" alt="Ruby on Rails">

**Systems and DevOps**<br>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">

---

<p align="center"><i>Open to internships and junior roles in Iasi or remote. The fastest way to reach me is <a href="https://www.linkedin.com/in/iva-antonin-b524a9307">LinkedIn</a>.</i></p>
