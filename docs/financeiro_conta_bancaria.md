<a href="http://docs.continentenuvem.com.br/dicas.html#dicas"><img align="right" src="http://docs.continentenuvem.com.br/images/dicas.jpg"></a>



{: #contabancaria}

### Conta Bancária

Nesta tela devem ser cadastradas todas as Contas bancárias que a empresa tem e movimenta.

Clicando com botão inverso do mouse em cima da conta,  ou no botão `Mais` no lado inferior direito da tela, as seguintes opções ficam disponíveis:

![](images/financeiro_contas_bancarias.jpg)



{: #movimentacaomanual}

#### Movimentação Manual de Banco

Nesta podem ser inseridas todas as movimentações de entrada e saída das contas bancárias que forem além das já feitas nos outros processos do sistema, como por exemplo uma saída devido há uma tarifa bancária, ou uma entrada referente há um adiantamento de Cliente.

Emissão é a data que a transação aparecerá no banco e também a data de contabilização.

Os motivos devem ser previamente cadastrados no Cadastro de [Motivo de Movimentação Manual de Banco](financeiro_motivo_movimentacao_manual_banco.md#cadastro).

![](images/financeiro_contas_bancarias_movimentacao_manual.jpg)

Alguns campos só aparecem de acordo com o motivo informado, por exemplo o campo Cliente ou Fornecedor só aparece se o motivo for parametrizado para [Gerar crédito para o cliente\fornecedor](financeiro_motivo_movimentacao_manual_banco.md#gerarcredito).

![](images/financeiro_contas_bancarias_movimentacao_manual_cliente.jpg)



Os campos de Créditos em aberto só aparecem se o motivo for parametrizado para [Liquidar crédito para o cliente\fornecedor](financeiro_motivo_movimentacao_manual_banco.md#liquidarcredito).

![](images/financeiro_contas_bancarias_movimentacao_manual_liquidarcredito.jpg)



{: #transacoes}

#### Transações Bancárias

Esta é uma tela de consulta, onde estão disponíveis todas as transações bancárias realizadas.

O Status Aberto representa as transações que ainda não foram Conciliadas. 

O Status Liquidado representa as transações que já foram Conciliadas, o histórico da Conciliação podem ser visualizado no menu [Histórico Conciliação](financeiro_conta_bancaria.md#historicoconciliacao)

O Status Cancelado representa as transações que foram canceladas através dos processos de [Cancelamento de Venda](venda_cancelamento.md) ou [Reversão de Recebimento](financeiro_contas_receber.md#reversao) 

![](images/financeiro_contas_bancarias_transacoes.jpg)



{: #saldo}

#### Saldo Bancário

Esta é uma tela de consulta, onde está disponível o Saldo bancário registrado no sistema, onde:

*Saldo Conciliado:* Saldo da ultima conciliação bancária feita.

*Saldo não conciliado*: Total das transações não conciliadas

Saldo Atual: Saldo da ultima conciliação bancária feita + Transações não conciliadas

![](images/financeiro_contas_bancarias_saldo.jpg)



{: #historicoconciliacao}

#### Histórico Conciliação

Esta é uma tela de consulta, onde está disponível o histórico das Conciliações bancárias realizadas.

![](images/financeiro_contas_bancarias_historico_conciliacao.jpg)



{: #conciliacao}

#### Conciliação Bancária

Nesta tela é feito o processo de conciliação bancária.

Na grade são listadas todas as transações bancárias realizadas com status aberto, ou seja que ainda não foram conciliadas.

No Campo `Extrato` deve se informar uma identificação para o extrato bancário, pode ser um número ou uma descrição. Nos campos `Data do Extrato` e `Saldo do Extrato` devem ser informadas as informações conforme descrito no extrato bancário.

![](images/financeiro_contas_bancarias_conciliacao_bancaria.jpg)



Ao selecionar as transações o sistema informa na parte inferior da tela os valores informados, como saldo inicial, as transações selecionadas e se há diferença de valores.

Caso necessário, pode-se incluir nesta mesma tela as [Movimentações Manual de Banco](financeiro_conta_bancaria.md##movimentacaomanual)

Não havendo diferenças o Extrato pode ser conciliado.

![](images/financeiro_contas_bancarias_conciliacao_bancaria_diferenca.jpg)



[Voltar](financeiro.md#financeirobanco)

