# Chat TI

Aplicação simples de chat desenvolvida em Node.js, utilizando Socket.IO para funcionalidade de troca de mensagens em tempo real.

Foi desenvolvida como estudo de Node.js e tecnologias relacionadas para aplicações web.

## Como testar

Como pré-requisitos, é necessário instalar o [Node.js](https://nodejs.org/en/download/) na última versão LTS, bem como o [MongoDB](https://www.mongodb.com/), para gravar os dados de usuários no banco de dados.

Com essas aplicações instaladas, abra o terminal ou prompt de comando (dependendo do sistema operacional utilizado) na pasta da aplicação. Em seguida, execute os seguintes comandos, em sequência:

## Obtendo o código
git clone https://github.com/iTPr0/ChatTI.git

No Windows/Mac/Linux:
```
npm install
npm install -g nodemon
```

## Inicie o servidor de bate-papo:
(não esqueça de lançar o Node.JS antes!)
```
npm run start ou node apps.js
```
## Agora abra este URL no seu navegador:
```
http://localhost:3000
```
e pronto. ;)

## Limitações

Como a aplicação foi desenvolvida com o intuito de apresentar as capacidades do Node.JS a novos desenvolvedores, a aplicação possui um escopo bem limitado, contendo apenas o básico para funcionamento do chat.

Algumas bibliotecas são importadas de CDNs diretamente nas views ou foram incluídas manualmente na pasta do projeto. Podem haver bugs de utilização e de segurança, então utilize a aplicação apenas para fins educativos.

Futuramente será desenvolvida uma nova versão corrigindo todos esses problemas utilizando um framework front-end adequado, bem como será adotada uma arquitetura melhor para a aplicação, possivelmente desenvolvida utilizando TDD.

**Você precisa se tornar um administrador antes de entrar.**

Use o comando abaixo.
```
/role [usuário] [0-3]
```
