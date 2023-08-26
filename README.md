# Guia de Instalação

## Configuração do Ambiente Virtual

### No Windows
```
pip install virtualenv
python -m virtualenv .venv
```

### No Linux
```
pip install virtualenv
python3 -m virtualenv .venv
```

## Entrar no ambiente virtualenv

### Windows

```
.venv\Scripts\activate
```


### Linux

```
source .venv/bin/activate
```

## Instalar as dependências

```
pip install requirements.txt
```

## copia o .env.example e renomeia para .env

## Rode o script secret_key.py

```
python3 secret_key.py
```

## Agora, copie a SECRET_KEY que foi gerada no terminal e coloque no seu arquivo .env

# Agora, você já pode rodar a aplicação

```
python3 manage.py runserver
```
# grace_curso_usp
