<h1 align="center">Георгий · DevOps / MLOps</h1>

<p align="center">
  <b>Инфраструктура, на которой живут LLM:</b> GPU-сервер как код, деплой с автооткатом, наблюдаемость, оценка качества моделей.<br>
  <sub><i>Infrastructure that LLMs run on: GPU server as code, self-rolling-back deploys, observability, model evaluation.</i></sub>
</p>

<p align="center">
  <a href="https://zhoratolk.github.io/portfolio/"><img src="https://img.shields.io/badge/портфолио-сайт-22c55e?style=for-the-badge&logo=githubpages&logoColor=white" alt="Сайт-портфолио"></a>
  <a href="https://github.com/zhoratolk/portfolio"><img src="https://img.shields.io/badge/кейсы-RU%20%2F%20EN-1e293b?style=for-the-badge&logo=github" alt="Кейсы"></a>
</p>

---

**Сейчас**

- 🖥️ Держу свой GPU-сервер (2× RTX 3060) на Ansible. На нём в продакшене работают три сервиса.
- 🚀 Катч — SaaS нарезки стримов: 2 200+ тестов, pull-деплой с откатом, circuit breaker между LLM-провайдерами.
- 📈 Аналитика досмотров YouTube автоматически меняет параметры нарезки клипов.
- 🐝 [swarm-orchestrator](https://github.com/zhoratolk/swarm-orchestrator) — рой LLM-агентов, который принимает работу только после реальной проверки.
- 📚 Учу сейчас: Kubernetes на практике, Terraform, Prometheus / Grafana.

**Стек, который эксплуатирую сам**

![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![NVIDIA](https://img.shields.io/badge/CUDA_·_NVENC-76B900?logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)

**Избранные кейсы**

| | |
|---|---|
| [Домашний GPU-сервер как код](https://github.com/zhoratolk/portfolio/blob/main/cases/gpu-server.md) | Ansible, аренда GPU между проектами, дедман-свич, постмортемы |
| [Катч — SaaS нарезки стримов](https://github.com/zhoratolk/portfolio/blob/main/cases/katch.md) | CI → ветка `green` → pull-деплой → healthcheck → откат |
| [Shorts-Maker](https://github.com/zhoratolk/portfolio/blob/main/cases/shorts-maker.md) | whisper + диаризация ≈14× реального времени, петля от аналитики |
| [shortmaker-deadman](https://github.com/zhoratolk/shortmaker-deadman) | Внешний сторож на GitHub Actions |

<sub>Санкт-Петербург · удалённо или гибрид · рассматриваю переезд в Алматы</sub>
