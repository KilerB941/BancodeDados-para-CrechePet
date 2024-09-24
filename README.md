🐾 Sistema de Gestão para Creche de Animais
Este projeto visa criar um sistema simples e eficiente para ajudar autônomos no gerenciamento de creches de animais. Utilizamos React para o front-end e PostgreSQL para o banco de dados, permitindo o registro e controle de informações sobre os animais, como dieta, medicação, alergias e histórico de cuidados.

📋 Visão Geral
O sistema foi desenvolvido para ajudar profissionais como Helen Costa de Lima, uma autônoma que cuida de animais e precisava de uma solução para armazenar dados importantes de maneira organizada e acessível.

🚀 Funcionalidades
Registro de clientes (donos dos animais)
Cadastro de animais com informações detalhadas (dieta, medicação, etc.)
Histórico de cuidados para cada animal
Busca rápida por animal ou cliente
Interface amigável e fácil de usar
🛠️ Tecnologias Utilizadas
React: Front-end dinâmico e interativo
PostgreSQL: Banco de dados para armazenar informações dos animais e clientes
Node.js / Express: Back-end para gerenciar a comunicação entre o front-end e o banco de dados
CSS: Para o design da interface
📦 Instalação
Siga as etapas abaixo para configurar e executar o projeto localmente:

1. Clone o repositório
bash
Copiar código
git clone https://github.com/seu-usuario/sistema-gestao-creche-animais.git
2. Instale as dependências
No diretório do projeto, execute:

bash
Copiar código
cd sistema-gestao-creche-animais
npm install
3. Configure o Banco de Dados
Certifique-se de ter o PostgreSQL instalado e configurado em sua máquina.

Crie um banco de dados chamado creche_animais.
Edite o arquivo .env para incluir as configurações do banco de dados:
makefile
Copiar código
DB_HOST=localhost
DB_USER=seu-usuario
DB_PASSWORD=sua-senha
DB_NAME=creche_animais
DB_PORT=5432
4. Execute o servidor
Para rodar o servidor backend (Node.js), execute:

bash
Copiar código
npm run server
5. Inicie o front-end
Em um novo terminal, execute o seguinte comando para iniciar o front-end (React):

bash
Copiar código
npm start
O sistema estará disponível em: http://localhost:3000

📖 Como Usar
Acesse a interface através do navegador em http://localhost:3000.
Cadastre novos clientes e animais usando os formulários disponíveis.
Acesse informações sobre dietas, medicações e histórico de cuidados dos animais rapidamente através da interface.
🤝 Contribuindo
Contribuições são sempre bem-vindas! Se você deseja melhorar este projeto ou adicionar novas funcionalidades, siga estas etapas:

Faça um fork do projeto.
Crie uma nova branch: git checkout -b minha-nova-funcionalidade.
Faça as suas alterações e commit: git commit -m 'Adiciona nova funcionalidade'.
Envie para a branch original: git push origin minha-nova-funcionalidade.
Abra um pull request.
🐛 Problemas e Sugestões
Se você encontrar problemas ou tiver sugestões, sinta-se à vontade para abrir uma issue.

📄 Licença
Este projeto está licenciado sob a MIT License. Consulte o arquivo LICENSE para obter mais detalhes.

