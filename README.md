create env 

```cmd
conda create -p venv python=3.7 -y
```

activate env
```cmd
conda activate wineq
```

created a req file

install the req
```cmd
pip install -r requirements.txt
```

```cmd
git init
```
```cmd
dvc init 
```
```cmd
dvc add data_given/winequality.csv
```
```cmd
git add .
```
```cmd
git commit -m "first commit"
```

tox command -
```cmd
tox
```
for rebuilding -
```cmd
tox -r 
```
pytest command
```cmd
pytest -v
```

setup commands -
```cmd
pip install -e . 
```

build your own package commands- 
```cmd
python setup.py sdist bdist_wheel
```
