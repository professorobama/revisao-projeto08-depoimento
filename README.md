# Projeto 08 (Trilha Simplificada) - Seção de Depoimentos com Colunas

Este projeto consolida os conhecimentos de componentização e layout, aplicando Flexbox para criar uma seção de página com múltiplas colunas responsivas.

## 🚀 Sobre o Projeto

O projeto consiste em uma seção de depoimentos que exibe três cards lado a lado. O objetivo é praticar a composição de um layout de seção a partir de componentes menores e utilizar padrões modernos de Flexbox para criar um design de colunas que se adapta a diferentes tamanhos de tela.

## 🛠️ Tecnologias e Conceitos Abordados

- **HTML5 Semântico**:
  - Introdução às tags `<blockquote>` (para citações) e `<cite>` (para a fonte da citação).
  - Uso de `<section>` e `<article>` para estruturar o conteúdo.
- **CSS3 Flexbox**:
  - **Layout de Colunas Responsivas**: Uso combinado de `flex-wrap: wrap` no container e a propriedade `flex: 1 1 300px` nos itens.
  - `justify-content: center`: Para alinhar itens em linhas que não estão completas.
- **Componentização**:
  - Estilização de um componente "card" reutilizável.
  - Combinação de múltiplos componentes para formar uma seção de página.
- **Estilização de Imagens**:
  - Criação de avatares circulares com `border-radius: 50%`.

## 💻 Como Executar

1. Crie uma pasta `assets` e coloque algumas fotos de perfil nela.
2. Atualize os caminhos das imagens nos atributos `src` das tags `<img>`.
3. Abra o arquivo `index.html` em seu navegador e redimensione a janela para ver o layout se adaptar.
