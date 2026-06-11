# 🏗️ Focus Infraestrutura — Website Corporativo

> Website institucional premium, responsivo e de alta performance desenvolvido para a **Focus Infraestrutura**, empresa especialista em engenharia, terraplanagem, pavimentação e obras civis industriais.

---

## 🛠️ Tecnologias & Ferramentas Utilizadas

O projeto foi construído priorizando performance, acessibilidade e facilidade de manutenção para a publicação de novos artigos no blog.

* **Interface & Estilização:**
  ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

* **Arquitetura Estática & Blog:**
  ![Eleventy](https://img.shields.io/badge/11ty-%23222222.svg?style=for-the-badge&logo=eleventy&logoColor=white)
  ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

* **Hospedagem & CI/CD:**
  ![GitHub Pages](https://img.shields.io/badge/github%20pages-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
  ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232088FF.svg?style=for-the-badge&logo=githubactions&logoColor=white)

---

## ✨ Recursos de Destaque

* 🔴 **Identidade Visual Premium:** Design alinhado à paleta corporativa de vermelho escuro (bordô), grafite e off-white.
* 🔄 **Carrossel Infinito Fluido (Portfólio):** Carrossel contínuo com algoritmo em JavaScript que clona elementos dinamicamente para evitar espaços em branco nas bordas.
* 📱 **Design Totalmente Responsivo:** Menus, seções adaptativas e inversão estritamente controlada do Hero para leitura confortável em dispositivos móveis.
* ⚡ **Blog Ultraleve (Jamstack):** Artigos técnicos gerenciados em Markdown compilados nativamente pelo Eleventy (11ty), garantindo carregamento instantâneo.
* 🤖 **Deploy Automatizado:** Fluxo contínuo via GitHub Actions integrado ao GitHub Pages, reconstruindo as URLs com `pathPrefix` seguro.

---

## 📂 Arquitetura de Pastas

A estrutura organizacional do repositório foi simplificada para manter os arquivos visuais na raiz e o conteúdo gerenciável de forma isolada:

```text
site-focusinfraestrutura/
├── .github/workflows/
│   └── eleventy.yml         # Automação de compilação e deploy na nuvem
├── assets/                  # Arquivos estáticos globais de estilização e mídia
│   ├── css/
│   │   ├── header.css       # Estilos isolados do cabeçalho fixo corporativo
│   │   └── footer.css       # Estilos isolados do rodapé simétrico
│   └── js/                  # Scripts de controle de abas e carrosséis
├── blog/                    # Pasta dedicada exclusivamente às postagens do blog
│   ├── primeiro-post.md     # Artigo técnico estruturado em Markdown
│   └── segundo-post.md
├── index.html               # Página Inicial (Home)
├── quem-somos.html          # Página Institucional
├── servicos.html            # Catálogo Técnico de Serviços com Fundo Fluido Animado
├── noticias.html            # Feed Geral de Notícias (Blog)
├── eleventy.config.js       # Configurações do compilador e PathPrefix
└── .eleventyignore          # Arquivos e diretórios ignorados pelo gerador