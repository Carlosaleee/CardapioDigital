# 🌊 Parada do Surf - Cardápio Digital

![Status do Projeto](https://img.shields.io/badge/Status-Em_Desenvolvimento-blue)
![Versão](https://img.shields.io/badge/Versão-1.0-green)

O **Parada do Surf** é um cardápio digital interativo e responsivo desenvolvido para facilitar pedidos em pizzarias e restaurantes via WhatsApp. Com uma interface moderna, o sistema permite que o cliente escolha produtos, gerencie o carrinho e envie o pedido formatado diretamente para o estabelecimento.

## ✨ Funcionalidades

- **Categorização Inteligente:** Filtros por categorias (Tradicionais, Especiais, Bebidas, etc).
- **Carrinho de Compras em Tempo Real:** Adição, remoção e cálculo automático de subtotal e taxa de entrega.
- **Checkout Integrado:** Formulário de endereço e escolha de forma de pagamento com cálculo de troco.
- **Integração com WhatsApp:** Envio automático da comanda formatada para o número do estabelecimento.
- **Design Responsivo:** Otimizado para celulares, tablets e computadores usando Tailwind CSS.
- **Limpeza de Dados:** Opção de "Limpar e Reiniciar" para esvaziar o carrinho rapidamente.

## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando tecnologias modernas de front-end:

* [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML) - Estrutura semântica.
* [Tailwind CSS](https://tailwindcss.com/) - Estilização moderna e utilitária.
* [JavaScript (Vanilla)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) - Lógica do carrinho e manipulação do DOM.
* [Font Awesome](https://fontawesome.com/) - Ícones da interface.
* [Google Fonts](https://fonts.google.com/) - Tipografia (Poppins).

## 🛠️ Como usar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/parada-do-surf.git](https://github.com/seu-usuario/parada-do-surf.git)
    ```
2.  **Configuração:**
    Abra o arquivo `index.html` e localize a constante `CONFIG` no início do script para alterar o número do WhatsApp e a taxa de entrega:
    ```javascript
    const CONFIG = {
        NOME: "Pizzaria Parada do Surf",
        WHATSAPP: "5513997700927",
        TAXA_ENTREGA: 5
    };
    ```
3.  **Execução:**
    Basta abrir o arquivo `index.html` em qualquer navegador moderno. Não é necessário servidor back-end ou instalação de dependências, pois o Tailwind é carregado via CDN.

## 📦 Estrutura de Arquivos

```text
├── img/                # Imagens do sistema (logo, capas, produtos)
├── index.html          # Arquivo principal (HTML + JS + CSS)
└── README.md           # Documentação do projeto
