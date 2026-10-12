# Site de Vendas

Aplicação de demonstração de vendas com frontend Angular e um backend local simples baseado em JSON Server. O backend incluído neste repositório serve os dados de exemplo de `backend/db.json`; não é a API Java do projeto [Vendas API](https://github.com/murillomtz/vendas-api).

## Tecnologias principais

- TypeScript
- Angular
- HTML e CSS
- Node.js
- JSON Server

## Executar

Em um terminal, inicie o backend:

```bash
cd backend
npm install
npm start
```

O script usa a porta `3001`. Em outro terminal, instale as dependências do frontend e execute:

```bash
npm install
npm start
```

A URL do frontend depende da versão Angular/Ionic deste projeto. Confira `package.json` e as configurações da API antes de iniciar. O servidor de dados é apenas local e baseado em JSON.
