# Tickets & orders API

API on DRF (service for processing ticket orders)

### Installing with GitHub
Install PostgresSQL and create db

git clone https://github.com/Yulia-Mala/dockerize-cinema.git\
cd cinema API python -m venv venv\
source venv/bin/activate\
pip install -r requirements.txt

#### set your credentials into venv variables: 

set DB_ HOST=...\
set DB NAME=...\
set DB_USER=...\
set DB PASSWORD=...\
set SECRET KEY=...

python manage.py migrate\
python manage.py runserver

### Run with docker
Docker should be installed

docker-compose build\
docker-compose up

### Access
create user: /api/user/register/\
get access token: /api/user/token/


### Back & front for:
• JWT authentication\
• Managing orders and tickets\
• Creating movies with genres, actors, cinema halls, movie sessions\
• Filtering movies and movie sessions

#### Documentation is located at /api/doc/swagger/
