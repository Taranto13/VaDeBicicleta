# VaDeBicicleta
Projeto proposto para a disciplina de Programação Orientada a Objetos

Como proposto em sala de aula, a aplicação VáDeBicicleta deve permitir o aluguel de bicicletas em totens espalhados pela cidade, gerenciar o cadastro, aluguel e devolução das bicicletas por meio de uma página web e aplicativo mobile.
A aplicação vai lidar com dados de usuários, bicicletas, cobranças e operações de empréstimo.
Terá comunicação entre backend e frontend (Arquitetura distribuída) e armazenamento seguro em um Banco de Dados PostgreSQL hospedado em um servidor Linux (Ubuntu Server 24.0).

Tecnologias Utilizadas:

Linguagem: Python (Orientado a Objetos)
Framework Backend: Flask
Banco de Dados: PostgreSQL (armazenamento seguro e transacional)
ORM: SQLAlchemy (para simplificar o acesso ao banco e facilitar migrações)
Migrações de Banco: Flask-Migrate
Frontend: React (ou Vue.js), para interface do usuário e interação com o backend
API: RESTful para comunicação entre frontend e backend
Autenticação: JWT (JSON Web Tokens) para autenticação de usuários
Segurança: Criptografia de senhas e CORS configurado para segurança das requisições
