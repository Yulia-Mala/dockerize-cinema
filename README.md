# Tickets & orders API

API on DRF (service for processing ticket orders)

### Installing with GitHub
1. Install PostgresSQL and create db

2. Set your credentials into .env file (you can find .env.sample fole in the project root directory)

3. ``git clone https://github.com/Yulia-Mala/dockerize-cinema.git``, then...

...MacOS:\
``-m venv venv``\
``source venv/bin/activate``\
``pip install -r requirements.txt``


...Windows:\
``pip install virtualenv``\
``virtualenv your-venv-name``\
``your-venv-name\Scripts\activate``\
``pip install -r requirements.txt``

4. ``python manage.py migrate``\
``python manage.py runserver``

### Run with docker
Docker should be installed

``docker-compose build``\
``docker-compose up``

### Access
create user: /api/user/register/\
get access token: /api/user/token/


### Back & front for:
• JWT authentication\
• Managing orders and tickets\
• Creating movies with genres, actors, cinema halls, movie sessions\
• Filtering movies and movie sessions

#### Tou can find docs via this link: /api/doc/swagger/

<img width="1272" alt="image" src="https://user-images.githubusercontent.com/121285272/235371335-d3ce4b73-2436-4f9d-ab46-2feb899b7ec1.png">

