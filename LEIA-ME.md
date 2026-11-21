# Passo a passo: publicar o planner no GitHub Pages

1. Crie uma conta gratuita em https://github.com (se ainda não tiver).
2. Clique em **New** (ou "+" > New repository).
   - Repository name: `planner-tjsp` (pode ser outro nome)
   - Marque **Public**
   - Clique em **Create repository**.
3. Na tela do repositório, clique em **uploading an existing file**.
4. Arraste para a área de upload **todos os arquivos desta pasta**:
   `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`
   (não precisa enviar este LEIA-ME.md, mas não tem problema se enviar).
5. Clique em **Commit changes**.
6. Vá em **Settings** > **Pages** (menu lateral).
   - Em **Source**, escolha **Deploy from a branch**.
   - Em **Branch**, escolha **main** e **/ (root)**. Clique em **Save**.
7. Aguarde 1 a 2 minutos e atualize a página. Vai aparecer o endereço:
   `https://SEU-USUARIO.github.io/planner-tjsp/`

## Instalar no celular

**Android (Chrome):** abra o endereço > menu (⋮) > **Instalar aplicativo** (ou "Adicionar à tela inicial").

**iPhone (Safari):** abra o endereço > botão Compartilhar (□↑) > **Adicionar à Tela de Início**.

O ícone "Planner TJSP" aparece na tela inicial e abre em tela cheia, como um app.

## Pontos importantes

- **Os dados ficam só neste aparelho e neste navegador.** Como o site está no GitHub Pages, o sincronismo com a nuvem do claude.ai não funciona. Por isso:
  - Use o botão **⬇ Backup** no planner com frequência (salva um arquivo .json).
  - Se trocar de celular ou de navegador, use **⬆ Importar** com esse arquivo.
- **Não use o navegador em modo anônimo**, porque os dados somem ao fechar.
- **Para atualizar o planner depois:** substitua o `index.html` no GitHub (botão de lápis ou "Upload files"). Em seguida, abra o app e feche-o totalmente; se não aparecer a mudança, puxe a tela para baixo para atualizar. O celular pode demorar alguns minutos para baixar a versão nova.
- O app funciona sem internet depois da primeira abertura. As fontes e os links do QConcursos continuam dependendo da conexão.
