# Setup

## DB
- Inicializar o postgres utilizando o [docker-compose](postgres/docker-compose.yml)


## MQ
- Inicializar o rabbitMQ utilzando o [docker-compose](rabbitMQ/docker-compose.yml)
- Acessar o console de administração do rabbit [console](http://127.0.0.1:15672/) user:guest pass:guest
- Menu Overview -> Import definitions
- Selecionar o arquivo [rabbitMQ/rabbit_gisa_2023-3-23.json](rabbitMQ/rabbit_gisa_2023-3-23.json)
- Clicar em Upload broker definitions

## Postman
- Clicar em Import 
- Selecionar o arquivo [postman/GISA.postman_collection.json](postman/GISA.postman_collection.json)
- Clicar em Import novamente
- Selecionar o arquivo [postman/Local.postman_environment.json](postman/Local.postman_environment.json)

## Aplicações
- Inicializar o [gisa-info-cadastro](https://github.com/puc-gisa/gisa-info-cadastro)
- Inicializar o [integracao-boa-saude](https://github.com/puc-gisa/integracao-boa-saude)

## Teste
- Utilizar os endpoints configurados no postman
