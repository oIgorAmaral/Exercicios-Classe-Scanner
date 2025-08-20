# Calculadora Universal - Exercícios de Lógica em Java

Este projeto é uma aplicação de console desenvolvida em Java que reúne 6 exercícios básicos de programação. O objetivo principal é demonstrar a aplicação de conceitos fundamentais como a manipulação de entrada de dados do usuário, estruturas de controle (`do-while`, `switch-case`) e a modularização do código em diferentes classes.

## 🚀 Funcionalidades

O programa apresenta um menu interativo onde o usuário pode escolher qual cálculo realizar:

1.  **Soma de Quatro Números:** Recebe quatro números inteiros e exibe a soma.
2.  **Média Aritmética:** Recebe três notas e calcula a média simples.
3.  **Média Ponderada:** Recebe três notas com seus respectivos pesos e calcula a média ponderada.
4.  **Aumento Salarial Fixo:** Recebe um salário e aplica um aumento fixo de 25%.
5.  **Aumento Salarial Variável:** Recebe um salário e um percentual de aumento, e exibe o valor do aumento e o novo salário.
6.  **Salário Líquido:** Recebe um salário base e calcula o valor final a receber, aplicando uma gratificação de 5% e um imposto de 7%.

## 📂 Estrutura do Projeto

O código foi organizado de forma modular para promover a clareza e a separação de responsabilidades:

-   `CalculadoraUniversal.java`: Classe principal que contém o método `main`. Responsável por exibir o menu e gerenciar a escolha do usuário.
-   `SomaQuatroNumeros.java`, `MediaAritmetica.java`, etc.: Classes auxiliares, cada uma contendo a lógica específica para uma das funcionalidades do menu.

## 🛠️ Como Compilar e Executar

Siga os passos abaixo para executar o projeto localmente.

### Pré-requisitos
-   É necessário ter o **JDK (Java Development Kit)** instalado e configurado corretamente nas variáveis de ambiente do sistema (testado com Zulu JDK 21).

### Passos
1.  Clone este repositório para sua máquina local.
2.  Abra o terminal (CMD, PowerShell, etc.) e navegue até o diretório raiz do projeto.
    ```bash
    cd caminho/para/o/projeto
    ```
3.  Compile todos os arquivos fonte `.java`:
    ```bash
    javac *.java
    ```
4.  Execute o programa:
    ```bash
    java CalculadoraUniversal
    ```

## 💻 Tecnologias Utilizadas
-   **Java**
