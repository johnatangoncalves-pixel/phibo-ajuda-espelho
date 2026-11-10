---
tags:
  - tag: impressora
    primary: true
  - erros
---

# Como corrigir erros na impressora de cupom

Este guia foi desenvolvido para ajudá-lo a resolver problemas de impressão em sua impressora térmica de cupons. Se você concluiu uma venda e o comprovante não foi emitido, ou se recebeu a mensagem de que a <mark style="background-color:$warning;">**"central de impressão está desativada"**</mark>, siga rigorosamente as etapas abaixo.

**Assista o vídeo abaixo para ver detalhadamente como resolver o problema:**

{% embed url="<https://www.loom.com/share/6969bd3494174bda8eec874f5a532079>" %}

<mark style="background-color:yellow;">**Etapa 1: Diagnóstico da Impressora no Windows**</mark>

O primeiro passo é isolar o problema. Precisamos saber se o Windows está conseguindo se comunicar com a impressora, independentemente do sistema Phibo.

#### **1.1  - Localizando a Impressora**

Pressione a tecla com a bandeira do Windows no seu teclado ou clique no botão Iniciar. Na barra de pesquisa, digite a palavra "impressora".

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FMSuRuH4HP1thTRyNi26r%2Fimage.png?alt=media&amp;token=55456ef9-e248-4f54-9ee8-5d16194b8995" alt=""><figcaption></figcaption></figure>

Clique na opção "**Abrir**" ou diretamente no nome "**Impressoras e scanners**".

#### **1.2 Realizando o Teste de Impressão (Interface Moderna)**

Se você estiver no Windows 11, localize sua impressora térmica (ex: Epson TM-T20). Clique sobre ela e procure o botão "**Imprimir página de teste**".

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2Fdpp9er4FmJ2We0OSbP0a%2Fimage.png?alt=media&amp;token=d098adc9-dcda-4b3e-8dfa-2633282f8cd9" alt=""><figcaption></figcaption></figure>

1.3 Realizando o Teste (Interface Clássica/Painel de Controle)

Caso prefira ou esteja em uma versão anterior do Windows:

Vá em "**Dispositivos e Impressoras**" no Painel de Controle.

Localize o ícone da sua impressora de cupom.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FbHFuvjO43iZsxNcXkBIr%2Fimage.png?alt=media&amp;token=abf69d06-33cb-4e40-b3c5-cff372f4144c" alt=""><figcaption></figcaption></figure>

Clique com o botão direito do mouse sobre ela e selecione "**Propriedades da impressora**".

Na aba "Geral", clique no botão "**Imprimir página de teste**".

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FG7Qc6Hpw8c6YDAfpLbNW%2Fimage.png?alt=media&amp;token=f36a383a-2276-400a-b265-55b35c65718d" alt=""><figcaption></figcaption></figure>

<mark style="background-color:$success;">**Resultado Esperado:**</mark>**Se a impressora emitir o papel de teste, a comunicação física e o driver estão perfeitos. Prossiga para a Etapa 2.**

<mark style="background-color:yellow;">Etapa 2: Verificação do Serviço de Impressão (Phibo Bot)</mark>

O PhiboBoot é o "tradutor" que recebe as vendas do sistema e as entrega para a impressora do Windows. Ele precisa estar sempre "vivo" e em execução.

#### **2.1 Verificando a Bandeja do Sistema**

Ao lado do relógio do Windows, clique na setinha para cima. Procure por um ícone azul discreto de uma impressora chamado Phibo Bot:

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FydzBFv21qHTh9bhBvGpj%2Fimage.png?alt=media&amp;token=c0f6b25b-0a3e-40e0-8e46-8bb4622f26b7" alt=""><figcaption></figcaption></figure>

#### **2.2 Ativando o Serviço**

Se o ícone não estiver lá, Vá até a sua Área de Trabalho (Desktop).

Localize o atalho do Phibo Bot e dê um duplo clique.

Aguarde cerca de um minuto. Uma notificação aparecerá confirmando: "**Boot de impressão 1.8 em execução**".

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FO9uTDJeK2qNJn8dxchvG%2Fimage.png?alt=media&amp;token=a34cb5be-e840-42be-9676-5ade6db7b3c5" alt=""><figcaption></figcaption></figure>

<mark style="background-color:yellow;">Etapa 3: Parametrização no Sistema Phibo</mark>

Agora que a impressora e o serviço estão funcionando, precisamos garantir que o sistema Phibo saiba para qual impressora enviar os cupons.

#### 3.1 Acessando a Gestão de Impressão

Dentro do sistema Phibo, siga o caminho: **Início > Configurar Módulos > Gestão de Impressão**.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FN3LkmEX3QqDHu4uRtflQ%2Fimage.png?alt=media&amp;token=658a4198-479f-409a-be3f-e21cfdb96ee9" alt=""><figcaption></figcaption></figure>

#### 3.2 Verificando o Status

Clique em "**Status da central de impressão**". Se o PhiboBoot estiver ativo (Etapa 2), o status aqui aparecerá como "Ativa".

#### 3.3 Configurando o Nome da Impressora

Clique em **"Impressoras Configuradas"**.

Localize o campo destinado à Impressora de Cupom (Térmica).

O nome escrito aqui deve ser exatamente igual ao nome que aparece no Windows (visto na Etapa 1). Dica: Use copiar e colar para evitar erros de digitação.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FUPPS7BvL7VBL4LMzjmf5%2Fimage.png?alt=media&amp;token=2aeb73e0-0d44-4265-a9a3-0876260e63ed" alt=""><figcaption></figcaption></figure>

#### 3.4 Impressão Automática vs. Manual

•        **Automática**: Marque a opção de impressão automática se desejar que o cupom saia assim que a venda for concluída (estilo shopping).

•        **Manual**: Desmarque se preferir escolher o que e quando imprimir.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2F1kPIak3uoYEcDTTI6XFw%2Fimage.png?alt=media&amp;token=535d1417-d66f-4e85-8571-cb08846ed0d5" alt=""><figcaption></figcaption></figure>

**IMPORTANTE**: Após qualquer alteração, clique sempre no botão "**Salvar**".

<mark style="background-color:yellow;">Teste Final: Imprimindo um Comprovante de Venda</mark>

Para testar se tudo deu certo:

Vá na sua lista de vendas concluídas (**VENDAS > RELAÇÃO DE VENDAS**).

Localize a venda desejada e clique no ícone da impressora ou da folhinha:

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2Fyq8q0VpxdDUxDHVV3Nfh%2Fimage.png?alt=media&amp;token=2f7b9de0-13bc-4c38-86d1-38ec07415174" alt=""><figcaption></figcaption></figure>

A impressora deverá emitir o barulho característico e o cupom sairá imediatamente.

{% hint style="info" %}
**Ainda com problemas?** Se mesmo após seguir todos os passos a impressão não sair, entre em contato com nosso suporte especializado. Escolha a **Opção 3 (Impressoras)** no nosso canal de atendimento. Nossos especialistas estão prontos para realizar uma configuração avançada para você.
{% endhint %}

---

*🔎 Também procurado como: impressora não imprime, cupom não sai, impressora térmica, impressora, imprimir, impressão, erro, problema, não funciona.*
