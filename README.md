# Agência Criativa Web 🎨

Site institucional de uma agência de design digital fictícia, desenvolvido como projeto prático do curso de Front-End da EBAC.

---

## 📋 Sobre o projeto

A **Agência Criativa Web** é um site institucional completo com design moderno, elegante e totalmente responsivo. O projeto foi desenvolvido do zero, aplicando conceitos fundamentais de desenvolvimento front-end, e posteriormente refatorado com **SASS** para uma arquitetura modular e escalável.

---

## 🚀 Tecnologias utilizadas

- **HTML5** semântico
- **CSS3** com variáveis, Flexbox e Grid
- **SASS (SCSS)** com partials, variáveis, mixins e aninhamento
- **JavaScript** vanilla para o menu hambúrguer
- **Node.js** para compilação do SASS

---

## 📐 Conceitos aplicados

- Arquitetura modular com **SASS Partials** e `@use`
- **Variáveis SASS** para cores, fontes e espaçamentos
- **Mixins reutilizáveis** para botões e espaçamento de seções
- **Mixin `respond()`** com mapa de breakpoints para media queries
- **Aninhamento de seletores** com `&` seguindo a metodologia BEM
- **Mobile-first** com `min-width` nos breakpoints
- Metodologia **BEM** para nomeação de classes
- Layout com **Flexbox** e **CSS Grid**
- Menu hambúrguer com JavaScript
- Scroll suave com `scroll-behavior` e `scroll-margin-top`
- Acessibilidade com atributos `aria-label` e HTML semântico

---

## 📁 Estrutura do projeto

```
agencia-criativa-web/
├── index.html
├── scss/
│   ├── estilos.scss        
│   ├── _variaveis.scss     
│   ├── _mixins.scss        
│   ├── _base.scss          
│   ├── _layout.scss        
│   └── _componentes.scss   
├── css/
│   └── estilos.css         
└── README.md
```

---

## 🗂️ Seções do site

- **Home** — banner de boas-vindas com CTA e card visual
- **Sobre nós** — descrição da agência com grid de estatísticas
- **Serviços** — 6 serviços em grid responsivo
- **Depoimentos** — 3 depoimentos de clientes fictícios
- **Contatos** — informações de contato e formulário

---

## 🎨 Identidade visual

| Elemento | Valor |
|---|---|
| Cor primária | `#1a1a1a` |
| Cor secundária | `#f5f4f0` |
| Cor de acento | `#8B7355` |
| Fonte de título | DM Serif Display |
| Fonte de corpo | DM Sans |

---

## 📱 Responsividade
O projeto adota a abordagem **mobile-first**, com breakpoints definidos como mapa de variáveis SASS e aplicados via mixin `respond()`.
 
| Breakpoint | Dispositivo |
|---|---|
| `576px` (sm) | Mobile landscape |
| `768px` (md) | Tablet portrait |
| `1024px` (lg) | Tablet landscape e desktop |
| `1280px` (xl) | Desktop grande |
 
---

## ⚙️ Como rodar o projeto

1. Clone o repositório:
```bash
git clone https://github.com/lucassloliveira/agencia-criativa-web.git
```
2. Instale o SASS via Node.js:
```bash
npm install -g sass
```
 
3. Compile o SASS:
```bash
sass scss/estilos.scss css/estilos.css
```
 
4. Abra o arquivo `index.html` no navegador ou use a extensão **Live Server** no VS Code.
> 💡 Para compilar automaticamente ao salvar, use o modo watch:
> ```bash
> sass --watch scss/estilos.scss css/estilos.css
> ```
 
---

## 📚 Projeto de estudo

Este projeto foi desenvolvido exclusivamente para fins educacionais como atividade prática do curso de Front-End da **EBAC — Escola Britânica de Artes Criativas e Tecnologia**. Todos os conteúdos, clientes e informações presentes no site são fictícios.
