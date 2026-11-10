# Hi, I'm Peerzada Rabet 👋 [![](https://visitcount.itsvg.in/api?id=peerzadarabet1807&icon=0&color=0)](https://visitcount.itsvg.in)

**Data scientist at ZS, working on generative AI.**

I'm based in Srinagar, Kashmir, and most of what I build outside work applies machine learning to farming and food: adulterated saffron from Pampore, apple scab in Shopian's orchards, disease screening for poultry farms. I also build healthcare AI and local-first LLM tools.

I write up results the way I'd want to read them. My poultry classifier scores 96.7% on held-out photos from its training data and 79.5% on a separately collected, PCR-confirmed set, and its README leads with that 17-point gap. The saffron model reaches 97.3% on its test set, and when Grad-CAM showed it was partly reading the paper the pure samples were photographed on, that went into the README too.

🌐 [The Organic Revival](https://www.theorganicrevival.com/) · 📫 peerzada.rabet2@gmail.com · 📍 Srinagar, Kashmir

## What I'm doing now

- Data scientist at ZS, focused on generative AI.
- Building PanunGPT with Wiser AI: a local-first AI workstation for Windows. It runs on Ollama and routes each request to a reasoning, coding, vision or lightweight model, with page-cited PDF Q&A and local speech-to-text. Nothing leaves the machine. The repo is private for now.
- Advocating sustainable farming at [The Organic Revival](https://www.theorganicrevival.com/).

## Selected work

| Project | What it is | Result |
|---|---|---|
| [Saffron Check](https://github.com/peerzadarabet1807/saffron-adulteration-detection) · [demo](https://peerzadarabet1807.github.io/saffron-adulteration-detection/) | Tells two kinds of pure saffron from three counterfeits using a photo of a single thread. ResNet50V2 with Grad-CAM, running in the browser on TensorFlow.js. Started as my B.Tech thesis at IIT Kharagpur. | 97.3% test accuracy (73 of 75); the original thesis CNN reached about 71% on validation |
| [FrostGuard-Scab](https://github.com/peerzadarabet1807/frostguard-scab) · [demo](https://peerzadarabet1807.github.io/frostguard-scab/) | Apple scab and spring-frost early warning for Kashmir orchards. Revised Mills infection periods on live Open-Meteo weather, plus a YOLO11n lesion detector on ONNX Runtime behind FastAPI and React. | Finds six infection periods when replaying Shopian's spring 2024 weather · 175 Python and 19 web tests |
| [Poultry disease detection](https://github.com/peerzadarabet1807/poultry-disease-detection) · [demo](https://peerzadarabet1807.github.io/poultry-disease-detection/) | Classifies photos of chicken droppings as Coccidiosis, Salmonella, Newcastle disease or Healthy. ResNet50 with class activation maps, in the browser or through a FastAPI backend. | 96.7% on internal held-out photos, 79.5% on 1,201 PCR-confirmed photos, reported side by side |
| [Claim denial analysis](https://github.com/peerzadarabet1807/gabeo-ai-healthcare-assessment-peerzada) | Healthcare revenue-cycle pipeline over EDI 835 and 837 data. Deterministic rules establish the facts of each denial, Claude recommends an appeal strategy, and clustering ranks batches by likely recovery. | Similar-claim matching with weighted cosine similarity, no embedding API needed |

🎓 B.Tech in Agricultural and Food Engineering, IIT Kharagpur

## How I work

My ML projects ship with a model card, a limitations section, CI and a live demo. I test the parts that break quietly: the saffron and poultry apps have parity tests proving the Python and in-browser preprocessing produce the same input, and FrostGuard pins every Mills threshold with a test.

One result that changed how I build: because it always has to pick one of its four classes, the poultry model gave a confident verdict on 8 of 12 photos that weren't poultry droppings at all. I treat benchmarks the same way. FrostGuard's detector misses its 15 ms CPU target at 640 px (59.6 ms) and meets it at 320 px (13.5 ms), and the README shows both.

## Tech stack

**AI and LLMs**
![Claude](https://img.shields.io/badge/Claude%20API-%23D97757.svg?style=for-the-badge&logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-%23000000.svg?style=for-the-badge&logo=ollama&logoColor=white)

**ML and computer vision**
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO11-%23111F68.svg?style=for-the-badge&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-%23005CED.svg?style=for-the-badge&logo=onnx&logoColor=white)

**Backend and frontend**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-%23009688.svg?style=for-the-badge&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)

**Cloud and DevOps**
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/github%20pages-%23121013.svg?style=for-the-badge&logo=github&logoColor=white)
![Render](https://img.shields.io/badge/Render-%2346E3B7.svg?style=for-the-badge&logo=render&logoColor=black)
![Colab](https://img.shields.io/badge/Colab-%23F9AB00.svg?style=for-the-badge&logo=googlecolab&logoColor=white)

## GitHub stats

![](https://github-readme-stats.vercel.app/api?username=peerzadarabet1807&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=peerzadarabet1807&theme=tokyonight&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=peerzadarabet1807&theme=tokyonight&hide_border=false&layout=compact)
