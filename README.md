# ProjetoBasicoJava
Este projeto foi desenvolvido em **Java** para aplicar os pilares da Programação Orientada a Objetos em um cenário de gestão bancária.

## Tech Stack & Conceitos

### Linguagem & Core
* **Java**
* **Console I/O**: Interação via terminal utilizando `java.io.PrintStream` e formatação de saída (`String.format`) para exibir saldos com precisão decimal.

### Programação Orientada a Objetos (POO)
* **Encapsulamento**: Proteção dos dados da conta (`Saldo`, `Cpf`) através de métodos acessores (Getters/Setters) e validação de regras de negócio (ex: impedir saques maiores que o saldo).
* **Composição**: A classe `Banco` gerencia uma coleção de objetos da classe `contaCorrente`, demonstrando o relacionamento "tem-um".

### Estruturas de Dados
* **Java Collections Framework**: Utilização de `java.util.ArrayList` para gerenciamento dinâmico da lista de correntistas, permitindo adição e remoção de contas em tempo de execução.
* **Iterators**: Uso de `java.util.Iterator` para percorrer a lista de clientes de forma segura e eficiente.
