<div class="readme-wrapper">

<h1>Do Plantio à Mesa 🌱🍽️<br><small>Festejando a Conexão Campo-Cidade</small></h1>

<blockquote>
<strong>Projeto inscrito no Concurso Agrinho 2025 – Subcategoria 4.</strong><br>
Site 100 % em HTML5 + CSS3, sem JavaScript, com foco em acessibilidade,
responsividade e conteúdo autoral.
</blockquote>

<hr>

<h2>📦 Sobre o Projeto</h2>

<p>
“Do Plantio à Mesa” guia o visitante pelas <strong>10 etapas do ciclo
alimentar</strong> – da semente à compostagem – mostrando ações concretas
para aproximar produtores rurais e consumidores urbanos.
O conteúdo foi escrito em linguagem simples, conforme o edital,
e reforçado por ilustrações e animações feitas só em CSS.
</p>

<h3>Como cada critério do edital é atendido</h3>

<table>
<thead><tr><th>Critério</th><th>Implementação</th></tr></thead>
<tbody>
<tr><td>Tema oficial</td><td>Todas as seções exaltam a <em>conexão campo-cidade</em>.</td></tr>
<tr><td>HTML + CSS apenas</td><td>Interatividade via <code>&lt;dialog&gt;</code>,
<code>&lt;details&gt;</code>, <em>scroll-snap</em> — nenhum JS incluído.</td></tr>
<tr><td>Acessibilidade</td><td>Skip-link, foco visível, contraste AA, botão “A+”.</td></tr>
<tr><td>Responsividade</td><td>Flexbox/Grid de 320 px a 4 K; testes em mobile/desktop.</td></tr>
<tr><td>Originalidade</td><td>Arte “Broto” e “Queijo 3-D” modeladas em CSS puro.</td></tr>
<tr><td>Referências</td><td>Fontes citadas nos modais e rodapé de cada seção.</td></tr>
</tbody>
</table>

<h2>🌟 Objetivos</h2>

<ul>
<li><strong>Inspirar</strong> – Evidenciar que cada refeição nasce na roça.</li>
<li><strong>Educar</strong> – Dar dicas para reduzir desperdício e CO₂.</li>
<li><strong>Engajar</strong> – Incentivar postagens com <code>#DoPlantioÀMesa</code>.</li>
</ul>

<h2>🚀 Tecnologias &amp; Boas-Práticas</h2>

<ul>
<li>HTML5 semântico (<code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;section&gt;</code>).</li>
<li>CSS 3 com custom properties e <code>clamp()</code> para tipografia fluida.</li>
<li>Carrossel, quiz e modais funcionando só com CSS.</li>
<li>Zero dependências externas além das Google Fonts.</li>
</ul>

<h2>🎨 Paleta &amp; Tipografia</h2>

<table>
<thead><tr><th>Variável</th><th>Cor / Valor</th><th>Uso</th></tr></thead>
<tbody>
<tr><td><code>--clr-primary</code></td><td>hsl(122 70% 30%)</td><td>Botões, links</td></tr>
<tr><td><code>--clr-secondary</code></td><td>hsl(35 90% 50%)</td><td>Destaques</td></tr>
<tr><td><code>--clr-bg-light</code></td><td>#faf8f5</td><td>Seções claras</td></tr>
<tr><td><code>--clr-bg-dark</code></td><td>#0e2311</td><td>Seções escuras</td></tr>
<tr><td><em>Títulos</em></td><td>Merriweather</td><td></td></tr>
<tr><td><em>Corpo</em></td><td>Poppins</td><td></td></tr>
</tbody>
</table>

<h2>📁 Estrutura de Pastas</h2>

<pre><code>.
├─ index.html        # página única
├─ styles.css        # layout, temas, animações
├─ README.md         # você está aqui 🙂
└─ assets/           # favicon, capturas, edital.pdf
</code></pre>

<h2>🗺️ Mapa Rápido do Site</h2>

<ul>
<li><strong>#inicio</strong> – Hero com gradiente animado</li>
<li><strong>#etapas</strong> – Carrossel “10 Etapas” + modais</li>
<li><strong>#plantio</strong> – Broto CSS + dicas de horta</li>
<li><strong>#jornada</strong> – Linha do tempo logística</li>
<li><strong>#industria</strong> – Queijo 3-D em CSS</li>
<li><strong>#consumo</strong> – Grid “Zero Desperdício”</li>
<li><strong>#historias</strong> – 4 cases reais de Douradina-PR</li>
<li><strong>#faq</strong> – Perguntas frequentes (<code>&lt;details&gt;</code>)</li>
<li><strong>#quiz</strong> – Quiz via checkboxes + CSS</li>
<li><strong>#acao</strong> – Chamada para compartilhar histórias</li>
</ul>

<h2>♿ Acessibilidade &amp; UX</h2>

<ul>
<li>Skip-link visível na primeira tecla <kbd>Tab</kbd>.</li>
<li>Anel de foco tracejado laranja em todos os controles.</li>
<li>Botão <strong>A+</strong> aumenta fonte usando <code>:has()</code>.</li>
<li>Suporte a <code>prefers-reduced-motion</code>.</li>
</ul>

<h2>💡 Como Rodar Localmente</h2>

<pre><code>git clone https://github.com/SEU-USUARIO/do-plantio-a-mesa.git
cd do-plantio-a-mesa
# abra index.html no navegador (duplo-clique ou xdg-open)
</code></pre>

<h2>🌐 Publicação via GitHub Pages</h2>

<ol>
<li>Settings → Pages → <em>Branch</em> = <strong>main / root</strong>.</li>
<li>Salvar – URL: <code>https://SEU-USUARIO.github.io/do-plantio-a-mesa/</code>.</li>
<li>Adicione a <em>topic</em> <strong>agrinho</strong> para pontuação extra.</li>
</ol>

<h2>🛠️ Contribuições</h2>

<p>Fork → branch <code>feature/&lt;nome&gt;</code> → commits claros → Pull Request.<br>
Correções de acessibilidade, traduções e melhorias são bem-vindas!</p>

<h2>📜 Licença</h2>

<p>Distribuído sob a <strong>Licença MIT</strong>. Consulte <code>LICENSE</code> para detalhes.</p>

<h2>🙋‍♂️ Autor</h2>

<p><strong>José Vinícius</strong> – 2.º ano, Colégio Cleoracy A. Gil (Douradina-PR)<br>
Contato: <a href="mailto:josevinicius@email.com">josevinicius@email.com</a></p>

<blockquote>
“Cada semente carrega uma história; cada prato, uma escolha.”
</blockquote>

</div>