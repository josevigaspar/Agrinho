# Do Plantio à Mesa 🌱🍽️  
_Festejando a Conexão Campo-Cidade_

Bem-vindo ao repositório do projeto **“Do Plantio à Mesa”**!  
Este site convida você a percorrer todas as etapas do ciclo alimentar — da semente ao prato — celebrando, de forma prática e interativa, o elo vital entre o campo e a cidade.

## 📦 Sobre o Projeto
O site foi criado como participação no **Concurso Agrinho 2025 – Subcategoria 4 (HTML + CSS)**.  
Ele combina conteúdos autorais, arte em CSS pura e dicas acionáveis para que qualquer pessoa possa **reduzir desperdícios, apoiar produtores locais** e adotar hábitos que diminuem a pegada de CO₂.

### 🌟 Objetivos Principais
1. **Inspirar** — Mostrar, em linguagem simples, por que cada refeição começa na roça e termina na mesa.
2. **Educar** — Oferecer ideias rápidas para plantar, comprar, cozinhar e descartar de forma responsável.
3. **Engajar** — Incentivar estudantes a compartilharem suas próprias histórias usando a hashtag `#DoPlantioÀMesa`.

## 🚀 Tecnologias Utilizadas
- **HTML 5 semântico** – Estrutura lógica e acessível.  
- **CSS 3 / Custom Properties** – Tema consistente, animações e arte 100 % CSS (broto & queijo).  
- **Responsividade** – *Flexbox*, *Grid* e *media queries* para telas de 320 px a 4 K.  
- **Acessibilidade** – Skip-link, contraste alto, botão *A+* para texto ampliado, navegação via teclado.

## 🎨 Paleta & Tipografia
| Variável            | Cor / HSL            | Uso principal            |
|---------------------|----------------------|--------------------------|
| `--clr-primary`     | `hsl(122,70%,30%)`   | Barras, destaques        |
| `--clr-secondary`   | `hsl(35,90%,50%)`    | Botões, links de ação    |
| `--clr-bg-light`    | `#faf8f5`            | Seções claras            |
| `--clr-bg-dark`     | `#0e2311`            | Seções escuras           |
| Títulos: **Merriweather**, Corpo: **Poppins** |

> Todas as cores foram escolhidas para reforçar a ideia de **nutrição (verde)** e **energia/acolhimento (laranja-dourado)**.

## 📄 Estrutura do Repositório
│ index.html # Página principal
│ styles.css # Estilos globais e animações
│ README.md # Este arquivo
└─ assets/ # (Imagens, PDFs de referência, favicon, etc.)

### Navegação do Site
- **Menu hambúrguer:** abertura/fechamento pelo toque ou tecla <kbd>Enter</kbd>.  
- **Botão ↑ Topo:** aparece após rolagem da seção **#jornada**.  
- **Botão A+:** aumenta toda a fonte em 15 %, útil para leitura confortável.  
- **Modais de Etapas/Histórias:** abrir clicando na figura, fechar com `✕`, `Esc` ou pelo fundo escurecido.

## 📐 Responsividade & Acessibilidade
- Breakpoints principais em **860 px** e **600 px**.  
- Elementos interativos recebem `:focus-visible` com borda tracejada laranja.  
- Animações são desativadas para quem possui `prefers-reduced-motion` ativo.

## 🌐 Publicação
O site está hospedado via **GitHub Pages**:  
🔗 **https://seu-usuario.github.io/do-plantio-a-mesa/**

> **Importante:** este repositório contém a *topic* oficial **`agrinho`** para pontuação na rubrica de Publicação.

## 💡 Como Rodar Localmente
```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/do-plantio-a-mesa.git

# 2. Acesse a pasta
cd do-plantio-a-mesa

# 3. Abra index.html no navegador
start index.html   # Windows
# ou
open index.html    # macOS

## 🛠️ Contribuindo
Contribuições são bem-vindas!

Fork ➜ 2. Branch ➜ 3. Commit com mensagens claras ➜ 4. Pull Request.

## 📜 Licença
Distribuído sob a Licença MIT. Veja o arquivo LICENSE para detalhes.

## 🙋‍♂️ Autor & Contato
Desenvolvido por José Vinícius – 2.ª série, Colégio Cleoracy A. Gil.
✉️ contato: josevinicius@email.com

Todos os textos e ilustrações CSS são 100 % autorais.
Referências externas (EMBRAPA, CONAB, IBGE) encontram-se citadas nas modais correspondentes.

Obrigado por visitar o “Do Plantio à Mesa”.
Participe postando sua ação com a hashtag #DoPlantioÀMesa e ajude a aproximar ainda mais cidade e campo!