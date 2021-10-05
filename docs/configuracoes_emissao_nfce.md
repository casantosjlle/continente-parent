[Início](index.md) / Configurações para Emissão de NFC-e

<a href="http://docs.continentenuvem.com.br/dicas.html#dicas"><img align="right" src="http://docs.continentenuvem.com.br/images/dicas.png"></a>



{: #configuracoes_emissao_nfce}

## Configurações para Emissão NFC-e

Siga o passo a passo a seguir para configurar o sistema para emissão de NFC-e, Nota Fiscal de consumidor eletrônica.



#### 1º Importar o Certificado Digital

Se você já fez as  Configurações para Emissão de NF-e você pode pular esta etapa.

Acesse o Menu Sistema>>Certificado Digital e faça a importação do certificado digital de sua empresa e informe a senha de acesso ao certificado.

![](images/configuracoes_nfe_importar_certificado.gif)



#### 2º Parametrize o ambiente de emissão de DF-e: Produção ou homologação

Se você já fez as  Configurações para Emissão de NF-e você pode pular esta etapa.

Acesse o Menu Sistema>>Parametrização>>Documento Fiscal>>Geral>>Ambiente> altere o ambiente para produção.

Na instalação do ERP Continente Nuvem esse parâmetro vem definido como homologação. O ambiente de homologação da SEFAZ é utilizado apenas para testes e não tem validade fiscal.

O parâmetro de ambiente define os ambientes de emissão de NF-e NFC-e

![](images\configuracoes_nfe_parametrizar_ambiente.gif)



#### 3º Parametrize o Certificado Digital 

Se você já fez as  Configurações para Emissão de NF-e você pode pular esta etapa.

Acesse o Menu Sistema>>Parametrização>>Documento Fiscal>>Geral>> Certificado Digital e parametrize o Certificado Digital importado anteriormente.

![](images\configuracoes_nfe_parametrizar_certificado1.gif)



#### 4º Informar a Série da NFC-e

Acesse o Menu Sistema>>Parametrização>>Documento Fiscal>>NFC-e e informe a Série da NF-e que será emitida.

![](\images\configuracoes_nfce_serie1.gif)



#### 4º Informar CSC Token e Id do Token da NFC-e

Acesse o Menu Sistema»Parametrização»Documento Fiscal»NFC-e>> e insira o CSC Token e o ID do Token.

O CSC (Código de Segurança do Contribuinte) , é um código de segurança alfanumérico, de conhecimento exclusivo do contribuinte e da SEFAZ, usado para garantir a autoria e a autenticidade do DANFE NFC-e.

O CSC deve ser solicitado pelo contribuinte no site da Sefaz ou da Receita de cada do estado, separando entre ambiente de homologação e de produção.



![](images/configuracoes_nfce_csc_token.gif)



#### 5º Atualize a Sequência Numérica

Acesse o Menu Sistema>>Sequência Numérica, pesquise pela entidade NFCe e clique em editar. No campo Próximo Sequencial informe qual deve ser o número de NFC-e a ser emitido pelo Continente. Uma vez parametrizado o sistema irá dar continuidade nesta numeração.

![](images/configuracoes_nfce_sequencia_numerica.gif)



Se você for um emissor de NF-e veja as também as [Configurações para emissão de NF-e](configuracoes_emissao_nfe).





[Voltar](index.md)

