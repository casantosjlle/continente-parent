[Início](index.md) / [Administração](administracao.md) / Empresa

<a href="http://docs.continentenuvem.com.br/dicas.html#dicas"><img align="right" src="http://docs.continentenuvem.com.br/images/dicas.png"></a>

{: #empresa}

### Empresa

No cadastro da empresa deve se atentar a correta inserção dos números de registros e endereço pois serão enviados à Sefaz por meio do documento fiscal eletrônico emitido.

![](images/administracao_empresa.jpg)

{: #dadoscontador}

#### Dados do Contador

![](images/administracao_empresa_contador.jpg)

##### Autorizado no XML emitido - autXML

 Ao marcar este campo o CPF ou CNPJ informado será levado para o XML na tag <autXML>, autorizando assim a consulta do XML da NF-e no Portal Nacional.

![](images/administracao_empresa_contador_autxml.jpg)



##### Receber por e-mail DF-e emitidos 

Ao marcar este campo o sistema fará o envio automático de um e-mail com o XML de todos os Documentos fiscais emitidos no último mês completo juntamente com um relatório de documentos emitidos no mesmo período. O e-mail será enviado para o endereço informado no campo e-mail as 00:00h do dia parametrizado no campo `Todo dia` .

![](images/administracao_empresa_contador_emailcontador.jpg)

###### Tarefa Agendada

Ao marcar o campo Receber por e-mail DF-e emitidos o sistema irá criar uma tarefa agendada que será executada no dia parametrizado. O agendamento da tarefa pode ser consultado na tela de [Tarefa agendada](administracao_tarefa_agendada.md). 

![](images/administracao_tarefa_agendada.jpg)



###### Histórico de e-mail enviado

Os e-mails enviados podem ser consultados através da tela de [Histórico e-mail enviado](administracao_historico_email_enviado.md) no menu Administração. Os e-mails enviados pelo processo de Envio automático ao Contador tem Origem "Anexo com NF-e". A pesquisa pode ser feita ainda pelo endereço de e-mail do destinatário ou pelo assunto:

![](C:/Users/carin/Documents/GitHub/continente-parent/docs/images/gestao_fiscal_gestao_dfe_historico_email_enviado.jpg)



[Voltar](administracao.md)