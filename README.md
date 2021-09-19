# ProjetoFinalTech
# ProjetoFinalTech

O projeto tem como o objetivo criar um gerenciamento de clientes e contas bancárias, onde será s disponibilizada uma API que forneça dados de clientes e contas (inicialmente para
consulta).

OBJETIVOS

Será construida uma API Spring BOOT que possuindo 2 endpoints principais:

● Recuperação de todas as contas bancárias
● Recuperação dos detalhes de 1 conta bancária (inclusive dados do seu titular)

ESPECIFICAÇÕES

Tecnologias que serão usadas para este projeto:

Banco de Dados: MySQL
API: SpringBoot

Modelagem de Dados:

Todo cliente possui os seguintes dados para serem cadastrados
● codigo interno
● nome
● cpf
● telefone
● email

Toda conta bancária possui os seguintes dados
● numero
● agência
● tipo da conta (0 - conta corrente, 1 - poupança, 2 - investimento)
● saldo
● titular da conta

ENTREGÁVEIS

Será entregue endpoint para consulta de todas as contas:

/contas
Endpoint para consultas do detalhe da conta
/contas/{id}
Todos os dados devem ser retornados em formato JSON.


Por:

- Lucas Eduardo Carlos Cravo
- Natalico Junior
- Lais
- Diego Justino
- Jonatha Teixeira
- Denise
