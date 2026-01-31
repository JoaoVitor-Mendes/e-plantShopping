# 🌿 Paradise Nursery – Shopping Cart Application

**Paradise Nursery** é um aplicativo de compras on-line focado em plantas de interior.  
A aplicação permite que os usuários naveguem por diferentes categorias de plantas, adicionem itens ao carrinho, ajustem quantidades e visualizem dinamicamente o custo total antes do checkout.

Este projeto foi desenvolvido como **projeto final**, aplicando conceitos de desenvolvimento front-end, componentização e gerenciamento de estado.

---

## 🚀 Funcionalidades

### 🏠 Página de Destino (Landing Page)
- Imagem de fundo
- Nome da empresa *Paradise Nursery*
- Parágrafo descritivo sobre a empresa
- Botão **Começar**, que direciona para a página de produtos

### 🌱 Página de Listagem de Produtos
- Exibição de **no mínimo 6 plantas de interior**
- Produtos organizados em **3 ou mais categorias**
- Cada planta possui:
  - Imagem em miniatura
  - Nome
  - Preço
  - Botão **Adicionar ao Carrinho**
- Cabeçalho com:
  - Ícone de carrinho de compras
  - Contador dinâmico com o total de itens no carrinho
  - Navegação entre páginas

### 🛒 Página do Carrinho de Compras
- Exibição detalhada dos itens no carrinho:
  - Miniatura da planta
  - Nome
  - Preço unitário
  - Quantidade
- Funcionalidades do carrinho:
  - Aumentar e diminuir quantidade de itens
  - Remover item do carrinho
  - Atualização dinâmica do total de itens
  - Atualização dinâmica do valor total da compra
- Botões:
  - **Continuar Comprando**
  - **Finalizar Compra**

---

## 🛠️ Tecnologias Utilizadas

- **React**
- **JavaScript (ES6+)**
- **HTML5**
- **CSS3**
- **Node.js**
- **Git & GitHub**
- **GitHub Pages** (deploy)

---

## 📁 Estrutura do Projeto

```text
src/
├── components/
│   ├── Header/
│   ├── ProductList/
│   ├── ProductCard/
│   ├── Cart/
│   └── CartItem/
├── pages/
│   ├── LandingPage.js
│   ├── ProductsPage.js
│   └── CartPage.js
├── data/
│   └── products.js
├── App.js
└── index.js
