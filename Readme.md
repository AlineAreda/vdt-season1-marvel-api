# Marvel API

## 🔖 Requisitos funcionais

### Cadastro de Personagens

- [X] Deve poder cadastrar um personagem com as características conforme tabela abaixo:
- [X] Deve retornar o id do personagem ao realizar o cadastro
- [X] Não deve cadastrar personagem com nome duplicado


| campos | descrição                             | tipo     | obrigatório |
| ------ | :------------------------------------ | -------- | ----------- |
| name   | nome do personagem                    | texto    | sim         |
| age    | idade                                 | inteiro  | não         |
| alias  | codinome                              | texto    | sim         |
| team   | afiliações (vingadores, x-men, etc..) | lista    | sim         |
| active | se o personagem está ativo ou não     | booleano | sim         |

### Busca de Personagens

- [X] Deve retornar uma lista de personagens cadastrados
- [X] Deve poder buscar por personagem por nome
- [X] Deve poder buscar personagem pelo id
- [X] Deve retornar 404 ao buscar por id não cadastrado

### Remover Personagem

- [X] Deve poder remover por id, um personagem cadastrado
- [X] Deve retornar não encontrado ao remover por id não cadastrado

## 🚀 Tecnologias

- [Node.js] - plataforma de desenvolvimento
- [Express] - framework onde a API foi construída
- [Cypress] - framework de testes automatizados
- [MongoDB] - Banco de dados (Não relacional)

## 👨🏻‍💻 Como executar o projeto

[Node.js](https://nodejs.org/) v16 ou superior para executar.


### ✨ Instalação e uso da arquitetura
-----------------------
- Instale o [Node.js](https://nodejs.org/en/download/);
- Baixe este repositório ou faça um git clone;
- Abra o diretório do projeto e execute o comando:
    - `npm install`
- Para abrir a interface de execução do Cypress, execute no diretório do projeto:
    - `npx cypress open`
- Para execução via linha de comando
    - `npx cypress run`

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feito com 💜 &nbsp;por Aline Areda 👋 &nbsp;[Meu linkedin](https://www.linkedin.com/in/aline-areda/)
