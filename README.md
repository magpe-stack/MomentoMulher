# Momento Mulher - PWA

**Momento Mulher** é um Progressive Web App (PWA) de design minimalista estritamente em preto e branco, desenvolvido para oferecer inspiração diária através de **1.000 frases motivacionais para mulheres**.

## 🌟 Funcionalidades

- **1.000 Frases Exclusivas:** Sorteio totalmente aleatório sem repetição imediata.
- **Estética Estritamente P&B:** Design limpo, elegante e focado na leitura.
- **Interface Intuitiva com 3 Botões Principais:**
  - **Modo Claro / Escuro:** Botão no topo à direita para alternar entre o tema escuro e claro.
  - **Copiar Frase:** Botão de Mão centralizado no rodapé para copiar a frase atual para a área de transferência.
  - **Próxima Frase:** Botão de Estrela centralizado no rodapé para sortear uma nova frase.
- **Suporte PWA Completo:** Pode ser instalado em dispositivos móveis e desktops, funcionando perfeitamente offline.

## 📁 Estrutura de Arquivos

```text
/
├── index.html       # Estrutura principal com logo e botoes SVG
├── style.css        # Estilização em preto e branco e temas
├── app.js           # Lógica do app e banco com as 1.000 frases
├── manifest.json    # Configurações do PWA para instalação
├── sw.js            # Service Worker para suporte offline
├── README.md        # Documentação do projeto
├── icon-192.png     # Ícone do PWA (192x192)
└── icon-512.png     # Ícone do PWA (512x512)
