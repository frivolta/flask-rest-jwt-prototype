# Testing jwt rest authorization
source env/bin/activate

pip install -r requirements.txt

from app import db
db.create_all()

python app.py
