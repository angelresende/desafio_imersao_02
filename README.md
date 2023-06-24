## DESAFIO 02 - Imersão Full Cycle

Neste desafio, você deve criar uma aplicação Nest.js com Docker que rode na porta 3000.


Esta aplicação precisa expor 2 rotas de API Rest:

<p>• Listar assets - POST /api/assets </p>
<p>• Criar assets - GET /api/assets </p>
<p>• Criar orders - POST /api/orders </p>
<p>• Listar orders - GET /api/orders </p>

Um asset tem os seguintes dados:

<p>• id (é informado pelo usuário) </p>
<p>• symbol (símbolo do ativo) </p>

Uma order tem os seguintes dados:

<p>• id automático do banco </p>
<p>• asset_id (relacionado com Asset) </p>
<p>• price </p>
<p>• status (open, pending, closed) (não pode deixar mandar o status no POST) </p>

