# Curso Be Mean - Conceitos e Exercícios Resolvidos

## 01. MongoDB

### Introdução ao MongoDB
* É um banco de dados NoSQL (Não Relacional)
* Orientado a documentos
* Aceita javascript no console :)
* Sem Schema pré-definido, Schema dinâmico
* Utiliza JSON/BSON
* Além de Sharding, GridFS, Geolocation (Posteriormente escrevo sobre)
* Site Oficial para mais informações <https://www.mongodb.org/>

### Aula 01 - Tópicos
* Para iniciar o serviço, executamos o comando: **mongod** no terminal. Caso dê erro na pasta **data/db**, criar a pasta no diretório **C:/** caso esteja no ruindows, caso esteja no linux: 
    *  **sudo mkdir /data** 
    *  **sudo mkdir /data/db** 
    *  **sudo chmod 777 -Rf /data**
* Para usar o client, executamos o comando no terminal: **mongo**
* Mongo-hacker para customizar nossa CLI(Command Line Interface) do mongoDB: https://github.com/TylerBrock/mongo-hacker
* Para **exportar** dados de uma coleção, usamos: mongoexport --db nome_do_database --collection nome_da_colecao --out minha_colecao.json
* Para **importar** dados de uma coleção, usamos: mongoimport --db nome_do_database --collection nome_da_colecao --drop --file arquivo_que_voce_quer_importar.json

#### Exercício Aula 01 
* Importar o arquivo restaurantes.json <https://github.com/igorsimoes/be-mean-modulos/blob/master/exercicios/mongodb/restaurantes.json> 
* Contar a quantidade de restaurantes
* Exercício Resolvido: <https://github.com/igorsimoes/be-mean-modulos/blob/master/exercicios/mongodb/class-01-resolved-igorsimoes-Igor-Simoes.md>

### Aula 02
* Utilizando o database ao entrar no mongo, executamos o comando: **mongo nome_database** ou digita apenas **mongo** e no CLI escolhe sua database através do comando **use nome_database**
* 

### Aula 03
### Aula 04
### Aula 05
### Aula 06
