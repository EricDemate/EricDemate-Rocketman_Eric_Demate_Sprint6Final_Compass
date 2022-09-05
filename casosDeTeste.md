![Banner](https://user-images.githubusercontent.com/64226050/188370353-6cf03a4d-6fcb-4bbb-af36-7295717a8ecb.png)

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/EricDemate/Rocketman_Eric_Demate_Compass/blob/develop/Licence)
## SUÍTE DE CASOS DE TESTE COMPLETA

### CT01- Validar Rota Cadastro de Usuário

*  CT01 Cadastrar Usuário - c/ êxito
* CT01.1 Cadastrar Usuário s/ nome
* CT01.2 Cadastrar Usuário email incorreto
* CT01.3 Cadastrar Usuário s/ email
* CT01.4 Cadastrar Usuário s/ senha
* CT01.5 Cadastrar Usuário admin sem valor booleano
* CT01.6 Cadastrar Usuário já existente
* BUG1 - Cadastrar Usuario - c/ 1 caracter :(

### CT02- Validar Rota de Cadastro de Produto

* CT02 Cadastrar Produto c/ êxito
* CT02.1 Cadastrar Produto c/ Usuário
* CT02.2 Cadastrar Produto c/ token ausente
* CT02.3 Cadastrar Produto existente

### CT03- Validar Rota de  Cadastro de Carrinho

* CT03 Cadastra Carrinho c/ êxito
* CT03.1 Cadastra Usuário/Produto  > c/ Login
* CT03.2 Cadastra Carrinho c/ Produto Duplicado
* CT03.3 Cadastra Carrinho c/ Produto qtd maior que estoque
* CT03.4 Cadastra Carrinho c/ token inesistente

### CT04- Validar Rota de  Login de Usuário

* CT04 Login c/ êxito
* CT04.1 Login s/ senha
* CT04.2 Login s/ êxito -> senha ou email invalido
* CT04.3 Login c/ email em branco
 
### CT05- Validar Rota de Modificação de Usuário

* CT05 Modificar Usuário existente - c/ êxito
* CT05.1 Modificar Usuário existente admin para normal
* CT05.2 Modificar Usuário existente - s/ nome
* CT05.3 Modificar Usuário existente - email incorreto
* CT05.4 Modificar Usuário existente - email duplicado
* CT05.5 Modificar Usuário existente - s/ email
* CT05.6 Modificar Usuário existente - s/ senha
* CT05.7 Modificar Usuário existente - s/ valor booleanoopy
* CT05.8 Modificar Usuário inexistente

### CT06- Validar Rota de Modificação de Produto

* CT06 Modificar Produto c/ êxito
* CT06.1 Modificar Produto c/ mesmo nome
* CT06.2 Modificar Produto s/ token
* CT06.3 Modificar Produto c/ {_id} inexistente
* CT06.4 Modificar Produto c/ Usuário comum
 
### CT07- Validar Rota Remoção de Usuário

* CT07 Deletar Usuário - c/ êxito
* CT07.1 Deletar Usuário s/ _id
* CT07.2 Deletar Usuário Inexistente
** * CT07.3 Deletar Usuário c/ carrinho

### CT08- Validar Rota de Remoção de Produto

* CT08 Deletar Produtos c/ êxito
* CT08.1 Deletar Produtos inseridos em carrinho
* CT08.2 Deletar Produtos token errado
* CT08.3 Deletar Produtos c/ Usuário comum

### CT09- Validar Rota de  conclusão de compra do carrinho

* CT09 Concluir Compra
* CT09.1 Concluir Compra c/ token inexistente
* CT09.2 Concluir Compra Carrinho Vazio

### CT10- Validar Rota de  cancelamento de compra do carrinho

* CT010 Cancelar Compra
* CT010.1 Cancelar Compra Carrinho Vazio
* CT010.2 Cancelar Compra c/ token inexistente

### CT11- Validar Rota de listagem de Usuário

* CT11 Listar Usuários
* CT11.1 Listar Usuários c/ {_id}
* CT11.2 Listar Usuários inexistente

### CTT12- Validar Rota de listagem de Produto

* CT12 Lista Produtos
* CT12.1 Lista Produtos c/ {_id}
* CT12.2 Lista Produto inexistente

### CT13- Validar Rota de listagem de Carrinho

* CT13 Lista Carrinhos
* CT13.1 Lista Carrinhos c/ {_id) 

____

![Banner](https://user-images.githubusercontent.com/64226050/188371378-9f12963c-251c-405f-94a0-f46624065097.png)

