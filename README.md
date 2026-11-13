Nome: Lucas tristão herminio    
Turma: 3° NDN

1. Instalar as dependências

Abra o terminal na pasta do projeto e execute:

npm install

2. Configurar o banco de dados

Abra o MySQL Workbench e execute o arquivo schema.sql para criar o banco de dados e a tabela de usuários.

3. Configurar as variáveis de ambiente

Crie um arquivo .env na pasta principal do projeto, utilizando o .env.example como modelo.

Configure os dados de conexão:

PORT=3002
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=SUA_SENHA
DB_DATABASE=dev_db
DB_PORT=3306

Substitua SUA_SENHA pela senha do seu MySQL.

4. Iniciar o servidor

No terminal, execute:

npm run watch

O servidor estará disponível em:

http://localhost:3002