<p align="center">
  <img src="https://github.com/scillapinheiro/gama_academy_desafio-1/blob/main/logo-gama-academy.png" width="50%">
</p>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-executando-o-projeto">Executando o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-professor(a)">Professor(a)</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="Grama XP 39" src="https://img.shields.io/static/v1?label=xp&message=39&color=success&labelColor=grey">
  
  <img alt="Stack Hacker" src="https://img.shields.io/static/v1?label=stack&message=hacker&color=success&labelColor=grey">
  
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=success&labelColor=grey">
</p>

## :computer: Projeto
Aplicação simples para criação e alteração de usuários.

## :rocket: Tecnologias
Esse projeto foi desenvolvido com as seguintes tecnologias:

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

## :arrow_forward: Executando o projeto
No terminal inicie o projeto digitando:
```
$ node dist/index.js
```
Quando confirmado que a aplicação está rodando, abra a url ``http://localhost:5000/`` ou ``http://127.0.0.1:5000/`` no navegador. Para fazer criar um usuário, digite ``criar-atualizar-usuario?id=numero&nome=nome`` no final da url.

Exemplo:
```
http://localhost:5000/criar-atualizar-usuario?id=123&nome=erik
```
Para atualizar um usuário já criado, repita o mesmo processo, mas inluindo ou alterando o dado novo. Exemplo:
```
http://localhost:5000/criar-atualizar-usuario?id=123&nome=erik-borges
```
Em todas as ações, será impresso no navegador a confirmação da execução.

## :green_heart: Professor(a)
Érik Borges
| :---: |

## :memo: Licença
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
