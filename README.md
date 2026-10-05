# 🍰 Doceria da Marta - Landing Page Institucional

Uma landing page moderna, acolhedora e responsiva para a confeitaria artesanal **Doceria da Marta**, desenvolvida com foco em padrões modernos de **UX Design**, **Copywriting persuasivo** e arquitetura limpa em **HTML5 Semântico** e **CSS3 (Grid & Flexbox)**. - Criada testando o uso da IA Antigravity do Google.

---

## 📁 Estrutura de Arquivos do Repositório

```text
fDDM/
├── index.html        # Estrutura semântica principal da landing page
├── index.tml         # Cópia compatível com a nomenclatura solicitada
├── estilos.css       # Estilização completa (CSS Grid, Flexbox, Media Queries)
└── README.md         # Documentação do projeto e decisões técnicas
```

---

## 🎯 Requisitos Atendidos

| Seção / Requisito | Implementação Técnica & Prática |
| :--- | :--- |
| **Header & Boas-Vindas** | `<header class="header-area">` contendo o banner de boas-vindas com UX design: proposta de valor clara, prova social (5.000+ eventos, avaliação 4.9★), selos flutuantes de qualidade e CTAs contrastantes. |
| **Navegação (`<nav>`)** | Menu sticky com itens obrigatórios: **Sobre a Empresa**, **Serviços**, **Contate-nos** (+ Depoimentos), com suporte a menu hambúrguer interativo para dispositivos móveis. |
| **Apresentação & Copywriting** | História fictícia e afetiva da Dona Marta (fundada em 2012), explorando os pilares de pureza dos ingredientes, design autoral e conexão emocional (Copywriting focado no método AIDA: Atenção, Interesse, Desejo e Ação). |
| **Seção de Serviços** | Disposição estruturada da seção com **CSS Grid** e **Carrossel interativo com Flexbox** (`scroll-snap-type: x mandatory`), botões de navegação e cards com categorias, fotos, diferenciais e links para orçamento. |
| **Depoimentos de Clientes** | Grade em **CSS Grid** com avaliações 5 estrelas, fotos de clientes reais em avatar, datas e depoimentos humanizados sobre casamentos, presentes e eventos corporativos. |
| **Seção de Contato** | Informações completas de atendimento (endereço nos Jardins - SP, WhatsApp, e-mail e horários) + formulário de cotação de serviços sob medida. |
| **CSS Grid na Página Completa** | Estruturação global do layout através de `display: grid; grid-template-areas: "header" "main" "footer";` além de grades específicas em cada seção. |
| **Responsividade & Unidades Relativas** | Utilização de `rem`, `em`, `%`, `vh`, `vw` e funções CSS modernas como `clamp()`, com Media Queries refinadas para desktops, tablets (≤1024px, ≤768px) e smartphones (≤480px). |

---

## 🎨 Design System & UX Design

- **Paleta Afetiva & Gastronômica:** Tons de framboesa/berry (`#9C3D54`), caramelo dourado (`#D48149`), fundo creme baunilha (`#FFF8F4`) e cacau escuro (`#2D1D1B`) para contraste e legibilidade impecáveis.
- **Tipografia:** 
  - Títulos: *Playfair Display* (elegância clássica e toque artesanal de confeitaria).
  - Textos corridos: *Poppins* (alta legibilidade e modernidade geométrica).
- **Acessibilidade (a11y):** Marcação semântica (`<header>`, `<nav>`, `<main>`, `<article>`, `<figure>`, `<footer>`), atributos `aria-label`, estados `:focus-visible` bem definidos e contraste validado WCAG.

---
