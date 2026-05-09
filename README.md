🎵 Sistema de Gerenciamento de Músicas em Python

Projeto desenvolvido em Python como atividade acadêmica do 1º semestre de Ciência da Computação, com foco em lógica de programação, manipulação de arquivos .txt, menus interativos e gerenciamento de usuários e playlists.

📌 Sobre o Projeto

O sistema simula uma aplicação de músicas no terminal, permitindo que usuários realizem login, pesquisem músicas, curtam/descurtam faixas e gerenciem playlists personalizadas.

Todos os dados são armazenados utilizando arquivos .txt, sem utilização de banco de dados, com o objetivo de praticar:

Manipulação de arquivos
Estruturas de repetição
Funções
Listas
Organização de menus
Lógica de programação
Estruturação de projetos
🚀 Funcionalidades
👤 Usuários
Cadastro de novos usuários
Sistema de login
Validação de senha
🔍 Busca de músicas
Buscar músicas pelo nome
Buscar músicas pelo artista
Histórico de músicas pesquisadas
❤️ Curtidas
Curtir músicas
Descurtir músicas
Histórico de músicas curtidas
Histórico de músicas descurtidas
🎶 Playlists
Criar playlists
Editar playlists
Adicionar músicas
Remover músicas
Excluir playlists
🛠️ Tecnologias Utilizadas
Python
Manipulação de arquivos .txt
Biblioteca os
📂 Estrutura do Projeto
projeto/
│
├── projeto.py
├── musicas.txt
├── usuarios.txt
├── artista.txt
│
├── usuario_musicas_buscadas.txt
├── usuario_musicas_curtidas.txt
├── usuario_musicas_descurtidas.txt
│
└── playlists/
▶️ Como Executar
1. Clone o repositório
git clone https://github.com/seuusuario/seuprojeto.git
2. Acesse a pasta do projeto
cd seuprojeto
3. Execute o programa
python projeto.py
📖 Exemplo de Funcionalidades

O sistema possui músicas previamente cadastradas como:

Kid Abelha
Skank
Rita Lee
Djavan
Vanessa da Mata
Natiruts

As músicas são armazenadas em arquivos .txt para consulta e gerenciamento.

📚 Conceitos Trabalhados

Durante o desenvolvimento foram aplicados conceitos como:

Funções em Python
Menus dinâmicos
CRUD básico
Manipulação de arquivos
Tratamento de entradas
Organização modular do código
Persistência de dados sem banco de dados

🔒 Segurança

Para evitar exposição de dados no login, o sistema não informa se o erro ocorreu no usuário ou na senha, exibindo apenas uma mensagem genérica de falha na autenticação.

👨‍💻 Autor

Luciano Ventura Monegatto
Estudante de Ciência da Computação

📌 Melhorias Futuras
Interface gráfica
Integração com banco de dados
Sistema de recomendação
Reprodução de músicas
Criptografia de senhas
API de músicas
Versão web
