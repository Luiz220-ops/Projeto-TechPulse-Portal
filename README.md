# TechPulse — Portal de Notícias de Tecnologia

Primeira versão funcional da página inicial do portal **TechPulse**, desenvolvida com HTML5 e CSS3, estruturada para funcionar
corretamente tanto em computadores quanto em dispositivos móveis.

## 📁 Organização do Projeto

* `techpulse-portal/`
  * `index.html` — Estrutura semântica e conteúdo da página inicial
  * `css/style.css` — Estilização externa, Box Model e responsividade
  * `README.md` — Documentação do projeto, justificativas e Sitemap Visual

## 📋 Especificações e Justificativas

* **Cores (Hexadecimal e RGBA):** Azul-marinho (`#0F172A`) no cabeçalho, rodapé e títulos; tons de azul (`#0284C7` e `#38BDF8`) nos botões e destaques interativos; fundo claro (`#F8FAFC` e `#FFFFFF`) com texto escuro (`#1E293B`) e sombras suaves em `RGBA` para conforto de leitura.
* **Letras (Tipografia):** Fontes sem serifa (`Segoe UI`, `Roboto`, `Arial`) pela nitidez em telas digitais, com tamanhos hierárquicos (`2.25rem` no `<h1>`, `1.5rem` no `<h2>` e `16px` no texto) e alinhamento à esquerda nos artigos para facilitar a leitura.
* **Espaços Criados:** Uso de `padding`, `margin` e bordas para separar cabeçalho (`#cabecalho-principal`), seção de abertura (`.secao-hero`), lista de tecnologias (`.lista-tecnologias`), cartões de notícias (`.card-noticia`) e rodapé, com adaptação para celulares via `@media (max-width: 768px)`.
* **Tecnologias e Serviços:** HTML5 semântico (`<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`, `<strong>`, `<em>` e atributo `alt`) e CSS3 externo. Os serviços do portal cobrem **Inteligência Artificial**, **Computação em Nuvem** e **Cibersegurança**.

## 🗺️ Sitemap Visual

* **Página Inicial (`index.html`)**
  * **1. Tecnologias**
    * Inteligência Artificial Generativa
    * Computação em Nuvem (Cloud Computing)
    * Cibersegurança e Privacidade
  * **2. Notícias & Guias**
    * Engenharia Front-End
    * Arquitetura Back-End
    * DevOps & Infraestrutura
  * **3. Institucional**
    * Sobre o TechPulse
    * Newsletter Semanal
    * Contato & Redação

* **Hierarquia de Conteúdo:** Organiza a navegação do geral para o específico — começa pela proposta de valor e botão de ação no topo, segue para os pilares tecnológicos e finaliza com os artigos detalhados e dados institucionais.
* **Taxonomia:** Divide o portal em três categorias principais mutuamente exclusivas, agrupando subcategorias por área técnica para facilitar a busca e evitar ambiguidade.
