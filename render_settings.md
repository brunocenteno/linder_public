Build Command
pip install --upgrade pip && pip install babel==2.9.1 && pip install -r requirements.txt && python setup.py install

Start Command
python odoo-bin --db_host=$DB_HOST --db_port=$DB_PORT --db_user=$DB_USER --db_password=$DB_PASSWORD --database=$DB_NAME --http-port=8069 --http-interface=0.0.0.0