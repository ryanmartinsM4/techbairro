Clique em Publish release. Copie o link da página que abrir: ele vai no registro de entrega?
https://github.com/ryanmartinsM4/techbairro/releases





# Entrega final da TechBairro
Aluno(a): ryan martins costa · Versão entregue: 3.3.2
Por que esse número de versão: Porque segue o padrão de versionamento semântico  onde o 3.3.2 representa um incremento de correção/ajuste (patch) em relação às versões anteriores da aplicação.
| # | Item | Evidência |
|---|---|---|
| 1 | A aplicação funciona: os 6 casos de teste passaram | docs/registro_de_testes.md |
| 2 | A versão aparece na janela e é a mesma do CHANGELOG e do README | sim |
| 3 | O pacote foi testado numa pasta limpa | sim |
| 4 | Tag e release publicadas, com o .zip anexado | https://github.com/ryanmartinsM4/techbairro/releases (link da release) |
| 5 | O repositório não tem banco, __pycache__ nem dist | .gitignore configurado corretamente |
| 6 | O histórico tem commits com mensagens claras |https://github.com/ryanmartinsM4/techbairro/commits (link dos commits) |
| 7 | README, manual de uso e requirements.txt estão no repositório |Documentação presente no repositório |
| 8 | A Issue "Teste do README" (Aula 26) está fechada | Issue fechada no repositório do GitHub |
| 9 | O vídeo está publicado e o link abre sem pedir login | https://youtu.be/V7HE5-IIcvc (link do vídeo) |
## Roteiro do vídeo
Bloco                  Tempo           O que vou mostrar ou dizer
1. Problema e solução   30 s          a associação de moradores  precisava de uma plataforma ou sistema digital para a gestão, entao eu desenvolvi o TechBairro  que é um sistema desktop em Python com interface Tkinter e banco SQLite."


2. Demonstração       1 min 30 s       "Vou demonstrar o funcionamento rápido do sistema. Primeiro, a janela de cadastro, onde preencho os dados do morador." (Faz um cadastro rápido).

"Na aba de consulta, consigo ver todos os registos vindos do banco de dados." (Clica em consultar).

"Posso selecionar um cliente para editar as informações ou excluir, com direito a uma mensagem de confirmação para evitar apagar por engano." (Mostra a edição/exclusão).

"Por fim, se tentarmos enviar um dado inválido ou deixar campos obrigatórios vazios, a regra de validação barra a operação e protege o sistema de erros." (Mostra o aviso de erro).

3. Como foi construída    30 s            O projeto foi construído em Python utilizando a biblioteca Tkinter para a interface e um banco de dados relacional SQLite (techbairro.db). O código-fonte foi totalmente versionado com Git e GitHub, contando com scripts de automação e a versão oficial publicada no GitHub Releases junto com  o pacote .zip executável."

4. Aprendizado   30 s               Uma dificuldade que tive foi na hora de gerar o pacote .zip, pois o programa ficava preso num loop gerando gigabytes infinitos. eu Resolvi isso  adicionando o dist em uma das linhas do codigo 
 (a tabela da Parte 3)
## Perguntas
Perguntas por escrito e autoavaliação
No final do docs/entrega_final.md, responda em poucas linhas cada pergunta abaixo. São as
perguntas que a turma e o professor fariam depois da apresentação.
• Pergunta 1: por que o arquivo techbairro.db não está no GitHub?
porque armazena dados dinâmicos gerados em tempo de execução localmente.

• Pergunta 2: qual caso de teste (desta entrega ou das Aulas 15, 20 e 21) pegou um defeito de
verdade? Qual era o defeito?
O teste do script de automação do pacote ZIP. O defeito era que ele criava um arquivo ZIP que aumentava de tamanho infinitamente por faltar a instrução de ignorar o próprio arquivo no código.

• Pergunta 3: se o voluntário da associação tiver só o link do repositório, como ele instala e executa
a TechBairro?Basta clonar o repositório no computador, abrir o terminal na pasta do projeto e rodar o comando python main.py (ou baixar o arquivo ZIP na aba de Releases do GitHub e executar a aplicação).


Autoavaliação (até 5 linhas): o que ficou bom no seu vídeo, o que você mudaria e o que aprendeu de
mais importante nesta unidade curricular. (Parte 6)
## Autoavaliação 
como é a primeira vez fazendo um video ele não ficou tão bom, mais tambem não ficou ruim e a explicação até que dá pro gasto e eu tentaria melhorar mais o audio que eu podia ter feito ele mais facil, mais decidir fazer dificil e o que eu mais aprendi foi como usar o git e tambem o github, e eu acho isso mais importante por que o git hub é algo que eu vou ter que usar muito no futuro,  (Parte 6)


