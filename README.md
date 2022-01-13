# WordPress 
WordPress é um sistema livre e aberto de gestão de conteúdo para internet, baseado em PHP com banco de dados MySQL.

Nesse `compose` (docker-compose.yml), pode ter acesso aos arquivos no WordPress através da pasta `wp` do projeto e configurar as variavés como desejar.

## Executar
```terminal
UID=${UID} GID=${GID} docker-compose up -d --build
```