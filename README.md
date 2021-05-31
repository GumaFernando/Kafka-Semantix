# Atividade realizada no Bootcamp de engenharia de dados oferecido pela empresa Semantix

  No módulo de Kafka Básico, foi proposta uma atividade para desenvolvermos,
para o entendimento do funcionamento do Apache Kafka, utilizando a Confluent.
  O Apache Kafka é uma  plataforma de streaming distribuída  e escalável Open Source, que através dessa plataforma
é capaz de publicar dados para qualquer número de sistemas ou aplicativos em tempo real, sendo possível ingerir trilhões de eventos por dia
em alta velocidade.

  Foi utilizada para elaboração desta atividade a plataforma Docker, onde foi disponibilizado
um arquivo docker-compose e com isso foi possível fazer a utilização dos serviços necessários.

## Desenvolvimento 

Serviços em execução utilizando o Docker

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/docker.PNG)

1. Criar o tópico msg-cli com 2 partições e 1 réplica
  criação de um tópico chamado 'msg-cli' com 2 partições e 1 réplica

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/1.png)

2. Descrever o tópico msg-cli

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/2.png)

3. Criar o consumidor do grupo app-cli

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/3.png)

4. Enviar as seguintes mensagens do produtor > msg1 msg2

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/4.png)

5. Criar outro consumidor do grupo app-cli

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/5.png)

6. Enviar as seguintes mensagens do produtor > msg4 msg5 msg6 msg7

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/6.png)

7. Criar outro consumidor do grupo app2-cli

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/7.png)


8. Enviar as seguintes mensagens do produtor

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/8.png)

APP CLI

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/appcli.png)

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/appcli_b.png)

APP CLI 2

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/appcli2.png)

9. Parar o app-cli

CTRL + C

10. Definir o deslocamento para -2 offsets do app-cli

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/10.png)

11. Descrever grupo

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/11.png)


