# TechBairro

Sistema de cadastro de clientes da TechBairro.

(README completo na Aula 26.)

# TechBairro
Sistema desktop de gestão de clientes e pedidos desenvolvido em Python e Tkinter para pequenos comércios e bairros. Destinado a comerciantes locais que precisam de um controle simples, organizado e offline
**Versão atual:** 3.3.1· Histórico de mudanças no [CHANGELOG](CHANGELOG.md)
## Funcionalidades
- Cadastro, consulta, edição e exclusão de clientes e pedidos com validação de campos.
- Persistência de dados local por meio de banco de dados relacional SQLite com consultas parametrizadas.
## Requisitos para execução
| Item | Requisito |
|---|---|
| Sistema operacional | Windows, Linux ou macOS |
| Python | Python 3.10 ou superior (versão testada: Python 3.10+) |
| Tkinter | Incluído na biblioteca padrão do Python|
| Bibliotecas externas | Nenhuma |
| Internet | Não necessária |
## Instalação
1. Na página inicial do repositório no GitHub, clique no botão verde Code e depois em Download ZIP.
2. Extraia o arquivo .zip compactado em uma pasta de sua preferência no computador.
3.  Abra o terminal na pasta extraída e execute o programa
 
## Configuração do banco de dados
O banco de dados (techbairro.db) é gerado automaticamente na raiz do projeto logo na primeira inicialização da aplicação. Ele não é versionado nem enviado para o GitHub (.gitignore) por se tratar de um arquivo de dados locais e dinâmicos, garantindo a privacidade das informações. Para realizar uma cópia de segurança (backup), basta copiar o arquivo techbairro.db para um diretório seguro. (onde fica o banco, quando ele é criado, como saber
qual banco está em uso, por que ele não vem no repositório
e como fazer uma cópia de segurança)
## Como usar
O passo a passo está no [Manual de uso](docs/manual_de_uso.md).
## Estrutura do projeto
- main.py: Arquivo principal responsável por iniciar a interface gráfica da aplicação.

- database.py: Módulo que gerencia a conexão, tabelas e comandos SQL com o banco de dados SQLite.

- CHANGELOG.md: Registro cronológico de todas as versões e atualizações do sistema.

- .gitignore: Arquivo de configuração que oculta arquivos temporários e de banco de dados do Git.

- docs/: Pasta destinada aos documentos de projeto, incluindo o manual do usuário.

- requirements.txt: lista informativa de depedencias da biblioteca padrão
(os arquivos e pastas principais, com uma frase cada)
## Autor
Ryan Martins Costa, Técnico em Desenvolvimento de Sistemas, Senac DF (seu nome, curso e instituição)