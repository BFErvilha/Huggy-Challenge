# Huggy Code Challenge

Desafio técnico Huggy.io

## Setup

Para rodar cada projeto deve-se criar um '.env'' e preencher as respectivas váriaveis de ambientes conforme mostrada na [documentão](https://developers.huggy.io/pt/API/api-v3.html#autenticacao) de como obte-las.

[API Utilizada](https://api.huggy.app/v3)

### Client

Criar .env com as seguintes variaveis:

- VUE_APP_API=
- VUE_APP_HUGGY_CLIENT_ID=
- VUE_APP_HUGGY_CLIENT_SECRET=
- VUE_APP_REDIRECT_URI='url + /auth/callback'

após isso executar os passos de instalação

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

## Server

Criar .env com as seguintes variaveis:

- HUGGY_CLIENT_ID=
- HUGGY_CLIENT_SECRET=
- REDIRECT_URI='url + /auth/callback'

após isso executar os passos de instalação

### Project setup

```
npm install
```

### Run

```
node server.js
```
