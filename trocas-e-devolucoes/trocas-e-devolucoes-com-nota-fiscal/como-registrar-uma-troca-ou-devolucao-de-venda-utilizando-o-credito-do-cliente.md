---
tags:
  - tag: troca-devolucao
    primary: true
  - nota-fiscal
  - clientes
  - vendas
---

# Como registrar uma troca ou devolução de venda utilizando o crédito do cliente

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar:** texto escrito a partir do vídeo. Conferir na tela do sistema os trechos marcados [confirmar na tela].
{% endhint %}

Use este processo para devolver um item com nota de devolução (sem tributar duas vezes), gerar crédito para o cliente e usar esse crédito em uma nova venda, como uma troca.

## Passo a passo

### Localizar a venda original

1. Se o cliente trouxer o **cupom de troca**, copie o número que aparece nele.
2. Sem cupom, descubra a data da compra: acesse **COMPRAS > GESTÃO DE ESTOQUE > LISTAR PRODUTOS**, bipe o código de barras do produto e veja, no histórico, **Clientes que compraram esse produto** com data e hora.
3. Com a data, acesse **Relação de vendas** e clique no ícone de **mapa do Brasil** da venda para ver o número e a série da NFC-e.

### Fazer a devolução

4. Acesse **VENDAS > DEVOLUÇÃO DE VENDA**.
5. Cole o número do cupom de troca e clique para localizar a venda. A Phibo identifica a nota (número e série). Se preferir, digite o número e a série da nota.
6. Mantenha o mesmo cliente ou altere para quem está trazendo a peça (por exemplo, quem ganhou de presente), para gerar o crédito para essa pessoa.
7. Em **Transporte**, selecione **Sem frete**.
8. Em **Item de devolução**, clique na **lupa** e na **bolinha verde** para adicionar o produto.
9. Clique em **Gerar e enviar NF-e**. A nota de devolução aparece em **Listar**.

{% hint style="warning" %}
Não altere a parte de configuração fiscal que já vem preenchida na tela de devolução [confirmar na tela]. Mudar esses campos pode causar problemas fiscais sérios.
{% endhint %}

### Conferir o crédito

10. Acesse **VENDAS > CONSULTAR VENDAS > CRÉDITO CLIENTE**.
11. Clique na **bolinha preta com seta branca** ao lado do cliente para ver o detalhamento e a origem do crédito (devolução de venda).

### Usar o crédito na troca

12. Acesse **PDV > REGISTRAR VENDA**, informe o vendedor e o cliente. O crédito para troca aparece na tela.
13. Lance o produto que o cliente vai levar e clique em **Efetuar recebimento**.
14. Em **Forma de pagamento**, escolha a última opção, **Crédito troca**.
15. Clique em **Concluir venda**. O crédito é consumido e você pode emitir, imprimir ou enviar a nova nota.

## 🎬 Vídeo

Em casos de trocas, trocas com saldo negativo ou devoluções de venda utilize o procedimento indicado no vídeo abaixo :

{% hint style="warning" %}
Atenção: Para realizar esse procedimento você deve possuir o módulo fiscal ativo e já ter emitido nota fiscal para a venda que está devolvida
{% endhint %}

{% embed url="<https://www.loom.com/share/8c9d739a09834715a02cd02977ad28b8?sid=2a70113e-2928-430f-ab2a-c9235d00b16b>" %}

---

*🔎 Também procurado como: troca, devolução, trocar peça, devolver, nota fiscal, NF, NFC-e, NF-e, cupom fiscal, cliente, cadastro de cliente, venda, vender, PDV, frente de caixa.*
