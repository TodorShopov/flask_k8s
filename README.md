# flask_k8s
This is a Flask App that runs on Kubernetes

## Installation
### 1. Clone/Fork the git repo and create a virtual environment

on Mac
```
git clone https://github.com/randiltennakoon/flask_k8s.git
cd flask_k8s
pip install virtualenv
virtualenv env
```
### 2. Activate the virtual environment

on Mac
```
source env/bin/activate

OR

. env/bin/activate
```

### 3. Run the application
```
chmod +x build.sh
chmod +x run.sh

./build.sh
./run.sh
```

- Navigate to `localhost:4449` to view the app. You can customize the `app.py` and `templates` as you prefer.



