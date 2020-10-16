# Happy

Projeto construído com **Typescript** durante a NLW 3 da Rocketseat.

Happy é um projeto que possibilita aos usuários visualizar os orfanatos próximos a sua localização e assim facilitando a visita.

# Projeto

O projeto se divide em três partes: o backend; o frontend web; e o frontend mobile.

## Backend

Desenvolvido usando as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [SQLite](https://www.sqlite.org/index.html)
- [TypeORM](https://typeorm.io/#/)

## Frontend Web

Desenvolvido usando as seguintes tecnologias:

- [ReactJS](https://pt-br.reactjs.org/)
- [Axios](https://github.com/axios/axios)

## Frontend Mobile

Desenvolvido usando as seguintes tecnologias:

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/)

# Executando Projeto

**Backend**:

Rodando migrations

```cmd
  yarn typeorm migration:run
```

Startando o servidor

```cmd
  yarn dev
```

Se atente à url que estão presentes na imagens, acesse o arquivo de views das images


**Frontend Web**:

Stardando aplicação

```cmd
  yarn start
```

**Frontend Mobile**:

Aconselho usar um dispositivo físico. É importante lembrar que o dispositivo deve ter o app do expo instalado

Startando aplicação

```cmd
  yarn start
``` 

Se atente a url de conexão com o backend, verique o arquivo api.ts na pasta services
