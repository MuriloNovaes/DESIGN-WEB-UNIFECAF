# Biblioteca Digital UniFECAF

Primeira interface web da Biblioteca Digital UniFECAF, desenvolvida com **HTML e CSS puros** para a disciplina Design Web.

- **Site publicado:** https://muriloNovaes.github.io/DESIGN-WEB-UNIFECAF/biblioteca-unifecaf/
- **Vídeo pitch:** [link do YouTube]

## Seções
1. Menu (Biblioteca, Livros, Unidades, Contatos)
2. Hero com chamada principal
3. Sobre a nossa biblioteca + serviços
4. Banner "Leia onde estiver"
5. Nossos livros (6 destaques com categoria e "Saiba mais")
6. As unidades (3 unidades)
7. Contatos e rodapé

## Estrutura
```
biblioteca-unifecaf/
├── index.html
├── css/
│   └── style.css
└── assets/
    └── imagens/
```

## Tecnologias e boas práticas
- HTML5 semântico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS com variáveis, Grid e Flexbox
- Responsivo: desktop, tablet e smartphone (media queries em 960px, 680px e 380px)
- Acessibilidade: textos alternativos, link "pular para o conteúdo", foco visível, contraste WCAG AA, `prefers-reduced-motion`
- Ilustrações próprias em SVG, nas cores da identidade UniFECAF

## Como executar
Abra o arquivo `index.html` no navegador. Não há dependências nem etapa de build.
