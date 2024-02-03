# Brat package

Update and initialize submodules after cloning
```
git submodule update --init --recursive

python3 -m venv venv

source venv/bin/activate

python3 -m pip install .

python3 -m brat.standalone 8081
```