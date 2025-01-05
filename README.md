# Sistema de Controle de Cartão de Crédito

Este projeto em Java simula um sistema básico de controle de cartão de crédito, onde o usuário pode registrar compras, verificar o saldo disponível e listar todas as compras realizadas.

## Estrutura do Projeto

O projeto é composto por três classes principais:

1. **Principal**: Contém o método `main` que executa a aplicação, permitindo a interação do usuário com o sistema.
2. **CartaoDeCredito**: Gerencia o limite do cartão, o saldo disponível e o registro das compras.
3. **Compra**: Representa cada compra realizada, contendo descrição, valor e métodos para ordenação.

---

## Funcionalidades

1. **Registrar Compras**: O sistema permite registrar compras, verificando se há saldo suficiente.
2. **Ordenação de Compras**: As compras são ordenadas pelo valor antes de serem exibidas.
3. **Exibição de Saldo**: O saldo disponível no cartão é exibido ao final da execução.

---

## Como Executar

1. Certifique-se de ter o Java instalado na sua máquina.
2. Copie o código para arquivos `.java` separados:
   - `Principal.java`
   - `CartaoDeCredito.java`
   - `Compra.java`
3. Compile os arquivos utilizando o comando:
   ```bash
   javac Principal.java CartaoDeCredito.java Compra.java
