python3.12 -m venv venv
. venv/bin/activate
pip install -r requirements.txt

git submodule update --init --recursive
pip install -e ./exo

exo
