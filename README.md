# 📱 Pokedex 1.0

Uma aplicação interativa que lista e detalha Pokémon, consumindo dados em tempo real da [PokeAPI](https://pokeapi.co/). Este projeto foi desenvolvido para praticar o consumo de APIs REST, manipulação de estados e estilização de componentes dinâmicos no frontend.

## 📋 Visão Geral

A Pokedex 1.0 permite aos usuários navegar por uma lista de Pokémon, visualizar suas estatísticas básicas, tipos e habilidades. É um projeto fundamental para demonstrar o fluxo de dados entre uma API externa e a interface do usuário.

## 🚀 Tecnologias Utilizadas

* **HTML5 / CSS3:** Estrutura e estilização (incluindo Grid e Flexbox para o layout dos cards).
* **JavaScript (ES6+):** Lógica de consumo da API (Fetch API), mapeamento de dados e renderização dinâmica.
* **PokeAPI:** A principal fonte de dados para todos os Pokémon, tipos e atributos.

## 🔧 Como Executar

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/tiagosantos0412/pokedex1.0.git](https://github.com/tiagosantos0412/pokedex1.0.git)
Acesse o diretório:

Bash
cd pokedex1.0
Inicie a aplicação:

Basta abrir o arquivo index.html em seu navegador ou utilizar a extensão Live Server no VS Code para uma melhor experiência de desenvolvimento.

🧪 Estratégia de Testes (QA View)
Como um projeto que depende de uma API externa, os seguintes pontos são validados nesta aplicação:

Integração de Dados: Verificação se os dados retornados pela PokeAPI (nome, imagem, tipo) estão sendo renderizados corretamente nos cards.

Performance de Carregamento: Avaliação do tempo de resposta ao carregar a lista inicial de Pokémon.

Tratamento de Erros: Validação de como a interface se comporta caso a API esteja fora do ar (Graceful degradation).

Responsividade: Garantia de que a grade de Pokémon se ajusta corretamente em dispositivos móveis e desktops.

📁 Estrutura de Pastas
/assets ou /img: Ícones e imagens auxiliares.

index.html: Estrutura principal da página.

style.css: Estilização dos cards e layout responsivo.

script.js: Toda a lógica de requisição assíncrona e manipulação do DOM.
