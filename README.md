# Agenda com Django

## Inicializando o ambiente e instalando os pacotes
```
poetry shell
poetry install
```

## Criando seu usuário admin
```
python manage.py createsuperuser
```

## Inicializando a agenda

```
python manage.py migrate
python manage.py runserver
```
