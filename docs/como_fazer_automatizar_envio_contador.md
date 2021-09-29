[Início](index.md) / Como automatizar envio de documentos para o Contador



#### Dados do Contador

Essa é uma funcionalidade adicional ao Continente Nuvem base.

Acesse Menu: Administração>>Empresa, aba Dados do Contador.

Informe os dados do seu Contador, para automatizar o envio de XML ou autorizar a consulta na SEFAZ.

![](C:\Users\carin\Documents\GITHUB\continente-parent\docs\images\administracao_empresa_contador.jpg)

{: #autxml}

##### Autorizado no XML emitido - autXML

Marque o  campo Autorizado no XML emitido - autXML, e o CPF ou CNPJ informado será levado para o XML da Nota fiscal na tag <autXML>, autorizando assim a consulta do XML da NF-e no Portal Nacional.

![](C:\Users\carin\Documents\GITHUB\continente-parent\docs\images\administracao_empresa_contador_autxml.jpg)



{: #emailcontador}

##### Receber por e-mail DF-e emitidos 

Marque o campo Receber por e-mail DF-e emitidos e sistema fará o envio automático de um e-mail com o XML de todos os Documentos fiscais emitidos no último mês completo juntamente com um relatório de documentos emitidos no mesmo período. O e-mail será enviado para o endereço informado no campo e-mail as 00:00h do dia parametrizado no campo `Todo dia` .

![](C:\Users\carin\Documents\GITHUB\continente-parent\docs\images\administracao_empresa_contador_emailcontador.jpg)