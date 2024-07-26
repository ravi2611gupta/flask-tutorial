py -m venv .venv
source .venv/bin/activate
pip install flask
pip install flask_restful
pip install flask_sqlalchemy
pip freeze > requirements.txt
touch .gitignore


deactivate (to deactivate the server)
pip install -r requirements.txt (to download the packages that are listed in requirements.txt file)
py api.py (to run the code on localhost)