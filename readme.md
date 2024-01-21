<h1 align="center" style="margin-top: 0px;">My personal tests for training stable diffusion models</h1>

# Introduction
In this repository I will experiment with different pipelines and workflows for stable diffusion primeraly using the hugging face Diffusors library. Furthermore I will try to train dreambooths and LoRas.


## Hardware
- >16 GB RAM
- GPU with > 8 GB VRAM

## Software
- Python 3.11

# Getting Started
## 1. Clone the repository

```bash
git clone https://github.com/MrWhatZitToYaa/Diffusors.git
cd Diffusors
```

## 2. Install the package

Optional (recommended): Create a virtual environment:

**venv:**

```bash
python3 -m venv diffVenv
source diffVenv/bin/activate
```

Then, install the package via

```bash
pip install -e .
```

# Development

## Setup
To set up the development environment, run the following commands:

```
pip install -e .[dev]
pre-commit install
```

# Citation
If you use ELQM: Energy-Law Query-Master for your research, please cite it using the following

```bibtex
@software{elqm_energy_law_query_master_2023,
    author = {Nikita Tatsch},
    title = {Tests with Stable Diffusion},
    month = jan,
    year = 2024,
    publisher = {GitHub},
    version = {1.0.0},
    url = {https://github.com/MrWhatZitToYaa/Diffusors.git}
}
```