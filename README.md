# command-line-cheat-sheet

### CLONE REPO WITH NEW BRANCH, OPEN IN VS CODE
cd C:\Users\Ariel\Google Drive\Work\Blossom Careers\
git clone -b Ariel/FixBugs https://github.com/JasperDaDolphin/kuse-flask-app/
cd kuse-flask-app
code .

### VENV
python -m venv .
\Scripts\activate
pip install -r requirements.txt

### RUN FLASK
set FLASK_APP=C:\Users\Ariel\Google Drive\Work\Blossom Careers\kuse-flask-app\app.py
flask run

### RUN TESTS
cd C:\Users\Ariel\Google Drive\Work\Blossom Careers\kuse-flask-app
set PYTHONPATH=C:\Users\Ariel\Google Drive\Work\Blossom Careers\kuse-flask-app
python -m unittest .

### PUSH TO GIT
git add .
git ls-files
git commit -m "message"
git push

### DOCKER BUILD
docker build -f Dockerfile -t image_name .
docker push image_name
docker pull image_name

### RUN PYTHON IN DOCKER IMAGE
docker run -i -t image_name

