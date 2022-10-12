# Desafio_DIO_refinando_banco_de_dados_de_E-commerce
## Este repositório é referente ao desafio "Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE" do bootcamp DIO UNIMED Ciência de Dados.

Solicitação: Refinar o banco de dados de e-commerce previamente inciado com os seguintes dados:
### -Cliente PJ e PF: Uma conta pode ser PJ ou PF, mas não pode ter as duas informações
      
      Foi criado um atributo chamado "PJ ou PF" do tipo booleano na entidade Cliente.

### - Pagamento: Pode ter cadastrado mais de uma forma de pagamento

      Foi criada uma entidade fraca chamada "Método de pagamento" com uma cardinalidade de 1:n com a entidade forte Cliente
      
### - Entrega: Possui código de rastreio

      Foram criados atributos não-nulos e obrigatórios na entidade fraca "Entrega"
