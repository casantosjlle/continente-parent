#### [Início](index.md) / [Gestão Fiscal](gestao_fiscal.md) /Grupo de Impostos

<a href="http://docs.continentenuvem.com.br/dicas.html#dicas"><img align="right" src="http://docs.continentenuvem.com.br/images/dicas.png"></a>

{: #grupoimposto}

### Grupo de Impostos

Nesta tela estão cadastrados os impostos que são calculados nos processos de compra, venda e devoluções.

Com a carga inicial do sistema já estarão cadastrados alguns grupos para vendas e um grupo para compras, você pode utilizá-los ou criar novos.

Os grupos podem ser Tipo: Compra ou Venda, onde o grupo de compra atende os processos de compra e devolução de compra e o Venda atende os processos de venda e devolução de venda.

Sempre que houver a emissão de uma NF-e, os impostos ICMS, IPI, PIS e COFINS devem estar configurados mesmo que não haja cálculo de valor de imposto propriamente, mas o CST deve estar configurado, caso contrário a NF-e será rejeitada. 

Orientamos que todo grupo de imposto criado tenha no mínimo esses 4 impostos, mesmo no processo de compra, onde não há emissão de NF-e, pois a NF-e é emitida pelo fornecedor, a orientação é criar o grupo com esses 4 impostos para que se houver a necessidade de efetuar uma devolução de compra os grupos já estejam preparados.

#### Como cadastrar?

###### ICMS

Para optantes do Simples Nacional é vedado o destaque do ICMS na emissão da NF-e, exceto para o ICMS-ST.

Portanto para os optantes do Simples nacional,  no campo alíquota deve ser informado 0.

No campo CST\CSON nos casos das devoluções deve ser informado sempre 900 e na venda ou compra deve ser informado o CSOSN de acordo com o enquadramento de sua empresa, podendo ser 101,102, 103, 300, 400 ou 500.

![](images/gestao_fiscal_grupo_imposto_icms.jpg)



###### ICMS-ST

O ICMS-ST deve ser recolhido somente em operações com não consumidores finais. 

Portado neste casos os CSOSN permitidos são:

- CSOSN 201: Venda destinada a revendedor não optante pelo Simples Nacional;
- CSOSN 202: Venda destinada a revendedor optante pelo Simples Nacional.

Atualmente o Continente Nuvem faz o cálculo apenas do ICMS-ST sobre MVA. 

No campo alíquota deve ser informada a alíquota de ICMS interestadual, ou seja, do estado de destino da mercadoria.

No Campo UF os estado da alíquota.

No campo MVA o percentual da margem de valor agregado.

No campo Redução MVA deve ser informado o percentual de redução de MVA, se não houver deixar 0

No campo ICMS próprio informar a alíquota interna do estado do adquirente.

No campo Redução de Base informar o percentual de redução de base de imposto, se não houver deixar 0.

![](images/gestao_fiscal_grupo_imposto_icms-st.jpg)

###### IPI

Para empresas optantes do Simples Nacional, no campo CST\CSOSN deve ser informado 53 para as saídas e 03 para as entradas,  no campo alíquota deve ser informado 0 e no campo código de Enq.:999. 

Salvo exceções de devolução de compra, onde o  IPI deve ser informado em campo próprio, neste caso os campos de alíquota e CST\CSOSN devem ser preenchidos conforme orientação do fornecedor.

![](images/gestao_fiscal_grupo_imposto_ipi.jpg)

###### PIS

Para empresas optantes do Simples Nacional, no campo CST\CSOSN deve ser informado 99 e no campo alíquota deve ser informado 0.

![](images/gestao_fiscal_grupo_imposto_pis.jpg)

###### COFINS

Para empresas optantes do Simples Nacional, no campo CST\CSOSN deve ser informado 99 e no campo alíquota deve ser informado 0.

![](images/gestao_fiscal_grupo_imposto_cofins.jpg)





[Voltar](gestao_fiscal.md)                                                                                                                                      





