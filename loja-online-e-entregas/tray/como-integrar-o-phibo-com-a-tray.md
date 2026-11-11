---
tags:
  - tag: loja-online
    primary: true
---

# Como integrar o Phibo com a Tray

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar:** texto escrito a partir do vídeo. Conferir na tela do sistema os trechos marcados [confirmar na tela].
{% endhint %}

{% hint style="warning" %}
🔧 **Nota interna – remover antes de publicar. Artigo unificado:** substitui “Como integrar o Phibo com a Tray (resumido)” (https://ajuda.phibo.site/sobre-o-sitema/integracao-tray/como-integrar-o-phibo-com-a-tray-resumido).
{% endhint %}

Integre sua loja na Tray com o Phibo para sincronizar produtos, estoque, preços, pedidos e clientes.

## Passo a passo

### Na Tray

1. Acesse **APLICATIVOS** e clique em **Instalar aplicativo** (botão azul à direita).
2. Pesquise por **Phibo**. Se não encontrar, pesquise por **sistema ERP**.
3. Clique em **Instalar**. O Phibo vai aparecer em **Meus aplicativos**.
4. Clique em **Acessar** e copie a **URL** exibida no topo.

### No Phibo

1. Acesse **INÍCIO > CONFIGURAR MÓDULOS > INTEGRAÇÕES**.
2. Clique em **Tray**.
3. No campo de URL, cole apenas a parte da URL que vem depois do traço após o ".br" [confirmar na tela]. Não use a parte "web api".
4. Preencha o campo **URL do canal de vendas** [confirmar na tela].
5. Clique em **Autenticar** e autorize o acesso do sistema ao site.
6. Deixe a opção de integração ativa (em verde) e clique em **Testar conexão**. A mensagem deve indicar que a loja está conectada.

{% hint style="warning" %}
Depois da integração, alterações de código de barras, grade, cor, tamanho e outras informações devem ser feitas no Phibo e enviadas para o site.
{% endhint %}

## Entendendo a integração

* **Produtos:** são enviados com estoque e preço atuais. Alterou no sistema, altera no site.
* **Coluna e-commerce:** em **Cadastrar produtos**, ao lado da quantidade, cada produto tem um status: **amarelo** (não integrado), **verde** (integrado com sucesso) e **vermelho** (erro).
* **Pedidos:** as vendas do site caem na tela **Vender e-commerce**, onde você finaliza o pedido.
* **Clientes:** quem compra no site pela primeira vez é cadastrado automaticamente no sistema.
* **Novas opções:** cadastrar produto no e-commerce, vincular, desvincular e importar produtos do e-commerce para o sistema.

A integração pode receber ajustes com o tempo. Em caso de dúvida, fale com o suporte.

## 🎬 Vídeo

{% embed url="<https://www.loom.com/share/144b09bf079c4afb92b4f551066806e4?sid=a970a781-5836-4531-bf16-6a7fdf7be8e4>" %}

## Vídeo complementar

{% embed url="https://www.youtube.com/watch?v=7WiiD1ZbKJM" %}

---

*🔎 Também procurado como: loja virtual, site, e-commerce, marketplace.*
