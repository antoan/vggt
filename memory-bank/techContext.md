# Tech Context

* **Primary Language(s):** Python (>= 3.10 required as per `pyproject.toml`)
* **Key Frameworks/Libraries:** NumPy, Pillow, huggingface_hub, einops, safetensors, opencv-python (Core dependencies)
* **Development Environment:** Managed using Poetry.
    *   Setup: Run `poetry install` to install core dependencies into a virtual environment.
    *   Virtual Environment Location: Managed by Poetry (typically in `~/.cache/pypoetry/virtualenvs/`).
    *   Activation: Use `poetry shell` to activate the virtual environment.
* **Build/Deployment Process:** [To be defined - How is the project built and deployed?]
* **External Dependencies:** [To be defined - Any APIs, databases, or other external services?]
* **Technical Constraints:** Requires Python 3.10 or higher. Installation of optional 'demo' dependencies might require troubleshooting due to version conflicts (e.g., with `viser`, `tyro`).
