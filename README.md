# strapi-cognito-auth

Validação do Amplify Access Token JWT no Strapi através do Cognito

- Alterar content type para role Autenticated com as permissões adequadas
- adicionar o arquivo permissions.js na pasta extensions/user-permissions/config/policies/

passar o Access Token do amplify
await Auth.currentSession().accessToken.jwtToken como Bearer nas requisições



