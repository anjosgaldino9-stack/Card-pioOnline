Projeto: Cardapio_Online
======================

Descrição
--------
Projeto didático front-end para um cardápio digital (hambúrgueres, acompanhamentos e bebidas) implementado com HTML e CSS. Foi criado para exercitar conceitos aprendidos no módulo de HTML e CSS do curso de Desenvolvimento Fullstack.

Tecnologias utilizadas e impacto das decisões
-------------------------------------------
- HTML5 (`index.html`): estrutura semântica que facilita manutenção, acessibilidade e indexação; ótima base para evolução para SPA ou templates.
- CSS3 (`style.css`): separa apresentação da estrutura, simplificando estilo, manutenção e possibilidade de theming.
- Layout com Flexbox / responsividade: facilita o posicionamento dos cards e reduz esforço para adaptar a interface a diferentes tamanhos de tela.
- Organização de assets (`imagensCompactadas/`): imagens otimizadas melhoram performance e experiência do usuário em redes lentas.
- Ausência de JavaScript no núcleo: mantém foco educativo em HTML/CSS; reduz complexidade, mas limita interatividade — ponto claro para evolução.

Benefícios pedagógicos
---------------------
- Separa responsabilidades (markup vs apresentação) e demonstra boas práticas de componentização visual (`.boxProduto`, `.boxImg`, `.boxTexto`).
- Simula fluxo real de projeto (organização de pastas, assets), preparando para integrações futuras com JS e back-end.

Estado do projeto
-----------------
Em desenvolvimento — implementação inicial em HTML/CSS concluída; funcionalidades dinâmicas (carrinho, persistência, API) ainda pendentes.

Contribuição & Contato
----------------------
Como contribuir:
- Faça fork do repositório.
- Crie uma branch com nome descritivo (ex.: `feat/carrinho-js`).
- Abra um Pull Request com descrição clara das mudanças.

Reportar problemas / solicitar features:
- Abra uma *issue* no repositório com título e passos para reproduzir.

Contato direto:
- E-mail: seu-endereco@example.com (substitua pelo seu contato real).
- GitHub: use o perfil do autor para mensagens diretas ou comentários em PRs.

Sugestões de contribuições úteis:
- Implementar carrinho com JavaScript e persistência em `localStorage`.
- Criar uma API simples (Node.js + Express) para receber pedidos.
- Melhorar acessibilidade (atributos `alt`, navegação por teclado, contraste).
- Tornar o layout totalmente responsivo com breakpoints adicionais.

Como testar localmente
----------------------
1. Abra `index.html` no seu navegador.
2. Para servir localmente (opcional), use um servidor estático (ex.: `python -m http.server 8000`).

Quer contribuir? Abra um PR ou envie um e‑mail — toda ajuda é bem-vinda.
