# Bem vindo ao desafio DevOps da Engineering do Brasil.

Neste desafio queremos validar seus conhecimentos em Docker, redes e sysadmim, para tanto temos uma app em Python3 é um simples Hello World e queremos usar um API Gateway com uma rota apontando para este app.
0. Faça um fork desse projeto, commit todas suas mudanças e nos envie o link do seu fork, para avaliação.
1. O app em python e um flask que ao receber uma request na porta 5000 responde com um hello world
2. Gere uma imagem Docker com o  app funcionando
3. O API Gateway desse desafio é o [Kong API Gateway](https://docs.konghq.com "link title") __https://docs.konghq.com__ 
4. Faça o deploy do Kong API Gateway 
5. Configure uma rota no Kong API Gateway para quando fizermos uma request com o path /desafio, a requisição seja enviada ao app python

## Entregáveis:
Como entregáveis esperamos um arquivo Dockerfile, um arquivo para subir os containers (docker-compose, docker-stack, deployment k8s), um script (python ou shell) com as chamadas para a criação de uma API e um README.md explicando como tudo isso funciona.

## Você ganha pontos extras se:
Se fizer um script que automatize todo esse processo ou faça alguma mudança no app.
