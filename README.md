TODO

python3 -m build
python3 -m venv test_env
cd test_env
source bin/activate
python3 -m pip install ../dist/doorbell-0.1.0.tar.gz 
bin/doorbell 
deactivate 