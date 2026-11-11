---
tags:
  - tag: phibozap
    primary: true
  - whatsapp
  - crediario
---

# Como enviar o comprovante de pagamento de parcela no crediário pelo PhiboZap

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar:** texto escrito a partir do vídeo. Conferir na tela do sistema os trechos marcados [confirmar na tela].
{% endhint %}

Configure o PhiboZap para enviar ao cliente, pelo WhatsApp, o comprovante de pagamento de cada parcela do crediário que você receber.

{% hint style="info" %}
**Antes de começar:** o cliente precisa ter o telefone correto no cadastro. Sem isso, ele não recebe nada.
{% endhint %}

## Passo a passo

### 1. Criar a mensagem

1. Acesse **INÍCIO > PHIBOZAP** e vá em **Mensagens**.
2. Clique em **Nova mensagem**, dê um nome (ex.: "Comprovante") e escolha o tipo **Eventual**.
3. Clique em **Salvar**.
4. Clique em **Adicionar**, escolha **Texto** e escreva a mensagem. Para incluir o nome do cliente, use a variável de nome `%xnome%` [confirmar na tela].
5. Volte para a tela anterior.

Não é preciso criar lista alvo: o próprio sistema define quem recebe, conforme os pagamentos.

### 2. Criar ou conferir a campanha

Normalmente a campanha **Comprovante de pagamento** já vem criada. Se não existir:

1. Vá em **Campanhas > Nova campanha** e dê um nome.
2. Em **Tipo de campanha**, escolha **Eventual**.
3. Selecione a mensagem que você criou e o evento **Comprovante de pagamento**.
4. Defina o envio:
   * **Botão verde (ativado):** o comprovante é enviado automaticamente ao concluir o recebimento.
   * **Botão vermelho (desativado):** você escolhe na hora se envia ou não.
5. Clique em **Salvar**.

### 3. Receber a parcela e enviar

1. Acesse **VENDAS > CREDIÁRIO > EFETUAR RECEBIMENTO** [confirmar na tela] e busque o cliente.
2. Selecione a parcela, informe a forma de pagamento (no PIX, a conta bancária), clique em **Receber** e confirme.
3. Se o envio automático estiver ativo, o cliente já recebe o comprovante.
4. Se estiver desativado, clique no ícone das **duas folhinhas** e depois no ícone do **WhatsApp** para enviar.

{% hint style="info" %}
Mensagens de cupom (comprovante de pagamento, cupom de venda, romaneio de bag) são sempre do tipo **Eventual**, porque só acontecem quando há aquela ação.
{% endhint %}

## 🎬 Vídeo

Veja abaixo o tutorial completo de como criar uma campanha no PhiboZap para automatizar o envio do comprovante de pagamento de uma parcela de crediário (realizado na tela **VENDAS > CREDIARIO > EFETUAR RECEBIMENTO**):

{% embed url="<https://www.loom.com/share/7301ddd9e78b4fd39e58e1ba02f1a3ba?sid=c8d42ecc-c379-46d7-be5b-5d0146584f11>" %}

---

*🔎 Também procurado como: PhiboZap, mensagem automática, disparo em massa, WhatsApp, Zap, mensagem, crediário, carnê, parcela, fiado.*
