# Métodos HTTP e sua aplicação em testes

Os métodos HTTP definem qual tipo de operação será realizada na API.

## GET
Utilizado para buscar informações.
O QA deve validar:
- Status 200
- Estrutura da resposta
- Dados corretos

## POST
Utilizado para criar um novo recurso.
O QA deve validar:
- Status 201
- Se o dado foi realmente criado
- Validações de campos obrigatórios

## PUT
Utilizado para atualizar dados.
O QA deve validar:
- Status 200 ou 204
- Se a alteração foi persistida corretamente

## DELETE
Utilizado para remover dados.
O QA deve validar:
- Status 200 ou 204
- Se o dado realmente foi removido
