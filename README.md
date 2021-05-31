# Atividade realizada no Bootcamp de engenharia de dados oferecido pela empresa Semantix

  No módulo de Kafka Básico, foi proposta uma atividade para desenvolvermos,
para o entendimento do funcionamento do Apache Kafka, utilizando a Confluent.
  O Apache Kafka é uma  plataforma de streaming distribuída  e escalável Open Source, que através dessa plataforma
é capaz de publicar dados para qualquer número de sistemas ou aplicativos em tempo real, sendo possível ingerir trilhões de eventos por dia
em alta velocidade.

  Foi utilizada para elaboração desta atividade a plataforma Docker, onde foi disponibilizado
um arquivo docker-compose e com isso foi possível fazer a utilização dos serviços necessários.

- Desenvolvimento 

Serviços em execução utilizando o Docker

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/docker.PNG)

1. Criar o tópico msg-cli com 2 partições e 1 réplica

2. Descrever o tópico msg-cli


3. Criar o consumidor do grupo app-cli

4. Enviar as seguintes mensagens do produtor > msg1 msg2

5. Criar outro consumidor do grupo app-cli


6. Enviar as seguintes mensagens do produtor > msg4 msg5 msg6 msg7


7. Criar outro consumidor do grupo app2-cli


8. Enviar as seguintes mensagens do produtor

9. Parar o app-cli

CTRL + C


10. Definir o deslocamento para -2 offsets do app-cli


11. Descrever grupo

12. Iniciar o app-cli
