# challenge-devops 
**In this repository is a Frexco devops challenge.**
--------------------------------------------------------------------
Desafio feito em um Linux Ubuntu 20.0.4 instalado no computador

Primeiramente criei o aplicativo do react em uma pasta chamada /desafio
com o comando:

#npx create-react-app app

#cd /app

#npm start

Depois criei um arquivo chamado Dockerfile, onde iria existir as configurações do docker
Setei algumas configurações necessárias para a construção da imagem ocorrer já com a configuração do NGIX
para fazer o direcionamento para a porta 80.

No terminal do linux executei o comando para criar a imagem:

#docker build -t react .

Logo depois criei o arquivo docker-compose com algumas informações e buildei com o comando:

#docker-compose build

Então para subir o container, rodei o comando:

#docker-compose up

Então, ao abrir o navegador e digitar 127.0.0.1:80, estava rodando a aplicação sem a porta padrão
já direcionando para a porta 80.

Logo depois precisei versionar com git e fazer o pull para o repositório que criei, segui os seguintes comandos:

#git init

#git add .

#ls

#git status

#git branch

#git remote add origin https://github.com/RhuanVL/challenge-devops.git

#git config --global user.email "user@email.com"

#git commit -m "app"

#git push -u origin master

# XD 
