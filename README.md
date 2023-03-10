create env
```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

create a req file

install the req
```bash
python -m pip install -r requirements.txt
```

Download the data "winequality.csv"

```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add .
```
```bash
git commit -m "first commit"
```
oneliner updates for readme
```bash
git add . && git commit -m "update Readme.md" 
```
```bash
git remote add origin https://github.com/sharmaruchikht/simple-dvc-demo.git
git branch -M main
git push origin main
```

tox command -
```bash
tox
```

for rebuilding -
```bash
tox -r
```

pytest command -
```bash
pytest -v
```

setup commands -
```bash
pip install -e .
```

build your own package commands -
```bash
python setup.py sdist bdist_wheel
```