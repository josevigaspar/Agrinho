🌾 Sobre o Projeto
──────────────────
“Do Plantio à Mesa” é um site em **HTML puro + CSS** que narra, em dez
etapas interativas, todo o percurso dos alimentos: da semente, passando
pela indústria e logística, até chegar ao prato — e então retornar ao
solo pela compostagem.  
Os textos, as ilustrações em CSS (broto animado e roda de queijo 3-D) e
as dicas de ação foram criados para aproximar **campo e cidade**,
conforme o tema oficial do edital.

🎯 Objetivos
────────────
1. **Inspirar** Mostrar que cada refeição nasce na roça e depende de
   milhares de decisões ao longo da cadeia.
2. **Educar** Entregar dicas simples que qualquer pessoa pode aplicar
   para reduzir desperdício, emissões e custos.
3. **Engajar** Convidar visitantes a postar suas iniciativas com
   **#DoPlantioÀMesa** e compartilhar boas práticas.

🚀 Tecnologias & Boas-Práticas
──────────────────────────────
• **HTML 5 semântico** (header, main, section, dialog).  
• **CSS 3** com Custom Properties, `clamp()` e *Grid/Flexbox*.  
• **Acessibilidade**: skip-link, contraste AA, foco visível, botão
  **A+** (amplia texto 15 %).  
• **Interatividade sem JS**: carrossel _scroll-snap_, quiz via
  checkboxes, modais `<dialog>`.

🎨 Paleta & Tipografia
─────────────────────
╭───────────────────────────────╮
│  --clr-primary     hsl(122 70% 30%) │ botões & links          │
│  --clr-secondary   hsl(35  90% 50%) │ destaques / call-to-action │
│  --clr-bg-light    #faf8f5          │ seções claras           │
│  --clr-bg-dark     #0e2311          │ seções escuras          │
╰───────────────────────────────╯  
• Títulos → **Merriweather**, Corpo → **Poppins**

📁 Estrutura
────────────
.
├─ index.html         # página única
├─ styles.css         # tema, animações, responsividade
├─ README.md          # este documento
└─ assets/            # favicon, prints, edital.pdf

🗺️ Mapa Rápido do Site
──────────────────────
• **#inicio** Hero animado + gradiente & ondas  
• **#etapas** Carrossel com 10 emojis + modais `<dialog>`  
• **#plantio** Broto em CSS + boas-práticas de horta  
• **#jornada** Linha do tempo logística (cards _slide-in_)  
• **#industria** Ilustração queijo 3-D em CSS puro  
• **#consumo** Grid “Zero Desperdício” (4 dicas)  
• **#historias** 4 cases reais de Douradina-PR (modais)  
• **#faq** Perguntas frequentes via `<details>`  
• **#quiz** Quiz de 3 perguntas (checkbox + CSS)  
• **#acao** Chamada para compartilhar histórias por e-mail

♿ Acessibilidade & UX
─────────────────────
✓ Skip-link visível na primeira tecla Tab  
✓ *Focus ring* dash laranja em todos os elementos interativos  
✓ Botão **A+** – usa `:has(#fs-toggle:checked)` para aumentar fonte  
✓ `prefers-reduced-motion` → animações pausadas  
✓ Testes em leitor de tela NVDA 2024 + Chrome DevTools Audit

💡 Como Rodar Localmente
────────────────────────
git clone https://github.com/SEU-USUARIO/do-plantio-a-mesa.git
cd do-plantio-a-mesa
# abra index.html no navegador (duplo-clique ou `xdg-open`)

🌐 Publicação via GitHub Pages
─────────────────────────────
1. Settings → Pages → Source = `main / (root)`  
2. Salvar; URL gerada -> `https://SEU-USUARIO.github.io/do-plantio-a-mesa/`  
3. Adicionar _topic_ **agrinho** nas configurações do repositório.

🛠️ Contribuições
────────────────
• Fork → Branch `feature/nome` → Commits claros → Pull Request.  
• Sugestões de acessibilidade, revisão de fontes ou traduções são
  muito bem-vindas!

📜 Licença
──────────
MIT. Consulte o arquivo `LICENSE` para detalhes.

🙋‍♂️ Autor
──────────
**José Vinícius** – 2.º ano, Colégio Cleoracy A. Gil (Douradina-PR)  
✉️ josevinicius@email.com

“Cada semente carrega uma história; cada prato, uma escolha.”