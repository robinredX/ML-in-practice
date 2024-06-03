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
