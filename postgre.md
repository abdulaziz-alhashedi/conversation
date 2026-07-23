# how to conect laravel to postgres

now user and database are created
port 5432
host 127.0.0.1
database yourdatabase name
user myuser
password yourpassword

# Grant permissions to user

GRANT CREATE ON SCHEMA public TO myuser;
GRANT USAGE ON SCHEMA public TO myuser;
GRANT ALL PRIVILEGES ON SCHEMA public TO myuser;
