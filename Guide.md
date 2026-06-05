# VibeVoice Realtime 0.5B — Guide

## Clone the repository

```bash
git clone https://github.com/microsoft/VibeVoice.git
cd VibeVoice
```

## Create and activate a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

## Install dependencies

```bash
pip install --upgrade pip
pip install -e .
```

```bash
pip install --upgrade pip setuptools wheel
pip install flash-attn --no-build-isolation
```

## Run the realtime demo

```bash
python demo/vibevoice_realtime_demo.py --model_path microsoft/VibeVoice-Realtime-0.5B
```

## Run inference from a file

```bash
python demo/realtime_model_inference_from_file.py --model_path microsoft/VibeVoice-Realtime-0.5B --txt_path demo/text_examples/1p_vibevoice.txt --speaker_name Carter
```
