# borse

## Install how-to

### You will need to have Python3 installed
sudo apt install python3-pip  

# install virtualenv
sudo pip3 install virtualenv

# initialize virtualenv
virtualenv venv

# activate virtualenv
. venv/bin/activate

# install python dependencies
pip3 install -r requirements.txt

# initialize db
python3 manage.py migrate

# create admin user
python3 manage.py createsuperuser

# run development server
python3 manage.py runserver
