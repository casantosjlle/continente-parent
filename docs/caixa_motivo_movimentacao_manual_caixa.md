[Início](index.md) / [Caixa](caixa.md) /  Motivo de Movimentação Manual de Caixa

<a href="http://docs.continentenuvem.com.br/dicas.html#dicas"><img align="right" src="http://docs.continentenuvem.com.br/images/dicas.png"></a>



{: #pesquisa}

### Motivo Movimentação Manual de Caixa

Nesta estão cadastrados todos os Motivos das movimentações manual de entrada e saída de Caixa que forem além das já feitas nos outros processos do sistema, como uma retirada de Caixa para Sangria, um adiantamento para um fornecedor etc.

Os motivos de códigos MTCX-001 ao MTCX-007 vem cadastrados por padrão, mas podem ser removidos ou alterados se necessário.

![](images/caixa_motivo_movimentacao_manual_pesquisa.JPG)



{: #cadastro}

Ao clicar em Novo pode ser cadastrado um novo motivo para Movimentação Manual de Caixa, o código do motivo por padrão  está atrelado há uma [sequência numérica](sistema_sequencia_numerica.md) mas pode ser alterada ou removida se necessário.

O Tipo deve ser de entrada ou Saída, se vai entrar dinheiro no Caixa ou Sair dinheiro no Caixa.

A Conta Contábil deve ser a conta do motivo da movimentação manual, por exemplo se for uma retirada de dinheiro para compra de algum material de escritório a conta contábil deve ser de material de escritório ou uso e consumo. 

Para as retiradas de Caixa para depósito em banco deve ser parametrizada a conta transitória de Caixa, pois ao fazer a entrada no sistema do dinheiro no banco o valor sairá da conta transitória e irá para conta contábil do banco. 

![](images/caixa_motivo_movimentacao_manual_cadastro.JPG)



{: #gerarcredito}

#### Gerar crédito para Cliente/Fornecedor

Essa opção deve ser marcada quando a movimentação irá gerar um Crédito para o Cliente ou Fornecedor.

Como por exemplo, quando um cliente faz um pagamento antecipado ou quando é feito um pagamento antecipado para um fornecedor. 

{: #liquidarcredito}

#### Liquidar crédito de Cliente/Fornecedor

Essa opção deve ser marcada quando a movimentação for liquidar um crédito já existente do Cliente ou Fornecedor.

Como por exemplo,  se for pago uma devolução de Cliente em dinheiro ou se o fornecedor devolveu o dinheiro da antecipação.



[Voltar](caixa.md)



