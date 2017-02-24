# sandbox

sandbox projects and whatnot

---

### microblog

```
git clone https://github.com/mjstealey/sandbox.git
cd sandbox/microblog/
virtualenv flask
source flask/bin/activate
pip install setuptools --upgrade
pip install -r requirements.txt
./db_create.py
./db_upgrade.py
./run.py
```

Runs on: [http://localhost:5000](http://localhost:5000)
