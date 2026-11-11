---
tags:
  - tag: migracao
    primary: true
  - primeiros-passos
  - estoque
---

# Importação total de estoque entre contas Phibo

Use este processo para levar todo o estoque de uma conta Phibo para outra conta Phibo.

{% hint style="warning" %}
* A exportação só funciona das 19h10 até as 12h30 do dia seguinte. Fora desse horário, ela fica bloqueada.
* Todos os fornecedores precisam ter CNPJ. Se faltar algum, o sistema avisa e não exporta.
{% endhint %}

## Passo a passo

### Na conta de origem

1. Acesse **Cadastrar fornecedor > Editar** e confira os fornecedores sem CNPJ.
2. Para cada um, tente primeiro excluir: se ele não tiver produtos, o sistema deixa excluir. Se não deixar, edite e coloque um CNPJ fictício (ex.: 123123...) e salve.
3. Acesse **GESTÃO DE DADOS > ESTOQUE > EXPORTAR DADOS**.
4. Exporte a primeira planilha, com os produtos de quantidade **maior que zero**.
5. Para levar também os produtos zerados e negativos, filtre por **igual a zero**, clique em **Aplicar filtro** e **Exportar dados**. Depois faça o mesmo com **menor que zero**.

### Na planilha

1. Junte as planilhas em uma só: copie as linhas das outras (sem o cabeçalho) e cole no final da primeira. O sistema aceita apenas um arquivo.
2. Nas colunas de código que aparecem em formato exponencial (com "E+"), clique com o botão direito, vá em **Formatar células > Personalizado** e use **0**.
3. Confira a coluna de unidades: ela aceita no máximo 3 caracteres (ex.: troque "pares" por "par").
4. Exclua a coluna **SKU**.
5. Na coluna **Cor hexa**, use **Limpar conteúdo** (não exclua a coluna, ela faz parte do modelo).
6. Corrija os CNPJs fictícios: em **Cadastrar fornecedor > Listar**, localize cada CNPJ da planilha, copie o nome do fornecedor e cole no lugar do CNPJ em todas as linhas dele (use o filtro para facilitar).
7. Exclua a linha do cabeçalho.
8. Clique em **Salvar como** e troque o tipo para **CSV UTF-8**.

### Na conta de destino

1. Acesse **GESTÃO DE DADOS > ESTOQUE > IMPORTAR DADOS** e envie a planilha. A importação segue o mesmo processo da importação de estoque, explicado em um artigo próprio.

## 🎬 Vídeo

A importação total do estoque é usada para transmitir em massa todo o estoque de uma conta Phibo para outra conta Phibo.

Assista ao vídeo abaixo para ver o passo a passo completo de como realizar esse procedimento:

{% embed url="<https://www.loom.com/share/965990b3b3c84891a8df722dd5209445?sid=1e75f3a5-c693-43ad-b888-c9fdae33d614>" %}

---

*🔎 Também procurado como: migração, importar dados, planilha, outro sistema, começar, implantação, treinamento, estoque, inventário, contagem, saldo de peças.*
