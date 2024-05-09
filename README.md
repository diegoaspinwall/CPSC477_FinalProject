# CPSC477_FinalProject

This is a project by Lleyton Emery and Diego Aspinwall for CPSC477 at Yale University. This repo is intended to be submitted alongside the official writeup. The project abstract:

> In this project, we address the natural language processing task of [BioLaySumm](https://biolaysumm.org), which aims to generate layperson-friendly summaries of biomedical research articles. We tried several methods, including extractive and abstractive summarization as well as a combination of the two to generate the best performing summary. Each summary was assessed based on its relevance, readability, and factuality.

For use, please download the .ipynb file corresponding to the model you are interested in training. You must download your own version of the data, located [here](https://www.codabench.org/competitions/1920/), and then paste its directory into the .ipynb file. It is recommended that you run these .ipynb files in Google Colab or at least on a GPU, as training/finetuning is time intensive.

Please note that the following external libraries are required:

- 'openai'
- 'pandas'
- 'tqdm'
- 'torch'
- 'google.colab'
- 'json'
- 'transformers'
- 'pytorch_lightning==1.6.0'
- 'textstat'
- 'numpy'
- 'rouge-score'
- 'bert-score'
- 'summac'
- 're'
- 'nltk'
- 'datasets'
- 'evaluate'
- 'os'
- 'accelerate'

All further instructions can be found in the files themselves. If anything is unclear, reach out to diego.aspinwall@yale.edu or lleyton.emery@yale.edu.
