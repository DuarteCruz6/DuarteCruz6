### Hi, I'm Duarte 👋

I build machine learning systems, mostly in **computer vision**, and I care as much about running them well as about training them.

MSc Autonomous Systems @ **DTU** · BSc CSE @ **IST** (Machine Learning 20/20) · ex-**Cloudflare**, ex-**Nmbrs**

🌐 [duartepcruz.com](https://duartepcruz.com) (most projects have a live in-browser demo) · 💼 [LinkedIn](https://www.linkedin.com/in/duartepcruz/) · 🤗 [Hugging Face](https://huggingface.co/duartepcruz)

---

#### Selected work

| Project | What it is | Result |
|---|---|---|
| [**Forest Guardian**](https://github.com/DuarteCruz6/JunctionX-Lisbon2025-Hackathon) | Segments invasive acacia in satellite imagery with YOLOv8n-seg. Labels built from Portugal's COS2018 land-use map; [model](https://huggingface.co/duartepcruz/forest-guardian-yolov8-seg) and [dataset](https://huggingface.co/datasets/duartepcruz/acacia_dataset) on HF; runs in the browser via ONNX. | 🥇 1st overall, JunctionX Lisbon 2025 · 0.56 box mAP@50 · 0 false alarms on 16 negative tiles |
| [**Portuguese fake-news detection**](https://github.com/DuarteCruz6/pt-fake-news-detection) | Five classifiers on 63k European Portuguese articles, plus LIME, permutation importance and topic clustering to see what they actually learned. [Paper](https://doi.org/10.5281/zenodo.18393436) | 🥈 2nd, NTT Data & Técnico Merit Prize · 0.926 macro-F1 (MLP), within 0.02 of fine-tuned BERT |
| [**Models in the browser**](https://duartepcruz.com/writing/models-in-the-browser/) | Running YOLOv8-seg and an MLP fully client-side, with outputs matched to the originals. | Write-up + live demos |
| [**AR meeting assistant**](https://github.com/DuarteCruz6/Junction2025) | Live captions, running summary and task extraction on Snapchat Spectacles. | Junction 2025, Espoo |

#### Engineering

At Cloudflare I co-designed a gRPC control plane (Go, Kubernetes) for an internal fuzz-testing platform. I also fixed a concurrency race in an AI-agent gateway, which removed about 9.7k errors a week, or 97% of its failures.

#### Stack

**ML:** PyTorch · Ultralytics YOLO · scikit-learn · Hugging Face · ONNX Runtime · LIME  
**Systems:** Python · Go · C++ · TypeScript · Docker · Kubernetes · gRPC · FastAPI · Celery/Redis

📫 Open to CV/ML internships, working-student roles and MSc thesis collaborations in perception: duartepcruze@gmail.com
