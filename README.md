## Como executar o projeto
Para executar o projeto, certifique-se de ter o Node.js instalado e siga as instruções abaixo:

1. Instale as dependências necessárias. No terminal, navegue até o diretório do repositório back-end e execute os seguintes comandos:
   
```bash
npm install
npm install prisma
npm install koa
```
## Configuração do banco de dados e autenticação de e-mail
Para configurar o banco de dados e a autenticação de e-mail, siga estas etapas:

Crie um arquivo .env no diretório do projeto.
Adicione as seguintes linhas ao arquivo .env:
```bash
DATABASE_URL="url-do-seu-banco-de-dados"
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-email-password
```
Ainda no diretório do repositório back-end, execute o seguinte comando para iniciar o servidor. :
```bash
node api/index.js
```
