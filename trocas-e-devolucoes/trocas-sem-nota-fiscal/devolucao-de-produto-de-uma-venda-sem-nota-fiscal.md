---
tags:
  - tag: troca-devolucao
    primary: true
  - vendas
  - nota-fiscal
  - produtos
---

# Devolução de produto de uma venda sem nota fiscal

{% hint style="info" %}
🔧 **Nota interna (D15) – remover antes de publicar:** conteúdo repetido com [Devolução de produto de uma venda com nota fiscal](../trocas-e-devolucoes-com-nota-fiscal/devolucao-de-produto-de-uma-venda-com-nota-fiscal.md). Juntar os dois e manter só um.
{% endhint %}

Caso o seu cliente devolva um produto adquirido e não tenha nenhuma NFE ou Cupom Fiscal emitido para ele, existem 3 tratativas que podem ser  realizadas  para registrar a devolução dessa mercadoria. Veja a seguir:

[#id-1a-situacao-o-cliente-esta-devolvendo-todos-os-produtos-da-compra](#id-1a-situacao-o-cliente-esta-devolvendo-todos-os-produtos-da-compra "mention")

[#id-2a-situacao-o-cliente-levou-varios-produtos-mas-esta-devolvendo-somente-uma-ou-algumas-pecas-e-vai-f](#id-2a-situacao-o-cliente-levou-varios-produtos-mas-esta-devolvendo-somente-uma-ou-algumas-pecas-e-vai-f "mention")

[#id-3-situacao-o-cliente-comprou-varias-produtos-e-esta-devolvendo-apenas-algumas-pecas-e-vai-pagar-no-c](#id-3-situacao-o-cliente-comprou-varias-produtos-e-esta-devolvendo-apenas-algumas-pecas-e-vai-pagar-no-c "mention")

1ª Situação: O cliente está devolvendo todos os produtos da compra.

Se o cliente estiver devolvendo todas as peças da venda,  basta excluir a venda que automaticamente as peças retornam pro seu estoque e  o movimento financeiro atrelado à essa transação é desfeito.

\
Para excluir a venda, basta fazer conforme o tutorial abaixo:\
\
[Como excluir uma venda no sistema Phibo ](https://youtu.be/EWc0sMKMFbE) 

2ª Situação: O cliente levou vários produtos, mas está devolvendo somente uma ou algumas peças e vai ficar com um crédito

{% hint style="warning" %}
ATENÇÃO: Essa alternativa seria para as vendas **sem** NF . Se a devolução é para uma venda que teve Nota/Cupom fiscal, deve ser feita conforme o seguinte tutorial: \
\
[Como Gerar Uma Nota De Devolução De Uma Venda](../trocas-e-devolucoes-com-nota-fiscal/como-gerar-uma-nota-de-devolucao-de-uma-venda.md)
{% endhint %}

Caso o seu cliente não esteja devolvendo todas as peças que ele comprou, você precisará fazer uma troca, porém utilizando o Produto Padrão na aba ITENS VENDA. Isso vai registrar no sistema o retorno da mercadoria devolvida, porém não vai registrar saída pra nenhuma de suas peças em estoque. \
\
Resumidamente, o Produto Padrão é o cadastro de um produto fictício. Ou seja, **ele existe somente no sistema** e não tem fisicamente no seu estoque e serve para testes ou situações que precise acrescentar valor na venda (como essa). Portanto, ao utilizá-lo, não causará diferença na quantidade de nenhuma de suas peças de verdade. 

Para registrar esse tipo de troca, onde o cliente não está levando nenhuma outra mercadoria, vá em **VENDAS > PDV**> selecione o botão TROCA: 

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2F4rbHqngyOYChVYGyL96q%2Ftroca%201.jpg?alt=media&amp;token=7623b7d0-8681-43d0-89ee-f6667d3c91c8" alt=""><figcaption></figcaption></figure>

Em seguida, coloque a(s) peça(s) que o cliente está devolvendo na aba ITENS DEVOLUÇÃO:

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FFcprFjNWYW4GnGP7ZV4V%2Ftroca%202.jpg?alt=media&amp;token=904005f4-541c-4461-bbfb-713535c91061" alt=""><figcaption></figcaption></figure>

E na aba ITENS VENDA, coloque o Produto Padrão. No campo INFORME O PRODUTO, Basta digitar "000" ou escrever a palavra "Padrão" e por o mesmo valor da soma dos produtos que estão sendo devolvidos (na exemplo acima, a soma deu R$ 258,00, portanto esse valor que será utilizado):

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FLjrv3JAQw1n2ZrEHcpbv%2Ftroca%203.jpg?alt=media&amp;token=5a7d24d8-db3d-4ea1-b99c-5527712fd7a9" alt=""><figcaption></figcaption></figure>

**Isso é feito para que o valor de venda abata o valor da devolução**, deixando zero no resultado pra poder finalizar a transação sem saída de nenhuma peça de verdade de seu estoque. \
Depois basta ir em EFETUAR RECEBIMENTO e clicar em CONCLUIR VENDA para finalizar.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FhTYPaXoZPAANxGgFGRBa%2Ftroca%204.jpg?alt=media&amp;token=62ab8d99-e769-40f8-9bbf-fa17b690a07b" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**IMPORTANTE**: Para finalizar a venda, é só clicar no botão CONCLUIR VENDA, não é necessário preencher nenhuma forma de pagamento.
{% endhint %}

Feito isso, basta criar um cupom de desconto para registrar o crédito do cliente. Quando ele voltar à loja, bastará informar o nome do cupom para aplicar o desconto sobre a venda. Veja abaixo o passo a passo de como criar um cupom de desconto

{% content-ref url="../../vendas-no-pdv/descontos-cupons-e-promocoes/como-configurar-e-usar-os-cupons-de-desconto-nas-vendas.md" %}
[Como configurar e usar os Cupons de Desconto nas vendas](../../vendas-no-pdv/descontos-cupons-e-promocoes/como-configurar-e-usar-os-cupons-de-desconto-nas-vendas.md)
{% endcontent-ref %}

3° Situação: O cliente comprou várias produtos e está devolvendo apenas algumas peças e vai pagar no crediário

Caso o cliente tenha comprado no crediário, nenhuma das opções acima te atenderá, pois elas não ajustarão o valor das parcelas devidas pelo cliente.

Para essas situações, o ideal é excluir a venda ( em **VENDAS > RELAÇÃO DE VENDAS > DIA DA VENDA** e clicar na lixeira) para que as parcelas em aberto sejam excluidas e lançar a venda novamente em **VENDAS > PDV REGISTRAR VENDA** incluindo apenas as peças que a cliente ficou.

---

*🔎 Também procurado como: troca, devolução, trocar peça, devolver, venda, vender, PDV, frente de caixa, nota fiscal, NF, NFC-e, NF-e, cupom fiscal, produto, peça, cadastro de produto.*
