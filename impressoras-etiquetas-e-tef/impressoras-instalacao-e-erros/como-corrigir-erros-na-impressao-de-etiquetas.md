# Como corrigir erros na impressão de etiquetas

Este tutorial irá guiá-lo através dos passos para diagnosticar e corrigir problemas comuns na impressão de etiquetas. Abordaremos três etapas principais para garantir que suas impressões sejam realizadas corretamente.

**Assista abaixo o passo a passo detalhado de como tratar os possíveis problemas com a impressão das etiquetas:**

{% embed url="<https://www.loom.com/share/e1ba8e4f015544309036ff0f89629bbc>" %}

### <mark style="background-color:yellow;">Passo 1: Verificação da Impressora no Windows</mark>

Antes de qualquer configuração no sistema, é crucial verificar se a impressora de etiquetas está funcionando corretamente no seu sistema operacional (Windows).

Pressione a tecla **Windows + R** para abrir a caixa de diálogo Executar.

Digite control printers e pressione Enter para abrir a janela de **Dispositivos e Impressora**s.

Localize sua impressora de etiquetas (ex: Elgin L42 ProFull).

Clique com o botão direito na impressora e selecione **Propriedades da impressora**.

Na aba Geral, clique em **Imprimir Página de Test**e.

Se a página de teste for impressa com sucesso, sua impressora está comunicando-se corretamente com o Windows. Caso contrário, pode ser necessário verificar a instalação dos drivers ou a conexão física da impressora.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FTfekAI4OIMmA87p2uKX3%2Fimage.png?alt=media&amp;token=53729291-759f-484b-b232-ddd82b121cf2" alt=""><figcaption></figcaption></figure>

### <mark style="background-color:yellow;">Passo 2: Verificação e Execução do PhibBot (Serviço de Impressão)</mark>

O PhiboBot é o serviço responsável por intermediar a comunicação entre o sistema e a impressora. Ele precisa estar em execução para que as etiquetas sejam impressas.

Minimize todas as janelas e localize a área de notificação da barra de tarefas (próximo ao relógio).

Clique na seta para cima para expandir os ícones ocultos.

Procure pelo ícone do Phibo Boot, que geralmente é uma **impressora azul**.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FLyKaP02fJtkCfLO34gxw%2Fimage.png?alt=media&amp;token=b0d54501-ed42-4473-a02e-3cc8d0ff0a2d" alt=""><figcaption></figcaption></figure>

Se o ícone não estiver visível ou o serviço não estiver em execução (uma notificação informará o status), localize o atalho do Phibo Bot na sua área de trabalho ou no menu Iniciar e execute-o com um duplo clique.

Aguarde alguns segundos até que uma notificação confirme que o "**Bot de Impressão versão X.X em execução**" (ex: 1.8) está ativo.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FMQfHc2eDL1RLIjBAXJxu%2Fimage.png?alt=media&amp;token=5a558aa0-d30b-4325-8c7e-0c495589721c" alt=""><figcaption></figcaption></figure>

### <mark style="background-color:yellow;">Passo 3: Configuração da Impressora no Sistema Phibo</mark>

Por fim, é necessário garantir que a impressora esteja configurada corretamente dentro do sistema Phibo.

No sistema Phibo, navegue até **Início > Configurar Módulos > Gestão de Impressão.**

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FKyazg4Xi0ZdyD0TOODFm%2Fimage.png?alt=media&amp;token=b2d2aefa-5413-4da3-99d9-77eaa85a3a82" alt=""><figcaption></figcaption></figure>

Dentro de Gestão de Impressão, verifique o Status do Serviço de Impressão. Ele deve indicar que o serviço está em execução.

Clique em **Impressoras Configuradas.**

Certifique-se de que a impressora de etiquetas (ex: Elgin L42 ProFull) esteja selecionada e que o nome exibido seja idêntico ao nome da impressora no Windows (verificado no Passo 1).

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2F7xZv2HWQG04M5CTt2Bfw%2Fimage.png?alt=media&amp;token=2cca25e3-8b2a-4ecb-b64d-9bbaa69af3be" alt=""><figcaption></figcaption></figure>

Se a impressora não estiver listada ou o nome estiver incorreto, insira os dados da impressora e clique em Salvar. As informações de tamanho e layout da etiqueta já devem estar pré-configuradas.

### <mark style="background-color:yellow;">Passo 4 : Impressão de Etiquetas</mark>

Após seguir todos os passos acima, você pode prosseguir com a impressão das suas etiquetas:

No sistema Phibo, vá para **Compras > Gestão de Estoque > Listar Produtos.**

Busque e selecione os produtos para os quais deseja imprimir etiquetas.

Adicione os produtos à **fila de impressão**.

Visualize a fila de impressão, onde você pode ajustar a quantidade de etiquetas por produto ou remover itens.

<figure><img src="https://1136259996-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MbXdm46cDzB-VCuUzq9%2Fuploads%2FFEG1dcS8nb53oZibYx38%2Fimage.png?alt=media&amp;token=a2ccffdb-672f-4084-8ebf-4e36a09333c4" alt=""><figcaption></figcaption></figure>

**Clique em Imprimir Etiquetas.**

Se as etiquetas forem impressas, o processo de correção foi bem-sucedido. \
Caso os problemas persistam, entre em contato com o suporte técnico da Phibo para assistência especializada.

---

*🔎 Também procurado como: etiqueta não imprime, etiqueta torta, etiqueta em branco.*
