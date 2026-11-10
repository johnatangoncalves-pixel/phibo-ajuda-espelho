---
description: "Emissão de NF-e modelo 55 com finalidade de devolver mercadorias para o fornecedor."
tags:
  - tag: nota-fiscal
    primary: true
  - troca-devolucao
  - compras
---

# Como emitir nota de devolução ao fornecedor, troca ou remessa para conserto (NF-e)

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar. Artigo unificado:** substitui “Como emitir uma nota fiscal de devolução para fornecedor no Phibo” (https://ajuda.phibo.site/sobre-o-sitema/fiscal/como-emitir-uma-nota-fiscal-de-devolucao-para-fornecedor-no-phibo).
{% endhint %}

Assista o vídeo abaixo e aprenda como:

{% embed url="<https://www.loom.com/share/dfc0025b8fc24e8d9546ad29c05f2121>" %}

{% hint style="success" %}
Esse mesmo processo será realizado para emitir notas de troca para fornecedor e remessa para conserto, basta alterar o campo "natureza da operação"
{% endhint %}

Veja também esse passo a passo completo descrito abaixo

1- Acesse a tela **COMPRAS > GESTAO DE ESTOQUE > DEVOLUÇÃO DE MERCADORIA**

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FvAGPMydiHdi3ow9Epy6m%2Fimage.png?alt=media&amp;token=c82e6d24-622e-4553-b9c7-c162c40c2105" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
IMPORTANTE: Se essa opção não estiver aparecendo para você, significa que o módulo fiscal ainda não está ativo na sua conta, será necessário entrar em contato com o suporte para realizar habilitação fiscal.
{% endhint %}

2 - Preencha o Fornecedor e a Natureza da Operação ( se será uma NF-e de devolução, troca ou conserto). Em seguida clique na lupa para selecionar as notas fiscais de origem dos produtos.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2F5XCIWXt6X4oIvWtWLe6A%2Fimage.png?alt=media&amp;token=e452eb32-391e-4479-aa28-d7397e0b0348" alt=""><figcaption></figcaption></figure>

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FHj0A9UNKvSlh7kWROtsf%2Fimage.png?alt=media&amp;token=8c778060-34d9-4424-827a-96d293108f11" alt=""><figcaption><p>CLIQUE NA LUPA PARA SELECIONAR AS NOTAS QUE DESEJA DEVOLVER</p></figcaption></figure>

{% hint style="info" %}
Para emitir uma nota de natureza ***devolução de mercadoria,*** é imprescindível que os produtos tenham sido cadastrados no sistema via xml. Se o seu produto foi cadastrado manualmente, será necessário buscar o xml dessa NF, inserir e validar os produtos  para realizar a devolução.
{% endhint %}

3 - Feito isso, clique na aba ITEM DA DEVOLUÇÃO e em seguida na lupa para selecionar os produtos que serão devolvidos.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FI4udO3QHknpZhgBJdotk%2Fimage.png?alt=media&amp;token=44adf28f-9115-47ad-9c09-b6af8ca7228a" alt=""><figcaption><p>DEFINA NO CAMPO <strong>QUANTIDADE</strong> QUANTOS PRODUTOS ESTÃO SENDO DEVOLVIDOS DAQUELE MESMO CÓDIGO. SE SÃO 3 BLUSAS IGUAIS (COM O MESMO CÓDIGO DE BARRAS) APAGUE O NÚMERO 1, ESCREVA 3 E SÓ DEPOIS SELECIONE O PRODUTO.</p></figcaption></figure>

4 - Depois de selecionar todos os produtos, clique na aba TRANSPORTE e defina a forma de frete:

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2F4Nap53e4EnSPg54nIGYG%2Fimage.png?alt=media&amp;token=e7caa784-f4df-4943-8b98-6cbfc72becb6" alt=""><figcaption><p>LEIA ATENTAMENTE AS OPÇÕES E, CASO ENVIO NÃO SEJA FEITO POR CORREIOS E NEM TRANSPORTADORA, BASTA PREENCHER <em><strong>"SEM FRETE"</strong></em></p></figcaption></figure>

{% hint style="warning" %}
**IMPORTANTE ! Se a forma de frete for via TRANSPORTADORA você precisará preencher a Razão Social, CNPJ, Endereço e Inscrição Estadual daquela transportadora**
{% endhint %}

{% hint style="danger" %}
É obrigatório informar o peso das mercadorias (o não preenchimento poderá acarretar multa). Caso o seu fornecedor não tenha informado, coloque um peso aproximado em KG, ou seja, se o peso for 200 gramas, preencha 0,200.
{% endhint %}

5 - Feito isso, clique no botão "GERAR E ENVIAR NFE", aguarde o processamento e clique em "LISTAR NFe EMITIDAS" para visualizar o Status da Nota emitida:

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FiDobREFsc0uUVpoRwpoy%2Fimage.png?alt=media&amp;token=43946cee-519c-4cc0-b00b-74dd6c68c2a0" alt=""><figcaption></figcaption></figure>

6 - Aí basta consultar se o status da NF-e está como "EMITIDA" e clicar no ícone da NF para salvar em PDF

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FDXPahk5aX2Xr4NJNsTyO%2Fimage.png?alt=media&amp;token=52ff91d9-8f33-4878-8824-ee847e9aea51" alt=""><figcaption><p>PARA SALVAR EM PDF CLIQUE NO ÍCONE INDICADO NA IMAGEM, FEITO ISSO, UMA NOVA JANELA VAI APARECER, ENTÃO BASTA CLICAR SOBRE O MESMO ÍCONE NOVAMENTE E SALVAR O PDF. </p></figcaption></figure>

 Prontinho! Nota fiscal emitida com sucesso! :tada:

{% hint style="info" %}
Caso a nota fiscal fique pendente, uma seta cinza aparecerá no lugar onde deveria estar o ícone para salvar em PDF. Mas não se preocupe, basta chamar o suporte que te ajudaremos a reprocessá-la.
{% endhint %}

---

*🔎 Também procurado como: nota fiscal, NF, NFC-e, NF-e, cupom fiscal, troca, devolução, trocar peça, devolver, compra, fornecedor, nota de entrada, mercadoria.*
