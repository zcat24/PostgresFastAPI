Creamos un ambiente virtual con el comando pipenv install.
Para activar el ambiente virtual del proyecto utilizamos el comando pipenv shell
Para correr un comando dentro del ambiente virtual utilizamos el comando pipenv run
Activamos el ambiente virtual e instalamos uvicorn fastapi con el comando pip install uvicorn fastapi
Despues corremos el comando uvicorn main:app --reload, para probar que si podamos hacer un get
CONFIG ----->
Creamos un .py para la configuracion
Ahora debemos instalar sqlalchemy con el comando pip install SQLAlchemy
E importamos lo siguiente:
    from sqlalchemy import create_engine
    from sqlalchemy.orm import sessionmaker
    from sqlalchemy.ext.declarative import declarative_base

Para crear el requirements.txt utilizo el siguiente comando: pip3 freeze > requirements.txt

Luego creamos el Modelo para eso creamos un archivo llamado model

Luego creamos el Crud




