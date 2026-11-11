---
description: "Esse método de cadastro é indicado para clientes que utilizam a etiqueta pré-impressa e necessitam cadastrar cada tamanho com um código de barras diferente."
tags:
  - tag: produtos
    primary: true
  - etiquetas
  - clientes
---

# Como cadastrar o mesmo produto com códigos de barras (EAN) diferentes por tamanho

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar:** texto escrito a partir do vídeo. Conferir na tela do sistema os trechos marcados [confirmar na tela].
{% endhint %}

Este procedimento é útil para quem usa etiquetas pré-impressas: ele permite ter peças com o mesmo código do produto, tamanho e cor, mas com códigos de barras (EAN) diferentes.

{% hint style="info" %}
**Por que é preciso fazer assim?** Dentro de um mesmo produto, o sistema não aceita duas variações com o mesmo tamanho e a mesma cor. Por isso, você cadastra com cores provisórias, separa as variações e depois corrige a cor.
{% endhint %}

## Passo a passo

### Parte 1: Cadastrar as variações com cor provisória

1. Acesse **COMPRAS > GESTÃO DE ESTOQUE > CADASTRAR PRODUTO NOVO**.
2. Edite o produto (ou cadastre um novo).
3. Adicione uma nova variação com o mesmo tamanho, mas escolha outra cor (provisória).
4. Gere o código de barras e clique em **Salvar**.
5. Repita para cada peça, sempre com uma cor provisória diferente.

### Parte 2: Separar as variações

1. Marque o produto no ícone de seleção.
2. Clique em **Ações > Alteração em lote**.
3. Remova as variações provisórias e deixe só uma.
4. Informe o mesmo código do produto e a mesma descrição e salve [confirmar na tela].
5. Repita até que cada variação vire um produto separado, todos com o mesmo código do produto.

### Parte 3: Corrigir a cor

1. Clique no ícone de edição de cada produto separado.
2. Troque a cor provisória pela cor correta. Você pode digitar parte do nome (ex.: "azul") para filtrar as cores.
3. O sistema mostra um alerta, mas permite salvar. Clique em **Salvar**.

Pronto: as peças ficam com o mesmo código do produto, tamanho e cor, cada uma com um código de barras diferente.

## Entendendo o resultado

* **Na busca:** ao pesquisar pelo código do produto, as peças aparecem tanto na lista de produtos quanto no PDV (**VENDAS > PDV REGISTRAR VENDA**, clicando na lupa).
* **Produtos de XML:** depois de validados, eles vão para **CADASTRAR PRODUTO NOVO**, e o processo é o mesmo.

## 🎬 Vídeo

Esse método de cadastro é indicado para clientes que utilizam a etiqueta pré-impressa e necessitam cadastrar cada tamanho com um código de barras diferente.

Veja abaixo o vídeo com demonstrativo de como realizar esse cadastro:

{% embed url="<https://www.loom.com/share/8946d11eed454fb3878a5d26ab4688f9?sid=4eece7c7-22b3-4a08-90da-b23733a9f95c>" %}

---

*🔎 Também procurado como: produto, peça, cadastro de produto, grade, tamanho, etiqueta, etiqueta de preço, código de barras, cliente, cadastro de cliente.*
