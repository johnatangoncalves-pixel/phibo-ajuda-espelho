---
tags:
  - tag: compras
    primary: true
  - nota-fiscal
  - estoque
  - produtos
---

# Como separar produtos que vieram juntos na nota de compra

Às vezes o fornecedor envia na nota vários tamanhos ou cores em um único item (por exemplo, "vestido midi, 4 unidades" com P, M e G). Veja como separar essas quantidades na validação da nota.

{% hint style="info" %}
**Antes de começar:** leia o arquivo XML da nota, defina coleção e margem e clique em **Salvar**. Essa parte tem um tutorial próprio.
{% endhint %}

## Passo a passo

### Ajustar gênero, marca e categoria

1. Acesse **COMPRAS > NOTA FISCAL > VALIDAR PRODUTOS** e abra a nota.
2. Marque o quadradinho do topo para selecionar todos os produtos. Desmarque os que estiverem com a bolinha verde.
3. Em edição em massa, defina o **gênero** e, se precisar, a **marca**, e clique em **Salvar**.
4. Para corrigir a categoria de um produto, selecione só ele, clique em **Ações > Categoria**, escolha a categoria e salve.

### Separar as quantidades

1. No produto, clique em **Ações** e no ícone de lápis com folha para abrir o detalhamento.
2. Se já houver uma linha pronta que você não quer, clique na lixeira para começar do zero.
3. Escolha a **grade** (ex.: P) e a **cor**, e informe a **quantidade** desse tamanho.
4. Informe o código de barras: clique em **Gerar**, bipe a etiqueta da peça ou digite o código.
5. Repita para cada tamanho e cor até a quantidade conferida ficar igual à da nota (ex.: 4 de 4).
6. Clique em **Confirmar**. O produto fica com a bolinha verde.

## Entendendo a tela

* **Bolinha verde:** o produto já foi conferido. Ele não pode estar selecionado na edição em massa.
* **Linha exibida:** depois de separar, a lista mostra só a última variação cadastrada, mas todas foram salvas no produto.
* **Código da nota:** quando a nota traz código de barras, use esse código na primeira variação.

{% hint style="warning" %}
Se o fornecedor mandar um **kit** (ex.: 1 kit com 10 peças), não dá para separar na nota, porque quantidade e preço são informações fiscais do XML. Confira o kit normalmente e depois ajuste o produto em **CADASTRAR PRODUTO**, clicando em **Editar** para informar tamanhos, cores, códigos, custo e preço de venda corretos.
{% endhint %}

## 🎬 Vídeo

Assista abaixo o vídeo e veja o passo a passo completo de como remover uma variação específica de um produto cadastrado:

{% embed url="<https://www.loom.com/share/7fea5d4bd83c4d9bbf55827863321293?sid=e9a337c7-7b7d-4ca3-99b7-0f51cb303d18>" %}

---

*🔎 Também procurado como: compra, fornecedor, nota de entrada, mercadoria, nota fiscal, NF, NFC-e, NF-e, cupom fiscal, estoque, inventário, contagem, saldo de peças, produto, peça, cadastro de produto.*
