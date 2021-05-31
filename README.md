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

### 1. Criar o tópico msg-cli com 2 partições e 1 réplica
-- foi criado  um tópico chamado 'msg-cli' com 2 partições e 1 réplica 

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/1.png)

### 2. Descrever o tópico msg-cli
-- Possível analisar informações referente o tópico criado

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/2.png)

### 3. Criar o consumidor do grupo app-cli (CONSUMIDOR 1)
-- Criado o Primeiro consumidor e inserido no grupo APP-CLI

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/3.png)

### 4. Enviar as seguintes mensagens do produtor > msg1 msg2
--Utilizando um producer para enviar ás mensagens : msg1 e msg2 para o tópico 'msg-cli'

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/4.png)

### 5. Criar outro consumidor do grupo app-cli - (CONSUMIDOR 2)
-- Foi criado o Segundo consumidor e inserido no grupo APP-CLI

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/5.png)

### 6. Enviar as seguintes mensagens do produtor > msg4 msg5 msg6 msg7
-- Utilizando um producer para enviar ás mensagens : msg4 e msg5 msg6 msg7 para o tópico 'msg-cli'

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/6.png)

### 7. Criar outro consumidor do grupo app2-cli
-- Criando um novo consumidor e inserindo no novo grupo chamado APP2-CLI

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/7.png)

### 8. Enviar novaas seguintes mensagens do produtor
-- Enviando novas mensagens do produtor

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/8.png)

### APP CLI
-- Verificando os dados chegando no (PRIMEIRO CONSUMIDOR) do grupo APP-CLI

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/appcli.png)

-- Verificando os dados chegando no (SEGUNDO CONSUMIDOR) do grupo APP-CLI

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/appcli_b.png)

### APP2 CLI 2
-- Verificando os dados chegando no consumidor do grupo APP2-CLI

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/appcli2.png)

#### OBS: Foi possível notar que os 2 consumidores que estão no mesmo grupo APP-CLI, a mensagem recebida intercala entre os 2,
#### já no consumidor que está no APP2-CLI os dados chegam completos

### 9. Parar o app-cli

CTRL + C

### 10. Definir o deslocamento para -2 offsets do app-cli

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/10.png)

### 11. Descrever grupo

![alt text](https://github.com/GumaFernando/Kafka_Atividade_semantix/blob/main/11.png)


