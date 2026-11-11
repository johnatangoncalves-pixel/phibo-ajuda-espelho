---
tags:
  - tag: loja-online
    primary: true
  - produtos
---

# Como vincular produtos à Bagy

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar:** texto escrito a partir do vídeo. Conferir na tela do sistema os trechos marcados [confirmar na tela].
{% endhint %}

Use a vinculação quando o mesmo produto já existe na Phibo e na Bagy, mas os dois ainda não estão conectados. Assim o estoque passa a ser atualizado entre os dois.

{% hint style="info" %}
**Antes de começar:** o produto precisa existir nos dois lugares. Se ele estiver só na Phibo, use a ação **Cadastrar produto no e-commerce**, e não a vinculação.
{% endhint %}

## Passo a passo

1. Na Phibo, localize o produto na tela de produtos [confirmar na tela]. Produtos não vinculados aparecem com a bolinha de status **amarela**.
2. Copie o **SKU** do produto (primeira coluna). Precisa ser o SKU, não outro código.
3. Na Bagy, abra o mesmo produto.
4. Vá na aba **EXTRAS**, cole o SKU no campo **ID externo** e clique em **Salvar**.
5. Volte à Phibo, selecione o produto e clique em **Vincular produto no e-commerce**.
6. Confira as variações. Se uma variação da Phibo não for encontrada na Bagy, indique qual variação corresponde a ela.
7. Clique em **Vincular** e confirme em **Sim**.
8. Quando o status ficar **verde**, o produto está vinculado e passa a se atualizar.

{% hint style="warning" %}
Não coloque o SKU no campo de código SKU da Bagy. Ele deve ir no campo **ID externo**, dentro da aba **EXTRAS**. Sem isso, a Phibo não encontra o produto no site.
{% endhint %}

## Entendendo a tela

* **Cadastrar produto no e-commerce:** envia para a Bagy um produto que está só na Phibo.
* **Vincular produto no e-commerce:** conecta um produto que já existe nos dois lugares.
* **Quantidade do e-commerce:** se essa opção estiver ativa, você pode separar uma quantidade para a loja física e outra para o e-commerce.

{% hint style="warning" %}
O ideal é cadastrar os produtos sempre primeiro na Phibo (manualmente ou por XML) e depois enviá-los para a Bagy. A vinculação dá mais trabalho e deve ser usada só quando o produto foi cadastrado nos dois lugares. Se houver produtos duplicados com o mesmo nome, a vinculação pode apresentar erros.
{% endhint %}

## 🎬 Vídeo

{% embed url="<https://www.loom.com/share/72c66883a88d43dfb9777cd79be22598?sid=313a0164-f758-4e82-8f1d-cf18887d1e47>" %}

---

*🔎 Também procurado como: loja virtual, site, e-commerce, marketplace, produto, peça, cadastro de produto, grade, tamanho.*
