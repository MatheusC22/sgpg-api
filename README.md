<h1 align="center">
    SGPG - API <br />
    <img src="https://img.shields.io/github/contributors/sgpg-univem/sgpg-api.svg?style=for-the-badge"/>
    <img src="https://img.shields.io/github/forks/sgpg-univem/sgpg-api.svg?style=for-the-badge"/>
    <img src="https://img.shields.io/github/stars/sgpg-univem/sgpg-api.svg?style=for-the-badge"/>
    <img src="https://img.shields.io/github/issues/sgpg-univem/sgpg-api.svg?style=for-the-badge"/>
    <img src="https://img.shields.io/github/license/sgpg-univem/sgpg-api.svg?style=for-the-badge"/>
</h1>

<h2 id="technologies"> 🛠 Tecnologias </h2>

- [TypeScript](https://www.typescriptlang.org/)
- [Prisma](https://www.prisma.io/)
- [Express](https://expressjs.com/)
- [MySQL](https://www.mysql.com/)

<h2 id="usage" > 👷 Configurando e rodando a API </h2>

```bash
# Clone o repositório
$ git clone https://github.com/sgpg-univem/sgpg-api.git

# Entre na pasta do projeto
$ cd sgpg-api

# Instale as dependências
$ npm install
# ou
$ yarn install
```

<h4>Configurando as variáveis de ambiente</h3>

Crie um arquivo ```.env``` na raíz de seu projeto:

```bash
# URL do banco (substitua os parâmetros)
DATABASE_URL="mysql://USER:PASSWORD@HOST:PORT/DATABASE"
# Porta da API
PORT=5000
```

<h4>Gerando o banco de dados e rodando a API</h4>

```bash
# Migre o banco de dados pelo Prisma
$ npx prisma migrate deploy
# Em caso de dúvidas, leia a documentação:
# https://www.prisma.io/docs/getting-started/quickstart

# Execute a aplicação
$ npm run serve
# ou
$ yarn serve
```

<h2 id="contribution"> 🤝 Contribuidores </h2>

<img src="https://contrib.rocks/image?repo=sgpg-univem/sgpg-api"/>

<h2 id="license"> 📝 Licença </h2>

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para obter mais detalhes.
