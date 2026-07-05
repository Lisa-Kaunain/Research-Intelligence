# Dataset

This project uses the **CShorten/ML-ArXiv-Papers** dataset from Hugging Face.

- Source: https://huggingface.co/datasets/CShorten/ML-ArXiv-Papers
- Contains: Titles and abstracts of Machine Learning research papers from ArXiv
- Loaded directly in the notebook via:

```python
from datasets import load_dataset
dataset = load_dataset("CShorten/ML-ArXiv-Papers", split='train')
```

No dataset files are stored in this repository. The dataset is downloaded automatically the first time the notebook runs, so no manual download is needed.
