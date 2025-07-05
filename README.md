Multimodal Biometric Recognition using Vision Transformers

This project implements a lightweight dual-stream ViT model to fuse iris and finger vein modalities using both score-level and feature-level fusion for secure biometric recognition.

## 📊 Results

| Fusion Method       | Accuracy | F1-Score |
|---------------------|----------|----------|
| Score-Level Fusion  | 89.5%    | 87.1%    |
| Feature-Level Fusion| 98.8%    | 98.9%    |
| Final Output Fusion | 99.5%    | 99.4%    |

## 📁 Structure

- `notebook/`: Colab notebook with full training, evaluation, and plots.
- `models/`: Saved PyTorch model.
- `outputs/`: CSV files of evaluation metrics.
- `requirements.txt`: Dependencies.

## 🚀 How to Run

```bash
pip install -r requirements.txt
