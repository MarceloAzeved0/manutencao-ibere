Passos para executar o projeto
-----------------------------------

### MySQL no Docker

1. Possuir Docker e Docker-Compose instalados no ambiente
2. Certificar que a porta 3307 está liberada
    2.1 Executar o comando ``` netstat -a ``` para verificar portas em uso
3. Executar o comando ``` $ docker-compose up iberedb```
4. O Banco de dados deve estar executando na porta 3307 pronto para configuração

### Instalando/Atualizando Dependências

1. Executar o commando ``` $ npm install ```
2. As dependencias do projeto estarão atualizadas

### Configurando o Banco para desenvolvimento

1. Criar um banco de dados chamado **ibere**
2. Instalar o Sequelize ``` $ npm install --save sequelize```
3. Executar o comando ``` $  npx sequelize-cli db:migrate ```
4. Executar o comando ``` $  npx sequelize-cli db:seed:all ```
5. O banco de dados vai ser configurado conforme a pasta database do projeto

### Criação de novas Tabelas e Models

1.  Utilizar o [Sequelize-cli](https://github.com/sequelize/cli)

### Execução do ambiente de desenvolvimento em docker

1. Executar o commando ``` $ docker-compose up api ```

