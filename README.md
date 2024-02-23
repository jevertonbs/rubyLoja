**Sistema de Supermercado**

---

### Descrição

O **Sistema de Supermercado** é uma aplicação de exemplo que simula a compra de produtos em um supermercado. Ele demonstra o uso de classes e objetos em Ruby para modelar produtos e interações de compra em um ambiente de supermercado.

### Arquivos

O sistema é composto por três arquivos principais:

1. **app.rb**: Este é o arquivo principal da aplicação, onde a lógica de execução é definida. Ele cria uma instância de um produto e passa suas informações para a classe Mercado para realizar a compra.

2. **produto.rb**: Este arquivo contém a definição da classe Produto, que representa um produto disponível para compra. Ele possui atributos como nome e preço.

3. **mercado.rb**: Este arquivo contém a definição da classe Mercado, que representa o ambiente de compra. Ele recebe as informações do produto e imprime uma mensagem indicando que o produto foi comprado.

### Como Usar

Para executar a aplicação, basta rodar o arquivo `app.rb`. Isso criará um produto com nome e preço definidos e simulará uma compra no supermercado.

### Exemplo de Uso

```ruby
# Cria um produto
produto = Produto.new
produto.nome = "PS5 1TB"
produto.preco = 5000.99

# Realiza a compra no mercado
Mercado.new(produto.nome, produto.preco).comprar
```

### Recursos Adicionais

Este sistema de supermercado é um exemplo simples de como usar classes e objetos em Ruby para modelar um cenário do mundo real. Ele pode ser expandido e personalizado para incluir mais funcionalidades, como carrinho de compras, estoque de produtos e métodos de pagamento.

---

Com o **Sistema de Supermercado**, você pode explorar os conceitos fundamentais de programação orientada a objetos em Ruby e criar aplicações mais complexas e funcionais baseadas nesses princípios. Divirta-se explorando e expandindo este exemplo para atender às suas necessidades!
