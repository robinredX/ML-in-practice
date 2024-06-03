# ML-in-practice

Contains the guided notebooks for each session.

## Lab
Go to [https://learn.baiome.org/](https://learn.baiome.org/) and login with your credentials.

## Cloning this repository

```bash
git clone https://github.com/robinredX/ML-in-practice
```
## Prepare the Python environment
We need Pytorch and Pytorch Geometric for day 3. Please install the requirements:
```bash
cd ML-in-practice
pip install -r requirements.txt
```


## Getting the data
Data is available in the shared folder. Before using, please copy the data to your local copy of this repository.

```bash
cd ML-in-practice
cp -r /home/shared/pub/MLint/data .
```
## Keep local changes
If you are not in ML-in-practice folder, navigate to it
```bash
cd ML-in-practice # Or your local path to ML-in-pratice
```
Stash your local changes, pull from current version of the main branch and merge your local changes:

```bash
git stash
git pull
git stash pop
```

## Further reading
- [Variational autoencoder](https://www.youtube.com/watch?v=rZufA635dq4)
- [GPT from scratch by Andrey Karpathy](https://www.youtube.com/watch?v=kCc8FmEb1nY), his other videos are also extremely informative
- [Geometric deep learning resources](https://geometricdeeplearning.com/)
- [Google tuning playbook](https://github.com/google-research/tuning_playbook)
- [Benchmarking spatial clustering methods with spatially resolved transcriptomics data](https://www.nature.com/articles/s41592-024-02215-8)
- [Learning Graph Cellular Automata](https://proceedings.neurips.cc//paper/2021/hash/af87f7cdcda223c41c3f3ef05a3aaeea-Abstract.html)
- [Single Cells Are Spatial Tokens - Transformers for Spatial Transcriptomic Data Imputation](http://arxiv.org/abs/2302.03038)
- [On the Scalability of GNNs for Molecular Graphs](http://arxiv.org/abs/2404.11568)
