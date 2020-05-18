[Início](index.md) / [Financeiro](financeiro.md) /  [Contas à Receber](financeiro.md#financeirocontasreceber) / Contas à Receber

<a href="http://docs.continentenuvem.com.br/dicas.html#dicas"><img align="right" src="http://docs.continentenuvem.com.br/images/dicas.png"></a>



{: #contasreceber}

### Contas à Receber

Nesta tela estão disponíveis as parcelas a Receber que foram faturadas como crediário ou cheque.

*Status:* Cancelado: Parcelas oriundas de Vendas que foram canceladas.

​             Revertido: Parcelas que foram recebidas e depois o recebimento foi revertido. Ao reverter o recebimento o sistema atualiza o status que antes estava Recebido para Revertido e gera um novo título em aberto igual ao original.

Os valores de juros e multa são calculados pelo sistema através das alíquotas parametrizadas nos [ajustes de Contas à Receber](sistema_ajustes_contas_receber.md#contasreceber), mas podem ser editados manualmente  ao clicar nos próprios campos em cada parcela. O valor de desconto também pode ser alterado manualmente em cada parcela ou através do menu [Desconto Total](financeiro_contas_receber.md#descontototal).

Se editados, os valores de juros, multa e desconto são salvos temporariamente, apenas para que seja feito o recebimento, assim que a tela de Contas a Receber for fechado e reaberto, nas parcelas em aberto o valor do juros e multa são novamente calculados  e o desconto é zerado.

![](images/financeiro_contas_receber_descontolinha.jpg)



Clicando com botão inverso do mouse em cima da parcela,  ou no botão `Mais` no lado inferior direito da tela, alguma opções de acesso estarão disponíveis.

**Para parcelas em aberto,** que são as com status Vencido ou À vencer, as seguintes opções estão disponíveis:

![](images/financeiro_contas_receber.jpg)



{: #descontototal}

#### Desconto Total

Nesta tela é possível informar um valor único de desconto que o sistema fará o rateio proporcionalmente para cada parcela selecionada. O desconto pode ser informado em valor ou em percentual.

![](images/financeiro_contas_receber_descontototal.jpg)



{: #reagendarvencimento}

#### Reagendar Vencimento


Nesta tela  é possível alterar o vencimento de uma parcela.

Uma vez alterado o vencimento, essa nova informação é salva permanentemente.



![](images/financeiro_contas_receber_reagendar.jpg)



{: #receber}

#### Receber de Crediário

O processo de recebimento no contas a Receber é similar ao faturamento, basta informar a(s) forma(s) de pagamento e faturar.

![](images/financeiro_contas_receber_receber.jpg) 

*Dinheiro*: A opção dinheiro só fica disponível se o usuário estiver com algum Caixa aberto.

*Crediário*:  O valor recebido como crediário é considerado um reparcelamento. Quando é feito um recebimento parcial, o valor que continua em aberto deve ser informado como crediário para que seja novamente lançado como uma nova parcela no Contas a Receber.

*Cartão:* O valor faturado como Cartão, seja débito, crédito, ou vales será lançado como transações para [recebimento de cartão](financeiro_administradora_cartao.md#recebimento).

*Cheque*:  O valor faturado como cheque será levado para o [Contas a Receber](financeiro_contas_receber.md#contasreceber).

*Depósito:* O valor faturado como depósito será lançado como uma entrada diretamente na conta bancária informada.

*Crédito:* Somente poderá ser faturado como crédito, se houver crédito disponível para o Cliente. Neste caso o recebimento faz o abatimento do crédito no valor informado no campo *consumido*

Após o faturamento o histórico de abatimentos e saldo de crédito para o cliente pode ser visto diretamente no [menu crédito no cadastro do cliente](vendas_cliente.md#credito).

![](C:/Users/carin/Documents/GitHub/continente-parent/docs/images/vendas_venda_faturamento_pagamento_credito.jpg)



**Para parcelas recebidas**, as seguintes opções estão disponíveis:

![](images/financeiro_contas_receber_recebido.jpg)



{: #reversao}

#### Reversão de Recebimento

Nesta tela  é possível fazer a reversão de um recebimento. O processo faz a reversão financeira e contábil do recebimento, basta informar o motivo da reversão. Esse motivo é utilizado como histórico no comprovante contábil.

Se duas parcelas foram recebidas juntas, as duas são revertidas.

![](images/financeiro_contas_receber_reversao.jpg)]



Ao reverter o recebimento o sistema atualiza o status que antes estava Recebido para Revertido e gera um novo título em aberto igual ao original.

![](images/financeiro_contas_receber_revertido.jpg)



{: #comprovante}

#### Comprovante de Recebimento

Nesta tela  é possível imprimir o comprovante do recebimento. O formato do comprovante é para impressão em bobina de 80mm e o logo é parametrizável no cadastro da [Empresa](administracao_empresa.md#logo).

![](images/financeiro_contas_receber_comprovante.jpg)





[Voltar](financeiro.md#financeirocontasreceber)

