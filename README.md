# OmniVoice 🌍

Add Intel XPU support for [OmniVoice](https://github.com/k2-fsa/OmniVoice)

# Installation

```shell
conda create -n omni-voice python=3.11 -y
conda activate omni-voice
git clone --depth=1 https://github.com/HSB0y/OmniVoice-IntelXPU.git
cd OmniVoice
pip install -e .
pip install torch==2.8.0 torchvision==0.23.0 torchaudio==2.8.0 --index-url https://download.pytorch.org/whl/xpu
```

