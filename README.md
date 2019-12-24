# Panela Social

Panela Social é um projeto Open Source que foi insipirado no reddit e busca encontrar soluções sociais subdividido no bairro, no destrito e no estado. Neste projeto foi utilizado Node.js, React e um banco de dados NoSQL mongodb.

## Instalação

### Pre-requisitos

* node
* npm
* mongodb

1. Clone esse repositório

2. Instale as dependecias do servidor
    ```bash
    $ cd server
    $ npm install
    $ cd ..
    ```
3. Instale as dependecias do cliente
    ```bash
    $ cd client
    $ npm install
    $ cd ..
    ```

## Rodando a Penela Social localmente

1. Rode o mongodb localmente
    ```bash
    $ mongo
    ```
2. Coloque o servidor para rodar
    ```bash
    $ cd server
    $ npm start
    ```
3. Em outro terminal, coloque a parte do cliente para rodar
    ```bash
    $ cd client
    $ npm start
    ```
4. visite `http://localhost:3000/` no seu navegador

## Testando a Panela Social

### Servidor

Lembre-se, para funcionar o mongodb tem que necessáriamente estar rodando.
```bash
$ cd server
$ npm test
```

### Cliente
```bash
$ cd client
$ npm test
```
