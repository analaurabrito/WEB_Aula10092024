# Projeto WEB

![image](https://user-images.githubusercontent.com/25181517/183890598-19a0ac2d-e88a-4005-a8df-1ee36782fde1.png)
![image](https://user-images.githubusercontent.com/25181517/183897015-94a058a6-b86e-4e42-a37f-bf92061753e5.png)
![image](https://user-images.githubusercontent.com/25181517/183568594-85e280a7-0d7e-4d1a-9028-c8c2209e073c.png)

_API. CRUD. NODE. AI._ </br>
> Esse repositório foi criado como atividade avaliativa para a disciplina de Programação Avançada WEB, da Universidade de Vila Velha, ministrada pelo professor Otávio Lube. O exercício consiste no desenvolvimento de uma API do tipo CRUD com Typescript, usando React, implementando o Prisma para conexão e migração do Banco de Dados e experimentando a inserção de AI através do GROQ.

> O projeto da API tem o controle dos modelos de usuário, posts e comentários.

## 💻 Lista de comandos

Alguns dos comandos usados para a execução do projeto:

- ``` npm init -y ```
- ``` npm i typescript ```
- ``` npx tsc --init ```
- ``` npm i ts-node ```
- ``` npx tsc ```
- ``` npm install express ```
- ``` npm i --save-dev @types/express ```

## Extensões do VSCode

Algumas das extensões usadas para no desenvolvimento do projeto:

```
{
    "recommendations": [
        "vscode-icons-team.vscode-icons",
        "esbenp.prettier-vscode",
        "prisma.prisma",
        "Prisma.prisma-insider",
        "rangav.vscode-thunder-client"
    ]
}
```

## Ts-node-dev

O ts-node-dev nos ajuda a ter mais produtividade uma vez que ele reinicializar o servidor automaticamente a medida que salvamos o projeto.

- ``` npm i ts-node-dev --save-dev ```

Depois de instalado, basta atualizar o script de execução do projeto para:

```
  "dev": "npx ts-node-dev ./src/server.ts"
```

## Prisma ORM

Para a instalação e utilização do Prisma, segue-se a documentação:

- https://www.prisma.io/docs/getting-started/quickstart

