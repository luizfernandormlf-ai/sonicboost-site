# Site gratuito do SonicBoost

Este é um site estático responsivo em português, com visual preto e roxo, pronto para personalização e hospedagem gratuita em um serviço de páginas estáticas.

## Conteúdo
- `index.html`: página principal
- `styles.css`: layout responsivo e tema
- `script.js`: comportamento simples do site
- `assets/sonicboost.svg`: ícone SVG
- `PRIVACIDADE.md`: rascunho da política de privacidade

## Importante antes de publicar
O site **não inclui um EXE compilado** e os botões de download ficam intencionalmente desativados/indicados como "em breve". Não publique um link para um ZIP de código-fonte como se fosse um instalador pronto.

Quando a versão do Windows estiver compilada e testada:
1. Publique o pacote final numa página de Releases do GitHub (ou hospedagem confiável).
2. Atualize o cartão Windows em `index.html` para apontar para o URL real do pacote.
3. Teste o link num computador que não tenha o ambiente de desenvolvimento instalado.
4. Substitua o contato na política de privacidade por um contato real.
5. Revise os textos de compatibilidade para refletir apenas recursos testados.

## Hospedagem gratuita com GitHub Pages
1. Crie/entre na sua conta do GitHub.
2. Crie um repositório público, por exemplo `sonicboost-site`.
3. Envie todos os arquivos desta pasta para a raiz do repositório.
4. Abra `Settings` → `Pages`.
5. Em `Build and deployment`, selecione `Deploy from a branch`, escolha `main` e `/ (root)`, e salve.
6. Aguarde o GitHub publicar o site e abra o endereço exibido na página Pages.

O endereço padrão do GitHub Pages é gratuito. Um domínio próprio é opcional e pode ter custo.

## Testar localmente
Dê dois cliques em `index.html` para abrir no navegador. Para testar em diferentes tamanhos de tela, redimensione a janela ou use o modo de dispositivo móvel das ferramentas do navegador.


## Página de sugestões e dicas
A página `sugestoes.html` reúne dicas básicas de áudio e uma chamada para enviar sugestões. Antes de publicar, substitua `SEU-EMAIL-AQUI@example.com` pelo endereço oficial de suporte.


## Configurar o formulário de sugestões (obrigatório antes de publicar)
A página `sugestoes.html` usa o serviço FormSubmit para enviar sugestões por e-mail sem precisar criar um servidor.

1. Abra `sugestoes.html` em um editor de texto.
2. Procure `https://formsubmit.co/SEU-EMAIL-AQUI@example.com`.
3. Substitua `SEU-EMAIL-AQUI@example.com` pelo e-mail real que receberá as sugestões.
4. Publique o site e envie uma sugestão de teste.
5. O FormSubmit enviará uma mensagem de confirmação para esse endereço. Abra-a e confirme a ativação; só então os envios serão encaminhados.
6. Faça um segundo teste para conferir o recebimento.

O serviço externo processa os dados enviados pelo formulário. Atualize a política de privacidade e publique apenas se estiver de acordo com as condições do serviço. O formulário não está pronto para receber mensagens até que o e-mail seja configurado e confirmado.
