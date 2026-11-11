---
tags:
  - tag: maquininha
    primary: true
  - vendas
---

# Como usar a maquininha integrada (TEF)

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar:** texto escrito a partir do vídeo. Conferir na tela do sistema os trechos marcados [confirmar na tela].
{% endhint %}

O TEF (Transferência Eletrônica de Fundos) conecta sua maquininha ao sistema Phibo, para que os pagamentos em cartão e PIX aconteçam de forma automática na venda.

{% hint style="info" %}
**Antes de começar:** o TEF precisa ser contratado com a provedora (SiTef) [confirmar na tela] e parametrizado pelo suporte. Avise se quer TEF no cartão, no PIX ou nos dois, pois são processos diferentes. As telas abaixo só aparecem depois da ativação.
{% endhint %}

{% hint style="warning" %}
O TEF ainda não é obrigatório em todos os estados. Se for no seu, o seu contador vai avisar.
{% endhint %}

## Passo a passo

### Fazer uma venda com TEF

1. Acesse **VENDAS > PDV > REGISTRAR VENDA**, selecione o vendedor e o cliente.
2. Se a venda não for presencial (por telefone ou WhatsApp), marque o ícone **venda não presencial**. Nesse caso, o cliente precisa ter CPF e endereço preenchidos.
3. Adicione os produtos e clique em **EFETUAR RECEBIMENTO**.
4. Escolha a forma de pagamento:
   * **PIX via TEF:** conclua a venda e o QR Code aparece na maquininha.
   * **Crédito ou débito:** selecione a maquininha cadastrada como TEF e informe só o número de parcelas (a bandeira não é pedida).
5. Clique em **Concluir**, confira os dados e clique em **Iniciar pagamento** [confirmar na tela]. Peça ao cliente para passar o cartão.
6. Com a transação aprovada, clique em **Finalizar**. A nota fiscal é emitida com a autorização do cartão vinculada no XML.

### Acompanhar as vendas

1. Acesse **VENDAS > CONSULTA VENDAS > VENDAS COM TEF**.
2. Confira o status. O correto é **Finalizado**.

### Fazer um estorno

1. Em **VENDAS > RELAÇÃO DE VENDAS**, exclua a venda. Se estiver no prazo, a nota fiscal é cancelada.
2. Volte em **VENDAS > CONSULTA VENDAS > VENDAS COM TEF** e abra a venda com status excluído.
3. Clique no ícone de estorno [confirmar na tela], informe o código do supervisor e passe o cartão físico do cliente.

### Venda pendente ou cancelada

1. Se a transação falhar ou for cancelada, a venda fica em **VENDAS COM TEF** e não vai para a relação de vendas.
2. Clique no ícone de **maquininha** ao lado da lixeira para tentar de novo, trocar a forma de pagamento ou excluir a venda.

{% hint style="warning" %}
Enquanto a venda com TEF estiver pendente, a nota fiscal também fica pendente.
{% endhint %}

### Reimprimir o comprovante

1. Em **VENDAS > CONSULTA VENDAS > VENDAS COM TEF**, clique no ícone de **impressora** da venda. Isso reimprime o comprovante do TEF, não o cupom da venda.

## 🎬 Vídeo

Assista o vídeo para ver detalhadamente como utilizar o TEF no sistema:

{% hint style="danger" %}
ATENÇÃO: Para registrar vendas com a integração TEF é necessário habilitar o módulo fiscal primeiro! Se você ainda não emite notas, basta chamar o suporte e solicitar a habilitação fiscal.
{% endhint %}

{% embed url="<https://www.loom.com/share/ac33aa7622c5415dab4889a1eb047561?sid=be46adfd-13f5-449b-9379-fec0f52bfa10>" %}

---

*🔎 Também procurado como: máquina de cartão, maquininha, cartão de crédito, cartão de débito, TEF, venda, vender, PDV, frente de caixa.*
