# Sky-Drive

Project page for **Sky-Drive: A Distributed Multi-Agent Simulation Platform for Socially-Aware and Human-AI Collaborative Future Transportation**.

Zilin Huang, Zihao Sheng, Zhengyang Wan, Yansong Qu, Yuhao Luo, Boyue Wang, Pei Li, Jiancong Chen, Keke Long, Jiayi Meng, Sikai Chen, Yue Leng

University of Wisconsin-Madison · Purdue University · The University of Texas at Arlington · Google

## About

Sky-Drive is the first comprehensive simulation platform that tightly integrates virtual reality (VR), multi-agent interactions, and human-centered AI approaches for multi-agent traffic simulation and human-centered autonomous agent research. Its key innovations include:

- **Digital twin framework** — high-fidelity virtual replicas of transportation systems for real-time monitoring and optimization.
- **Distributed multi-agent architecture** — synchronized simulation across multiple terminals with precise real-time interactions between autonomous vehicles (AVs), human-driven vehicles (HDVs), and pedestrians.
- **Multi-modal human-in-the-loop framework** — captures rich human behavioral data via steering wheels, eye-tracking cameras, and smartwatch sensors.
- **Foundation model integration** — LLMs and VLMs for enhanced human-machine collaboration and personalized decision-making.
- **Human-AI bi-directional mechanism** — knowledge exchange between human drivers and AI systems through human feedback and transportation-science domain knowledge.
- **Hardware-in-the-loop module** — ROS compatibility for verifying autonomous driving algorithms on physical platforms.

Sky-Drive supports research across VR-enabled VRU–AV interactions, reinforcement-learning-based driving policy learning, customized long-tail scenario generation, and LLM-enabled personalized driving.

## Running the site locally

This is a static website served directly (no build step required, thanks to `.nojekyll`). To preview locally:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Structure

- `index.html` — page content.
- `static/` — CSS, JS, images, videos, and PDFs.
- `_site/` — pre-rendered copy of the site.

## Acknowledgments

This project page is built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), parts of which were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
