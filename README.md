# Sistema de IOT pré pronto

Componentes do sistema:
- Node red
- broker mqtt
- Home assistant
- banco de dados

Como preparar, primeiro crie um arquivo `.env` com esse modelo:
```
MQTT_USR="user"
MQTT_PASS="pass"
DB_USR="user"
DB_PASS="pass"
DB_NAME="name"
```

edite os dados para maior segurança, após isso execute:

``` bash
docker-compose up -d
```

e pronto, seu sistema de IOT será incializado com sucesso.
