🛍️ Projeto: Ordenação de Produtos com Lambda (Java)

Este é um pequeno projeto Java que demonstra como ordenar uma lista de produtos usando expressões lambda. Ele mostra o poder da programação funcional em Java para escrever código mais conciso e legível.
📦 Estrutura do Projeto

O projeto possui três classes:
✅ Product (entities.Product)

Representa um produto com os atributos:

    name (String): nome do produto

    price (Double): preço do produto

Inclui métodos getters/setters e toString() para exibição formatada.
✅ Program (app.Program)

Classe principal que:

    Cria uma lista de produtos.

    Usa lambda para ordenar os produtos alfabeticamente pelo nome, ignorando maiúsculas/minúsculas.

    Imprime os produtos ordenados no console.

Exemplo da ordenação com lambda:

list.sort((p1, p2) -> p1.getName().toUpperCase().compareTo(p2.getName().toUpperCase()));

✅ MyComparator (app.MyComparator)

Um comparador de produtos (implementa Comparator<Product>) que faz exatamente a mesma ordenação que a lambda, 
mas foi deixado fora da execução principal para fins didáticos.

🖨️ Exemplo de Saída

Notebook: 1200.0
Tablet: 450.0
TV: 900.0

🚀 Como Executar

    Compile o projeto:

javac app/*.java entities/*.java

    Execute a aplicação:

java app.Program

📚 Conceitos Usados

    Programação funcional com lambda

    Interface Comparator

    API de coleções do Java (List, ArrayList)

    Encapsulamento com getters/setters





