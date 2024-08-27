# Loja Online - Projeto de E-commerce Minimalista

## Descrição do Projeto

Este projeto é uma implementação de uma loja online minimalista, desenvolvida com foco em performance, usabilidade e design clean. A aplicação oferece uma experiência de compra fluida, com funcionalidades como listagem de produtos, carrinho de compras e processo de checkout.

## Tecnologias Utilizadas

- **HTML5**: Estruturação semântica da página.
- **CSS3**: Estilização avançada com uso de Flexbox e Grid para layouts responsivos.
- **JavaScript (ES6+)**: Lógica de negócios e interatividade do cliente.
- **Fake Store API**: API REST para simulação de dados de produtos.

## Características Principais

1. **Design Responsivo**: Adaptável a diferentes tamanhos de tela.
2. **Carregamento Lazy e Infinito**: Melhora a performance e experiência do usuário.
3. **Filtro e Ordenação de Produtos**: Facilita a busca e organização dos itens.
4. **Carrinho de Compras Interativo**: Permite adição, remoção e ajuste de quantidades.
5. **Processo de Checkout**: Inclui cálculo de frete baseado no CEP (simulado).
6. **Animações Suaves**: Proporciona uma experiência visual agradável.

## Técnicas e Padrões Utilizados

### JavaScript Moderno (ES6+)

- **Classes**: Utilização extensiva de classes para estruturar o código (ex: `Product`, `CartItem`, `ShoppingCartUseCase`).
- **Módulos**: Organização do código em módulos para melhor manutenção (implícito na estrutura do projeto).
- **Arrow Functions**: Usado para callbacks e métodos curtos.
- **Template Literals**: Para geração dinâmica de HTML.
- **Destructuring**: Utilizado em vários pontos para uma sintaxe mais limpa.
- **Promises e Async/Await**: Para operações assíncronas, especialmente na comunicação com a API.

### Padrões de Projeto

- **Repository Pattern**: Implementado nas classes `ProductRepository` e `CartRepository`.
- **Use Case Pattern**: Encapsulamento da lógica de negócios na classe `ShoppingCartUseCase`.
- **Observer Pattern**: Utilizado na implementação do carregamento infinito.

### API e Comunicação Assíncrona

- Uso do `fetch` API para requisições HTTP.
- Implementação de tratamento de erros nas chamadas à API.

### Manipulação do DOM

- Uso de métodos modernos para manipulação do DOM, como `querySelector` e `addEventListener`.
- Criação dinâmica de elementos HTML para uma melhor performance.

### Otimização de Performance

- Implementação de carregamento lazy para imagens.
- Paginação infinita para carregar produtos sob demanda.
- Uso de debounce na função de busca para otimizar chamadas à API.

### Acessibilidade

- Uso de tags semânticas do HTML5 para melhorar a acessibilidade.
- Implementação de estados focáveis para navegação por teclado.

## Como Executar o Projeto

1. Clone o repositório para sua máquina local.
2. Abra o arquivo `index.html` em um navegador moderno.
3. Para desenvolvimento, recomenda-se o uso de um servidor local como Live Server do VS Code.

## Contribuições

Contribuições são bem-vindas! Por favor, leia o arquivo CONTRIBUTING.md (a ser criado) para detalhes sobre nosso código de conduta e o processo para enviar pull requests.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE.md para detalhes.