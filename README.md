# SyntaxWear - E-commerce de Tênis e Sneakers

Este projeto é uma landing page/vitrine para uma loja de e-commerce de tênis e sneakers, SyntaxWear. O objetivo é apresentar os produtos de forma atraente, destacando categorias e ofertas, e capturar o interesse do usuário com um design moderno e responsivo.

## Funcionalidades

*   **Seção Hero:** Destaque principal com imagem de fundo, título impactante e chamadas para ação ("Ver modelos", "Comprar").
*   **Categorias de Produtos:** Exibição de diferentes categorias de tênis (Casual, Esporte, Moderno, Futurista) com links para suas respectivas páginas.
*   **Grade de Produtos em Destaque:** Uma seção com um layout de grade para apresentar produtos específicos e coleções.
*   **Formulário de Newsletter:** Campo para inscrição de e-mail, incentivando o engajamento do cliente.
*   **Rodapé Completo:** Contém links de navegação para as categorias (Masculino, Feminino, Outlet), informações da loja e sobre a empresa, além de links para redes sociais.
*   **Redes Sociais:** Ícones clicáveis para Instagram, WhatsApp, TikTok e Facebook.
*   **Design Responsivo:** A estrutura do CSS é preparada para se adaptar a diferentes tamanhos de tela.

## Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

*   **HTML5:** Para a estrutura e conteúdo semântico da página.
*   **CSS3:** Para a estilização e layout, com uma abordagem modular (componentes separados) e uso de variáveis CSS para facilitar a manutenção e padronização.

## Estrutura de Arquivos

```
.
├── css/
│   ├── components/       # Estilos específicos para componentes (header, footer, hero, etc.)
│   │   ├── footer.css
│   │   ├── header.css
│   │   ├── hero.css
│   │   ├── product-category.css
│   │   └── product-grid.css
│   ├── base.css          # Estilos base para elementos HTML
│   ├── reset.css         # Reset de estilos para consistência entre navegadores
│   ├── layout.css        # Estilos para o layout geral
│   └── variables.css     # Definição de variáveis CSS (cores, fontes, etc.)
├── images/
│   ├── banners/          # Imagens de banners
│   ├── icons/            # Ícones SVG
│   ├── logo/             # Logo do site
│   ├── products/         # Imagens dos produtos
├── index.html            # Página principal do site
└── README.md             # Este arquivo
```

## Como Usar

Para visualizar o site, basta abrir o arquivo `index.html` em qualquer navegador web moderno. Não é necessário nenhum servidor ou configuração adicional.

```bash
# Navegue até a pasta do projeto
cd ecommerce-syntaxwear

# Abra o arquivo index.html no seu navegador preferido
# Exemplo no Windows:
start index.html

# Exemplo no macOS:
open index.html

# Exemplo no Linux:
xdg-open index.html
```

## Customização

*   **Conteúdo HTML:** Edite o arquivo `index.html` para alterar textos, links, adicionar ou remover seções e produtos.
*   **Estilos CSS:**
    *   Para estilos globais, modifique `base.css`, `layout.css`, `reset.css` e `variables.css`.
    *   Para estilos de componentes específicos, edite os arquivos `.css` dentro da pasta `css/components/`.
    *   As variáveis em `variables.css` são ideais para alterar cores e fontes rapidamente em todo o site.
*   **Imagens:** Substitua as imagens nas pastas correspondentes (`images/banners`, `images/icons`, `images/logo`, `images/products`) para personalizar os visuais.

## Créditos

Desenvolvido como um projeto de vitrine.
```
