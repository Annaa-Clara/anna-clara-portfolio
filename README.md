# annaclara.dev — Portfólio Pessoal

Portfólio pessoal de Anna Clara, bacharelanda em Engenharia de Software e desenvolvedora backend em formação. Site único em HTML, CSS e JavaScript puros, sem frameworks ou build tools, com tema claro/escuro, animações autorais e formulário de contato funcional.

**Site publicado:** [Acesse meu Portfólio](https://annaa-clara.github.io/anna-clara-portfolio/)

---

## Sobre o projeto

Este repositório contém o código-fonte do meu portfólio, criado para apresentar minha trajetória, stack técnica e projetos como desenvolvedora backend. O objetivo foi construir uma identidade visual própria, moderna, técnica e memorável.

---

## Funcionalidades

* **Loading screen** com barra de progresso animada
* **Cursor customizado** (anel que segue o mouse, com efeito de hover em elementos interativos)
* **Barra de progresso de scroll** no topo da página
* **Header fixo** com destaque automático da seção atual e efeito de blur ao rolar
* **Menu mobile animado** em tela cheia
* **Terminal animado no hero**, simulando comandos digitados em tempo real
* **Efeito typewriter** alternando entre diferentes descrições profissionais
* **Tema claro/escuro** com alternância suave, preferência salva em `localStorage` e sem flash ao recarregar
* **Seção "Sobre"** com foto em recorte orgânico (`clip-path`), fugindo dos formatos genéricos
* **Stack técnica** organizada por abas (Backend, Banco de Dados, Ferramentas)
* **Cards de projetos** com hover, tecnologias utilizadas e links para deploy/repositório
* **Timeline de trajetória** em estilo "git log"
* **Formulário de contato** com validação client-side e envio real via Formspree
* **Botão de download do currículo** (PDF)
* **Totalmente responsivo** (desktop, tablet e mobile)
* Respeita `prefers-reduced-motion` para usuários sensíveis a animações

---

## Tecnologias Utilizadas

| Camada | Tecnologia |
| :--- | :--- |
| **Estrutura** | HTML5 semântico |
| **Estilo** | CSS3 (Custom Properties, Grid, Flexbox, clip-path) |
| **Interatividade** | JavaScript (vanilla, sem dependências) |
| **Tipografia** | Google Fonts (Space Grotesk, Inter, JetBrains Mono) |
| **Formulário** | Formspree |
| **Deploy** | GitHub Pages |

> *Sem frameworks, sem bundlers e sem etapa de build, é HTML puro pronto para rodar em qualquer navegador.*

---

## Estrutura do Repositório

```text
annaclara/
├── index.html
├── curriculo-anna-clara.pdf
└── images/
    └── anna-clara.jpg
