[Início](index.md) / [Administração](administracao.md) / Período

<a href="http://docs.continentenuvem.com.br/dicas.html#dicas"><img align="right" src="http://docs.continentenuvem.com.br/images/dicas.png"></a>

{: #periodo}

### Período

O objetivo do período é impedir que lançamentos sejam feitas em datas indevidas e calcular o último saldo contábil e [custo médio](administracao_periodo.md#customedio) dos produtos.

Para que seja realizada uma transação no CN, o período que está sendo feito a transação deve estar em aberto, caso contrário o sistema emitirá o alerta de erro solicitando a abertura do período. **Orientamos sempre manter somente o período atual com status Aberto.**

![](images/administracao_gerenciamento_periodo.jpg)



{: #customedio}

#### Custo médio

##### O que é?

O custo médio ou custo médio ponderado, representa o valor da média dos gastos com a compra de cada produto. 

##### Como é calculado?

A cada movimentação de entrada de um produto no estoque, o sistema realizará o cálculo automático do custo médio.

As movimentações de entrada contempladas são:

Lançamento manual de compra: onde o custo será o Valor dos produtos +Frete+Seguro+ICMS ST+IPI

Lançamento manual de entrada via Movimentação manual de estoque:, onde o custo será o custo total informado manualmente.

###### *Fórmula:* 

![](images/administracao_periodo_custo_medio_formula.jpg)



###### *Registro de estoque:*

![](images/administracao_gerenciamento_periodo_registro_estoque.jpg)



##### Onde é usado?

É com base no custo médio de cada produto que será executada a transação e contabilização de estoque na Venda. 

###### *Exemplo:*  

Vamos analisar a primeira venda executada no exemplo de registro de estoque, onde o produto tem um custo médio de R$5,13 e quantidade vendida foi 300.  Vamos exemplificar com um preço de venda unitário de R$9,50. 

A transação de saída de estoque será de R$1539,00, que é R$5,13 x 300.

![](images/administracao_gerenciamento_periodo_transacoes_estoque.jpg)



A contabilização do estoque na venda será do mesmo valor da transação do estoque, onde teremos então:

 Contabilização do estoque: D- Custo da mercadoria vendida R$1539,00

​                                                   C- Estoque de mercadoria R$1539,00

![](images/administracao_gerenciamento_periodo_lancamento_contabil.jpg)



Já a receita de venda será contabilizada de acordo com o preço de venda aplicado, que é R$9,15 x 300.

Contabilização da Receita:   C- Receita de Venda   R$2850,00 

​                                                  D- Duplicatas a Receber  R$2850,00



[Voltar](administracao.md)



##### 