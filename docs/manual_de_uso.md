# Manual de uso da TechBairro
## A tela principal
A janela principal exibe os campos de entrada de dados para preenchimento (Nome, Telefone, E-mail e Endereço), os botões de controle das ações (como Cadastrar, Alterar, Excluir e Limpar), uma tabela com a lista completa dos clientes cadastrados, um contador de registros totais e uma área de mensagens de status na parte inferior. (o que aparece na janela: campos, botões, contador, mensagens)
## Cadastrar um cliente
1. Digite o nome, o telefone, o e-mail e o endereço nos respectivos campos de texto da tela principal.
2. Clique no botão **Cadastrar** para salvar as informações no sistema.
## Consultar os clientes cadastrados
1. Visualize a tabela de listagem localizada na interface principal para ver todos os clientes salvos e seus respectivos dados em ordem.
## Alterar os dados de um cliente
1. Clique sobre o cliente desejado na tabela da tela principal para carregar seus dados nos campos de cadastro.
2. Altere as informações necessárias e clique no botão **Alterar** (ou Atualizar) para salvar as modificações.
## Excluir um cliente
1. Selecione o cliente que deseja remover clicando sobre ele na tabela da tela principal.
2. Clique no botão **Excluir** e confirme a remoção para apagar o registro do sistema. 
## Regras de preenchimento
| Campo | Obrigatório? | Regra |
|---|---|---|
| Nome | sim| Texto contendo o nome completo do cliente|
| Telefone | sim | Número de contato, preferencialmente incluindo o DDD |
| E-mail | Não | Endereço de e-mail válido para contato.|
| Endereço | Não | Informações de localização do cliente|
## Mensagens do sistema
| Mensagem | O que significa | O que fazer |
|---|---|---|
| Cliente cadastrado com sucesso! | O registro foi gravado com êxito no banco de dados. | Nenhuma ação necessária; o cliente já aparecerá na lista. |
## Dúvidas frequentes
**Como faço para fazer um backup dos meus dados?**
Basta copiar o arquivo `techbairro.db` localizado na pasta principal do projeto e salvá-lo em um local seguro, como um pen drive ou serviço de nuvem.