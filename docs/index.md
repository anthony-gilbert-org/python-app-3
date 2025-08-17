
# python-app-3

A lightweight Python application built to demonstrate core features, including setup, execution, and configuration.

##  Features

- Modular Python code structure
- Configurable via environment variables
- Easy to run locally or in containers
- Simple logging for debugging

##  Requirements

- Python 3.9+
- pip (Python package manager)
- (Optional) Docker

##  Installation

Clone the repository:

```bash
git clone https://github.com/anthony-gilbert/python-app-3$.git
cd python-app-3
pip install -r requirements.txt
python main.py
python main.py --config config.yaml
```
Configure
```bash
APP_ENV=development
LOG_LEVEL=INFO
```

##  Docker

Build and run:

```bash
docker build -t python-app-3 .
docker run --rm -it python-app-3
```

You can access the app by accessing this url:
```sh
python-app-3-development.local/app/v1/info
```