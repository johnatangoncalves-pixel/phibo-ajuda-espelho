---
tags:
  - tag: nota-fiscal
    primary: true
  - erros
---

# O que fazer quando a nota é rejeitada

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar:** artigo novo escrito a partir do conteúdo existente da Central. Conferir com o suporte os pontos marcados [confirmar com o suporte].
{% endhint %}

Quando a Secretaria da Fazenda do seu estado (Sefaz) recusa uma nota, ela **não é emitida**. O Phibo mostra uma mensagem com um **código** e a **descrição do problema**. Na maioria das vezes, basta corrigir o dado indicado e emitir de novo.

## Passo a passo

1. **Leia a mensagem com calma.** Anote o código e o texto da rejeição (ou tire um print da tela).
2. **Veja de que tipo é o problema**, pela lista abaixo, e abra o artigo indicado.
3. **Corrija o dado** e tente emitir a nota novamente.
4. Se a mensagem continuar aparecendo, fale com o suporte e envie o print da rejeição.

## Problemas mais comuns

| A mensagem fala de… | O que verificar | Artigo |
|---|---|---|
| Certificado digital (vencido, inválido, senha) | Se o certificado está dentro da validade e cadastrado corretamente | [Como cadastrar o certificado digital](../configuracao-fiscal/como-incluir-o-certificado-digital.md) |
| Dados do cliente (CPF/CNPJ, endereço, CEP) | O cadastro do cliente da venda | [Como editar ou excluir um cliente](../../clientes/cadastro-de-clientes/como-editar-ou-excluir-um-cliente.md) |
| Numeração da nota (duplicidade, número já usado) | Se a numeração pulou ou se a nota já foi emitida | [Como inutilizar uma nota que não foi emitida](../corrigir-cancelar-e-inutilizar/como-inutilizar-uma-nota-fiscal.md) |
| Credenciamento / emissor não autorizado | Lojas do Paraná precisam liberar o emissor na Sefaz | [Lojas do Paraná: como liberar a emissão de notas na Sefaz](../configuracao-fiscal/como-fazer-o-credenciamento-na-sefaz-do-parana.md) |
| Formato do certificado (.p12) | Converter o arquivo para .pfx | [Como converter o certificado digital para o formato aceito (P12 → PFX)](../configuracao-fiscal/como-converter-o-certificado-digital-de-p12-para-pfx.md) |

{% hint style="info" %}
Se a Sefaz estiver fora do ar, a nota pode ser recusada mesmo com tudo certo. Aguarde alguns minutos e tente de novo. [confirmar com o suporte: como o Phibo trata emissão em contingência]
{% endhint %}

## Ainda com dúvida?

[Fale com o suporte pelo WhatsApp](https://wa.me/553171591121) e envie o print da mensagem de rejeição.

---

*🔎 Também procurado como: nota fiscal, NF, NFC-e, NF-e, cupom fiscal, erro, problema, não funciona.*
