# JARVIS 2.0 🤖

JARVIS 2.0 is a personal AI assistant designed to run locally on my PC using LM Studio.

The long-term goal is to create an AI that can interact with both the digital and physical world. The project will eventually connect the AI to PC controls, computer vision, sensors and a robotic arm.

## Current Features

* Runs locally through LM Studio
* Uses an OpenAI-compatible local API
* Maintains conversation history
* Command-line interface
* Designed to be expanded with hardware controls

## Planned Features

* 🦾 Robotic arm control
* 👁️ Computer vision
* 🎙️ Voice input
* 🔊 Voice output
* 🖥️ PC automation
* 🌡️ Hardware sensors
* 🧠 Persistent memory

## Requirements

* Python 3
* LM Studio
* A locally installed AI model
* `openai` Python package

## Setup

Install the required package:

```bash
pip install -r requirements.txt
```

Open LM Studio, load an AI model and start the local server.

The default API address is:

```text
http://localhost:1234/v1
```

Then open `jarvis.py` and replace:

```python
MODEL = "YOUR_MODEL_NAME"
```

with the model identifier used by your LM Studio server.

Run:

```bash
python jarvis.py
```

JARVIS 2.0 should then be ready to use.

## Project Goal

This is the beginning of a larger hardware and software project. The eventual goal is for JARVIS 2.0 to be able to understand commands, control my computer and physically interact with objects using a custom robotic arm.
