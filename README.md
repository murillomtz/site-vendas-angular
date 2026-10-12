# Site de Vendas Servidor de Dados

Repositório que contém um backend de demonstração com JSON Server e uma coleção de produtos. Apesar do nome fazer referência a Angular, o conteúdo disponível na branch principal não inclui o código de uma interface Angular.

**Categoria:** Backend de demonstração · API simulada.

## Tecnologias principais

- JavaScript
- Node.js
- JSON Server 0.16

## O que está neste repositório

- `backend/db.json`: base JSON que contém a coleção `products`.
- `backend/package.json`: dependência JSON Server e script de inicialização.
- Arquivos de dependências do backend também estão versionados no repositório.

JSON Server transforma a coleção em uma API para listar, consultar, criar, atualizar e excluir registros de produtos. Ele é uma ferramenta de demonstração; o repositório não contém regras de negócio de um backend Java nem um servidor de pagamentos.

## Executar

Entre na pasta correta, pois não há `package.json` na raiz:

```bash
cd backend
npm install
npm start
```

O script inicia JSON Server na porta **3001**. A coleção fica disponível em `http://localhost:3001/products`.

## Situação do frontend

A inspeção da branch principal encontrou apenas os arquivos do servidor de dados. Não foram encontrados fontes Angular, `angular.json`, uma pasta de aplicação frontend ou uma compilação navegável da interface.

Por esse motivo, não foi possível produzir uma captura de um sistema frontend em execução a partir deste repositório. Para recuperar a interface, é necessário localizar o código em outra branch, em outro repositório ou em um backup.

## Relação com outros projetos

Não foi confirmada uma interface correspondente na lista fornecida. Este backend JSON Server não é o backend de `vendas-api-front`, que consome o projeto Java [Vendas API](https://github.com/murillomtz/vendas-api). A semelhança dos nomes não comprova que sejam a mesma aplicação.


## Histórico

Repositório criado no GitHub em **2021-03-24**. Essa data identifica a criação do repositório; não comprova o início nem a conclusão do desenvolvimento.
