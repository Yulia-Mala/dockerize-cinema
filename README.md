# Tickets & orders API

API on DRF (service for processing ticket orders)

### Installing with GitHub
Install PostgresSQL and create db

git clone https://github.com/Yulia-Mala/dockerize-cinema.git

...MacOS:\
-m venv venv\
source venv/bin/activate\
pip install -r requirements.txt


...Windows:\
pip install virtualenv\
virtualenv your-venv-name\
your-venv-name\Scripts\activate\
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

<img width="1272" alt="image" src="https://user-images.githubusercontent.com/121285272/235371335-d3ce4b73-2436-4f9d-ab46-2feb899b7ec1.png">

