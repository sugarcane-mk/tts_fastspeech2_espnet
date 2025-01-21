# Training and Fine-Tuning Tamil TTS with FastSpeech2 in ESPnet

## 1. Install ESPnet
Clone the ESPnet repository and navigate to the `tools` directory:
```bash
git clone https://github.com/espnet/espnet
cd espnet/tools
```
### Setup python environment

You can set up the Python environment using one of the following methods:
- Option 1: Using setup_venv.sh
```
./setup_venv.sh $(command -v python3)
```
- Option 2: Using setup_python.sh
```
./setup_python.sh $(command -v python3)
```
### Build ESPnet

Install all required tools by running:
```
make
```
### Verify Installation

Ensure that your current directory is ../espnet/tools. Then, run the following command to check the installation:
```
bash -c ". ./activate_python.sh; . ./extra_path.sh; python3 check_install.py"
```
## 2. Setup or create from existing recipe

