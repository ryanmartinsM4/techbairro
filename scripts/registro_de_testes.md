# Registro de testes da TechBairro
Versão testada: 3.3.2 · Data: 28/10/2026 · Responsável: Ryan martins costa
Sistema operacional e versão do Python: ____
| ID | Requisito | Passos e dados | Esperado | Obtido | Status |
|---|---|---|---|---|---|
| CT01 | RF01 | Cadastrar um cliente com todos os campos certos | vai cadastrar o cliente|  cadastrou o cliente| passou. |
| CT02 | RF01 | Salvar com Nome e Endereço vazios | vai aparecer uma mensagem para preencher o nome e endereço | Erro exibido solicitando os campos obrigatórios | passou.|
| CT03 | RF02 | Telefone 61 9999 0000 (com espaços) | mensagem para preencher só com números | telefone errado: use somente numeros| passou. |
| CT04 | RF03 | E-mail ana@email (sem ponto) | formato de email errado| email invalido: uso o formato nome@gmail.com| passou|
| CT05 | RF05 | Editar um cliente, trocar o telefone e salvar | ele vai atualizar os dados do cliente | cliente atualizado com sucesso | passou|
| CT06 | RF06 | Excluir um cliente: responder Não, depois Sim | não vai mudar nada quando aperta o não, mais exclui o cliente quando aperta sim | cliente excluido | passou |
## Testes automáticos
Saída do `python testar_validacao.py`: ok
## Defeitos encontrados
nenhum (o que falhou, como foi corrigido e em qual commit; ou "nenhum")