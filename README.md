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

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

onliner updates for readme
git add . && git commit -m "update Readme.md" 

git remote add origin https://github.com/sharmaruchikht/simple-dvc-demo.git
git branch -M main
git push origin main