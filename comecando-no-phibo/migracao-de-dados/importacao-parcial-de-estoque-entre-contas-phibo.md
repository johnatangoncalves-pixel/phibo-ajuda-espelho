---
tags:
  - tag: migracao
    primary: true
  - primeiros-passos
  - estoque
---

# Importação parcial de estoque entre contas Phibo

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar:** texto escrito a partir do vídeo. Conferir na tela do sistema os trechos marcados [confirmar na tela].
{% endhint %}

Use este processo para levar produtos cadastrados recentemente de uma conta Phibo para outra, por exemplo quando matriz e filial compram juntas e uma mesma nota (XML) é dividida entre as lojas.

{% hint style="info" %}
**Antes de começar:**
* Abra cada conta Phibo em um navegador diferente. No mesmo navegador, as informações se misturam.
* Saiba a data (ou o intervalo de datas) em que os produtos foram cadastrados.
{% endhint %}

{% hint style="warning" %}
Esta migração funciona só para os últimos produtos cadastrados, não para o estoque inteiro.
{% endhint %}

## Passo a passo

### Na conta de origem

1. Acesse **COMPRAS > GESTÃO DE ESTOQUE > LISTAR PRODUTOS**.
2. Use o filtro **Foram cadastrados em** e informe a data ou o intervalo do cadastro.
3. Confira os fornecedores. Fornecedor sem CNPJ não pode ser exportado: em **Cadastrar fornecedor**, edite-o e coloque um número fácil de reconhecer como inventado (ex.: 11222222...).
4. Clique no botão verde **Exportar dados padrão de gestão de dados**. A outra exportação em Excel não traz todos os dados necessários.

### Na planilha

1. Mude as colunas de código (como o código de barras) de **Geral** para **Número**, para corrigir valores em formato exponencial (com "E+").
2. Exclua a coluna **SKU**.
3. Na coluna **Cor hexa**, use **Limpar conteúdo** (não exclua a coluna).
4. Troque os CNPJs de fornecedor inventados pelo nome do fornecedor e replique para as demais linhas [confirmar na tela]. CNPJ diferente do registrado na Receita Federal não carrega.
5. Ajuste as quantidades para o que vai para a outra loja. Não pode haver quantidade negativa: troque por zero.
6. Exclua a linha 1 (cabeçalho).
7. Clique em **Arquivo > Salvar como** e escolha o tipo **CSV UTF-8**, para que acentos e cedilha sejam aceitos.

### Na conta de destino

1. Acesse **INÍCIO > GESTÃO DADOS > ESTOQUE > IMPORTAR DADOS**.
2. Selecione o arquivo e clique em **Validar**. Se houver erro, abra o relatório para ver o que corrigir.
3. Clique em **Confirmar carga do arquivo**.
4. Acompanhe em **Gestão de importação**: o arquivo fica **pendente** até ser processado e fica verde como **concluído** quando terminar.

{% hint style="warning" %}
* O estoque não entra na hora: pode levar até as 8h do dia seguinte.
* Só é possível importar uma planilha de estoque por dia. Cadastre o máximo de produtos antes de migrar.
* A importação e a exportação ficam disponíveis das 19h15 até as 12h30 do dia seguinte.
{% endhint %}

## 🎬 Vídeo

Assista atentamente o tutorial abaixo para realizar a importação em massa  de alguns itens do estoque de uma conta Phibo para outra conta Phibo :

{% embed url="<https://www.loom.com/share/56aa9f1de64e45ac8a90d80a26915bcf?sid=94653d5b-2584-4564-a99f-75e12cd81b8f>" %}

---

*🔎 Também procurado como: migração, importar dados, planilha, outro sistema, começar, implantação, treinamento, estoque, inventário, contagem, saldo de peças.*
