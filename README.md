# AMQP-com-RabbitMQ

Implementação do Protocolo AMQP(Advanced Message Queuing Protocol) utilizando o RabbitMQ.
O RabbitMQ server é uma robusta e escalavel implementacao de um Broker AMQP.

Para o sucesso dos exemplos é preciso que o RabbitMQ Server esteja em execução!

A teoria e o codigo fonte básico foi obtido do proprio site do RabbitMQ:
https://www.rabbitmq.com/

Requisitos
Primeiramente precisamos instalar uma versao da linguagem "Erlang" compativel com seu sistema operacional.
Faça o Download e instale sua Erlang. https://www.erlang.org/downloads

Então fazemos o download do rabbitmq Server.
Com a instalação concluida o RabbitMQ vai estar setado e em execução(configuracao padrão)

OBS:.Caso nao esteja em execução entre na pasta de serviços do sistema e execute o RabbitMQ Service


Por default o Python nao vem com a biblioteca que precisamos para trabalhar o protocolo, logo para executar os codigos precisamos da biblioteca "pika" (sim, por mais que você de risada este é o nome da library srsrs).

Pika é uma implementação em Python do AMQP que inclui extensões RabbitMQ!
Sua documentação pode ser encontrada em: https://pika.readthedocs.io

To install it run

	pip install pika==0.10.0
You may first need to run

	easy_install pip

Após essas etapas estamos aptos a executar os scripts!
