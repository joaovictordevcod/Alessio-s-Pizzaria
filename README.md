# Alessio's Pizzaria - Projeto Final Fundamentos CSS (One Bit Code)

![Screenshot da página inicial da Alessio's Pizzaria](placeholder.png)
*(Substitua placeholder.png pelo caminho real para uma captura de tela do seu projeto)*

## 📝 Descrição

Este projeto é uma landing page simples para uma pizzaria fictícia chamada "Alessio's Pizzaria". Ele apresenta seções como Home (com um hero banner), Cardápio (exibindo diferentes pizzas em cards), Sobre Nós e Contato.

## 🎯 Propósito

Este site foi desenvolvido como a **solução para o desafio final do módulo de Fundamentos do CSS** da plataforma **One Bit Code**. O objetivo principal foi aplicar e reforçar os conceitos essenciais de CSS aprendidos durante o módulo.

## ✨ Funcionalidades

*   Navegação simples através de um cabeçalho fixo.
*   Seção "Hero" com imagem de fundo, título chamativo e botão "Call to Action".
*   Exibição do cardápio de pizzas utilizando cards estilizados.
*   Seção "Sobre Nós" com texto descritivo e imagem de fundo com gradiente.
*   Seção "Contato" com informações de endereço, telefone, e-mail e horário de funcionamento.
*   Rodapé com informações de copyright.
*   Navegação suave (`scroll-behavior: smooth;`) entre as seções ao clicar nos links do menu.
*   Design responsivo básico (através do uso de unidades relativas e `box-sizing`).

## 🛠️ Tecnologias Utilizadas

*   HTML5 (Estrutura semântica)
*   CSS3 (Estilização e Layout)

## 📚 Principais Conceitos de CSS Aplicados

Este projeto serviu como prática intensiva para diversos fundamentos de CSS, incluindo:

*   **Box Model:** Uso de `margin`, `padding`, `border`, `width`, `height` e, crucialmente, `box-sizing: border-box;` para um controle de layout mais intuitivo.
*   **Seletores:**
    *   **Básicos:** Seletor universal (`*`), de tipo (`h1`, `p`, `nav`), de classe (`.hero`, `.menu-list`), de ID (`#home`, `#about`).
    *   **Combinadores:** Descendente (`nav a`), filho (`address > *`).
    *   **Pseudo-classes:** `:not()` (ex: `section:not(#home)`).
    *   **Agrupamento:** `h3, p`.
*   **Cores e Fundos (Backgrounds):** Definição de cores (`color`, `background-color`), uso de imagens de fundo (`background-image`, `background-size`, `background-position`), e aplicação de gradientes (`linear-gradient`).
*   **Bordas (Borders):** Utilização de `border-radius` para cantos arredondados em botões e cards.
*   **Textos e Fontes:** Definição de `font-family`, `font-size`, `font-weight`, `text-align`, `text-decoration`, `font-style`.
*   **Display:** Controle do tipo de caixa de exibição com `display: inline`, `display: inline-block`.
*   **Variáveis CSS (Custom Properties):** Definição de variáveis globais (`:root`) para cores (`--color-primary`, `--color-dark`, etc.) e seu uso (`var()`) para fácil manutenção e consistência de tema.
*   **Unidades:** Uso de unidades relativas como `rem` e `vh`.
*   **Listas:** Estilização de listas (`list-style: none`).
*   **Sombras:** Aplicação de `box-shadow` para dar profundidade aos cards do menu.
*   **Ajuste de Objeto:** Uso de `object-fit: cover` para controlar como as imagens se ajustam dentro de seus contêineres.
*   **Reset CSS:** Aplicação de um reset básico (`* { margin: 0; padding: 0; box-sizing: border-box; }`) para garantir consistência entre navegadores.
*   **Scroll Behavior:** Implementação de `scroll-behavior: smooth;` para rolagem suave.

## 🚀 Como Executar

1.  Clone ou faça o download deste repositório.
2.  Navegue até a pasta do projeto.
3.  Abra o arquivo `index.html` em seu navegador web preferido.

## 🙏 Agradecimentos

*   Agradecimento à **One Bit Code** pelo excelente módulo de Fundamentos do CSS e pelo desafio proposto.
