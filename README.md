# Setup

## DB
- Inicializar o postgres utilizando o [docker-compose](postgres/docker-compose.yml)


## MQ
- Inicializar o rabbotMQ utilzando o [docker-compose](rabbitMQ/docker-compose.yml)
- Acessar o console de administração do rabbit [console](http://127.0.0.1:15672/) user:guest pass:guest
- Menu Overview -> Import definitions
- Selecionar o arquivo [rabbitMQ/rabbit_gisa_2023-3-23.json](rabbitMQ/rabbit_gisa_2023-3-23.json)
- Clicar em Upload broker definitions



