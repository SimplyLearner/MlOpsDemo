```python
conda create -n mlops-demo python=3.7 -y
conda activate mlops-demo
pip install dvc
git init
dvc init
dvc repro
```