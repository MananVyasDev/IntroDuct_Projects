# PyTorch ML Project Template

## Project Structure
```
pytorch-ml/
├── data/                # Dataset storage
│   ├── raw/
│   └── processed/
├── models/             # Model definitions
│   ├── base.py
│   └── implementations/
├── notebooks/          # Jupyter notebooks
│   ├── EDA.ipynb
│   └── Training.ipynb
├── src/               # Source code
│   ├── data/
│   │   ├── dataset.py
│   │   └── transforms.py
│   ├── training/
│   │   ├── trainer.py
│   │   └── utils.py
│   └── evaluation/
│       └── metrics.py
├── tests/             # Unit tests
├── configs/           # Configuration files
└── requirements.txt
```

## Dependencies
```
torch>=2.0.0
torchvision>=0.15.0
numpy>=1.24.0
pandas>=2.0.0
scikit-learn>=1.3.0
matplotlib>=3.7.0
jupyter>=1.0.0
pytest>=7.4.0
```

## Features
- PyTorch model templates
- Data preprocessing pipelines
- Training utilities
- Evaluation metrics
- Experiment tracking
- Model serialization
- Testing framework

## Getting Started

1. Create virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # or
   .\venv\Scripts\activate  # Windows
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Prepare your data:
   ```bash
   python src/data/prepare_data.py
   ```

4. Train model:
   ```bash
   python src/training/train.py
   ```
