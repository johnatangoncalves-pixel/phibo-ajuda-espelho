---
tags:
  - tag: compras
    primary: true
  - nota-fiscal
  - estoque
  - produtos
  - vendas
---

# Como alterar a margem de venda ou a coleção de uma nota de compra

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar:** texto escrito a partir do vídeo. Conferir na tela do sistema os trechos marcados [confirmar na tela].
{% endhint %}

Errou a margem de venda ou a coleção ao inserir um XML? Veja como corrigir antes de validar os produtos e como ajustar os que já foram validados.

{% hint style="warning" %}
A edição do XML só altera os produtos que ainda não foram validados. Produtos já validados estão cadastrados no sistema e precisam ser editados no cadastro de produto (veja a Parte 2).
{% endhint %}

## Passo a passo

### Parte 1: Editar o XML antes da validação

1. Acesse **COMPRAS > NOTA FISCAL > VALIDAR PRODUTOS** para identificar o fornecedor e o número da nota. Produtos com **x vermelho** ainda não deram entrada.
2. Acesse **COMPRAS > NOTA FISCAL > LER ARQUIVO XML**.
3. Clique em **Editar nota de entrada**.
4. Informe o fornecedor. O sistema lista as notas dele. Se houver muitas, use a data de emissão e o número da nota para achar a certa.
5. Clique no ícone da nota para abri-la [confirmar na tela].
6. Se quiser, edite o código de barras de cada peça ou clique em **Limpar EAN** para apagar todos. O código do produto não pode ser alterado aqui.
7. Altere a **coleção** e a **margem de venda**.
8. Clique fora do campo ou aperte **Tab** para o sistema recalcular os preços de venda.
9. Clique em **Salvar**.
10. Volte em **VALIDAR PRODUTOS**, confira o **preço unitário de venda** e valide.

### Parte 2: Alterar produtos já validados

1. Acesse **COMPRAS > GESTÃO DE ESTOQUE > CADASTRAR PRODUTO NOVO**.
2. Localize o produto e clique no ícone de edição.
3. Para mudar uma variação, edite a **margem de venda** ou o **preço** dela e salve. Essa edição vale só para aquela variação.
4. Para mudar todas as variações de uma vez, clique em **Outras ações > Alterar preço de venda**, informe a nova margem e salve.

## Entendendo a tela

* **Preço de custo unitário:** quanto custa cada peça.
* **Valor total:** custo total dos produtos da nota. Ele não muda quando você altera a margem.
* **Preço unitário de venda:** preço calculado com a margem aplicada.

## 🎬 Vídeo

Veja o passo a passo abaixo para entender como alterar a margem de venda ou coleção de um xml inserido no sistema:

{% embed url="<https://www.loom.com/share/5ebb4c8924314db3af71cde3c4e289ac?sid=75e2ea31-59be-4609-893d-dccbcafb9122>" %}

{% hint style="info" %}
**IMPORTANTE: Os produtos já validados não terão sua margem de venda ou coleção alterados, somente os produtos não validados.**
{% endhint %}

---

*🔎 Também procurado como: compra, fornecedor, nota de entrada, mercadoria, nota fiscal, NF, NFC-e, NF-e, cupom fiscal, estoque, inventário, contagem, saldo de peças, produto, peça, cadastro de produto.*
