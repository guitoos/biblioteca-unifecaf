# Biblioteca Digital UniFECAF

Interface web da Biblioteca Digital UniFECAF, desenvolvida a partir do protótipo de baixa
fidelidade fornecido pela instituição, utilizando **exclusivamente HTML5 e CSS3** — sem
frameworks, bibliotecas, construtores de sites ou templates prontos.

Trabalho da disciplina de **Design Web**.
**Guilherme Oliveira Silva Santos — RA 143422**

---

## Sobre o projeto

Página única com as seis seções definidas no protótipo:

1. **Banner (hero)** — abertura com título, texto de apoio e chamadas para ação
2. **Sobre a nossa biblioteca** — bloco institucional em três colunas + quatro cartões de serviço
3. **Faixa de destaque** — frase-síntese e indicadores numéricos
4. **Nossos livros** — grade de seis obras com capa, categoria, descrição e botão
5. **As unidades** — três unidades em blocos de imagem + texto alternados
6. **Contatos** — atendimento, endereço e mapa ilustrado

## Características

- **Responsivo de 320 px a 1440 px**, escrito em abordagem *mobile first* com quatro pontos de
  quebra (600 px, 768 px, 992 px e 1200 px). Sem rolagem horizontal em nenhuma largura testada.
- **Paleta derivada da identidade visual da UniFECAF** — nove cores declaradas como variáveis CSS,
  todas as combinações de texto com contraste acima de 4,5:1 (WCAG 2.1 AA).
- **19 ilustrações autorais em SVG**, criadas para o projeto, somando cerca de 33 KB.
- **Acessibilidade**: HTML semântico, hierarquia de títulos consistente, textos alternativos,
  link de salto para o conteúdo, foco visível, alvos de toque amplos e suporte a
  `prefers-reduced-motion`.
- **Sem JavaScript** — toda a interação é resolvida com CSS.

## Estrutura de arquivos

```
biblioteca-unifecaf/
├── index.html              estrutura e conteúdo da página
├── css/
│   └── style.css           layout, identidade visual e responsividade
└── assets/
    └── imagens/            19 ilustrações autorais em SVG
```

## Como executar localmente

Não há etapa de build. Basta clonar o repositório e abrir o arquivo `index.html` no navegador:

```bash
git clone <url-do-repositorio>
cd biblioteca-unifecaf
```

## Tecnologias

- HTML5 (marcação semântica)
- CSS3 (variáveis, Grid, Flexbox, `clamp()`, `aspect-ratio`, media queries)
- SVG (ilustrações vetoriais)
- Google Fonts — Poppins e Inter, com alternativas do sistema

---

Projeto acadêmico. As ilustrações são de autoria própria.
