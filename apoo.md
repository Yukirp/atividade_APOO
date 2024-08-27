# sumário executivo

O sistema será direcionado para empresas que operam por revenda. A plataforma deverá ser capaz de possuir um controle de estoque de produtos variados, além de que, deverá também ser capaz de criar perfis de novos revendedores, os quais serão responsáveis por executar as vendas. 
O sistema irá operar na internet, possuindo uma interface responsiva amigável tanto para desktop quanto para mobile. A depender do tipo de usuário, a tela exibida possuirá diferentes funcionalidades de acordo com o perfil logado. 
O usuário poderá ter acesso às compras efetuadas por diferentes clientes, além de também mostrar o desempenho de cada revendedor para a conta de gerência maior. 
O sistema irá mostrar na grade todos os produtos cadastrados ou os produtos relacionados às categorias mostradas na interface. “O sistema pode listar todos os vendedores e mostrar o total de vendas realizadas no último mês”. 
O deverá possibilitar uma visão geral sobre os produtos, vendas e vendedores, facilitando assim a gestão do negócio da empresa.

### Requisitos Funcionais

| **Código** | **Descrição**                                                                                                        | **Campos**                                                                                                                                  |
|------------|----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| RF01       | O sistema deverá possibilitar o login do usuário.                                                                    | Email e Senha                                                                                                                               |
| RF02       | O sistema deverá ter a funcionalidade que possibilite gerenciar os vendedores.                                       |                                                                                                                                             |
| RF03       | O usuário deve ser capaz de visualizar todos os produtos cadastrados ou os produtos relacionados a determinada categoria. |                                                                                                                                             |
| RF04       | O usuário deve ser capaz de adicionar um ou mais produtos a um carrinho de compras.                                  |                                                                                                                                             |
| RF05       | O usuário deve ter acesso a uma página que detalha as informações do produto.                                        |                                                                                                                                             |
| RF06       | O vendedor deve escolher entre uma das três formas de pagamento aceitas pela plataforma.                             |                                                                                                                                             |
| RF07       | O Representante de vendas deve ser capaz de realizar uma compra.                                                     | Endereço do cliente, número do cliente, forma de pagamento, CNPJ do cliente, valor total da compra, data de compra                          |
| RF08       | O sistema deverá possibilitar que o gerente e o vendedor possam visualizar as compras de um determinado cliente.     | Nome ou CPF                                                                                                                                 |
| RF10       | O sistema deve permitir que os vendedores visualizem suas próprias informações pessoais.                             | Nome, CPF, e-mail, telefone, endereço                                                                                                       |
| RF11       | O sistema deve permitir que os vendedores visualizem o histórico de suas próprias vendas.                            |                                                                                                                                             |

---

### Requisitos Não Funcionais

| **Código** | **Restrição**                                                   | **Categoria**  |
|------------|-----------------------------------------------------------------|----------------|
| RNF01      | Não possui                                                      | Segurança      |
| RNF02      | Somente o gerente pode realizar cadastro, alteração e deletar vendedores. | Relatório      |
| RNF03      | -                                                               | Relatório      |
| RNF04      | O valor total deve ser a soma dos produtos vezes a quantidade.  | Compra         |
| RNF05      | Não possui                                                      | Compra         |
| RNF06      | A forma de pagamento deve ser: PIX, Crédito ou Débito.          | Compra         |
| RNF07      | O CNPJ do cliente deve ser válido.                              | Registro       |
| RNF08      | Os campos devem ser válidos.                                    | Relatório      |
| RNF10      | O vendedor logado pode visualizar apenas suas informações.      | Visualização   |
| RNF11      | Apenas o vendedor logado pode visualizar seu próprio histórico de vendas. | Relatório      |
