# Quiz da Unidade de Teleoperação

Quiz público com 40 questões, sem cronômetro, com aprovação mínima de 70%.

## Rodar localmente

1. Instale Node.js 18+.
2. Abra um terminal nesta pasta.
3. Execute `npm install`.
4. Defina a senha administrativa:
   - Windows PowerShell: `$env:ADMIN_PASSWORD="uma-senha-forte"`
   - Linux/macOS: `export ADMIN_PASSWORD="uma-senha-forte"`
5. Execute `npm start`.
6. Acesse `http://localhost:3000`.

## Publicar

Publique este projeto em uma hospedagem que aceite Node.js. Configure a variável de ambiente `ADMIN_PASSWORD` na hospedagem e use o comando `npm start`.

A prova pública fica na raiz (`/`) e o painel administrativo em `/admin`.

## Observação de segurança

O gabarito fica somente em `server.js`; o navegador recebe perguntas e alternativas, mas não recebe as respostas corretas.
