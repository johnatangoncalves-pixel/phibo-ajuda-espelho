---
tags:
  - tag: migracao
    primary: true
  - primeiros-passos
  - clientes
---

# Importação de clientes (outro sistema)

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar:** texto escrito a partir do vídeo. Conferir na tela do sistema os trechos marcados [confirmar na tela].
{% endhint %}

Use a importação de clientes para cadastrar de uma vez a lista de clientes que você trouxe de outro sistema para a Phibo.

{% hint style="info" %}
**Antes de começar:** tenha em mãos a planilha modelo de importação e leia as regras da tela de importação, que mostram o formato de cada coluna.
{% endhint %}

{% hint style="warning" %}
A tela de importação fica aberta até por volta das 11h30 e é liberada novamente às 19h10. Programe-se: depois das 19h10 não há suporte.
{% endhint %}

## Passo a passo

### Parte 1: preparar a planilha

1. Acesse **INÍCIO > GESTÃO DE DADOS > CLIENTES > IMPORTAR DADOS** e clique no ícone de **+** para ver todas as regras de cada campo [confirmar na tela].
2. Abra a planilha modelo. As colunas em **vermelho** são obrigatórias: nenhuma célula delas pode ficar vazia, do início ao fim da lista.
3. Apague os dados de exemplo e cole os dados dos seus clientes nas colunas correspondentes.
4. **Código do cliente:** se não tiver, crie uma sequência (1, 2, 3...).
5. **Data de cadastro:** use a data real ou qualquer data, no formato indicado nas regras [confirmar na tela].
6. **Celular:** 11 dígitos, sem repetir. Para clientes sem telefone, crie números fictícios diferentes entre si.
7. **Gênero:** preencha M ou F para todos os clientes.
8. **Aniversário:** informe dia e mês em colunas separadas. Para quem não tem data, use uma data que não existe (ex.: 30/02) [confirmar na tela], para que o sistema não envie avisos.
9. **E-mail:** é opcional, mas, se informado, precisa ser válido (com @ e domínio) e não pode se repetir.
10. **Status:** preencha somente **S**, sem espaços. Com espaço, o cliente entra como desativado.
11. **Tipo de pessoa:** 1 para pessoa física e 0 para pessoa jurídica [confirmar na tela].
12. **CPF/CNPJ:** sem pontos, traços, barras ou espaços, com 11 dígitos (CPF) ou 14 (CNPJ). Confira o zero à esquerda e se não há duplicados.
13. **CEP:** no formato mostrado no arquivo de regras [confirmar na tela]. O CEP precisa existir. Para CEP geral (terminado em 000), preencha o logradouro.
14. Preencha número, complemento, bairro, UF e cidade.
15. Ordene a planilha de A a Z e apague a linha de títulos.

### Parte 2: salvar e importar

1. No Excel, salve como **CSV (separado por vírgulas)**. O arquivo gerado já usa ponto e vírgula entre as colunas, que é o formato correto.
2. No Google Planilhas, baixe como **valores separados por vírgula**, abra o arquivo no Bloco de Notas e substitua todas as vírgulas por ponto e vírgula.
3. Volte em **IMPORTAR DADOS**, clique em **Arquivo**, escolha o CSV e clique em **Carregar**.

4. Se aparecer erro em uma linha, as linhas anteriores já foram importadas. Corrija a linha, apague as já importadas e carregue de novo.
5. Se carregar por mais de 5 minutos, recarregue a página e confira o último cliente importado.

## 🎬 Vídeo

Para importar os contatos dos clientes do seu sistema anterior para o sistema Phibo assista atentamente o passo a passo abaixo:

{% embed url="<https://www.loom.com/share/82f234c6ceec434786150957521f12b7?sid=0bc7495e-311b-40fd-9383-34ceca4f67d8>" %}

{% hint style="info" %}
Clique no ícone abaixo para fazer o dowload da planilha modelo de importação de clientes:
{% endhint %}

{% file src="/files/UCQoqYQOsL31qP8M9fnJ" %}

---

*🔎 Também procurado como: migração, importar dados, planilha, outro sistema, começar, implantação, treinamento, cliente, cadastro de cliente.*
