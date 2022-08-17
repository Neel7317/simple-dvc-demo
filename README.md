```bash
create env
```
```bash
activate env
```
```bash
create requirements.txt
```
install the requiremts
```bash
'''pip install -r requirements.txt'''
```

download data from kaggle winequality...

https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

```bash
git init
```
```bash
dvc init
```
```bash
dvc add data...
```
```bash
git add .
```
```bash
git commit -m "first commit"
#for one line
git add . && git commit -m "update README.md"
 ```
```bash
git add .
```
```bash
git commit -m "update README.md"
```
```bash
git remote add origin https://github.com/Neel7317/simple-dvc-demo.git
```
```bash
git branch -M main
```
```bash
git push -u origin main
```
tox command
```bash
tox
```
for rebuilding
```bash
tox -r
```

pytest command
```bash
pytest -v
```

setup command -
```bash
pip install -e .
```
```
create an artifcats folder

mlflow server commands::
mlflow server \
    --backend-store-uri sqlite:///mlflow.db \
    --default-artifact-root ./artifacts \
    --host 0.0.0.0 -p 1234

```