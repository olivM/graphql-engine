# Multiplayer Tic Tac Toe

This is a multiplayer tic tac toe app that uses the following components:

- Frontend
  - React
  - Apollo
- Backend
  - Hasura for GraphQL CRUD over database
  - Custom GraphQL Server with ApolloServer for custom logic

## Docker deployment

To deploy all the services run the app using docker:

```sh
docker-compose up -d --build
```

You can access your app at http://localhost:3030
