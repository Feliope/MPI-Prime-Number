# MPI Prime Number Checker

Este repositório contém um projeto desenvolvido para a disciplina de **Programação Paralela**, parte do curso de **Ciência da Computação** da **Universidade Federal Fluminense (UFF)**. O objetivo do trabalho é aplicar técnicas de paralelismo utilizando **MPI (Message Passing Interface)** para verificar a primalidade de números inteiros em um intervalo determinado.

## 💡 Objetivo

Implementar uma solução em C utilizando MPI para distribuir a tarefa de verificação de números primos entre múltiplos processos, explorando o processamento paralelo para melhorar a performance em comparação com abordagens sequenciais.

## 🛠 Tecnologias e Ferramentas

- **Linguagem:** C
- **Paralelismo:** MPI (Message Passing Interface)
- **Compilador:** `mpicc`
- **Execução:** `mpirun` ou `mpiexec`

## 🚀 Como Compilar e Executar

1. **Compilar o código:**
   ```bash
   mpicc Bag_Of_Tasks.c -o Bag_Of_Tasks
   ou
   mpicc Naive.c -o Naive
2. **Executar o código:**
    ```bash
    mpirun -np 4 ./Bag_Of_Tasks 1 10000
    ou
    mpirun -np 4 ./Naive 1 10000
    
## 📈 Desempenho

Com a paralelização via MPI, espera-se uma redução significativa no tempo de execução em comparação à versão sequencial, especialmente para intervalos grandes. A divisão de trabalho entre os processos segue uma estratégia simples de balanceamento de carga por faixa de valores.

## 📌 Requisitos

1. Ambiente com MPI instalado
2. Sistema Linux (recomendado)

## 📄 Licença

Este projeto é acadêmico e está disponível sob a licença MIT. Sinta-se livre para estudar, modificar e utilizar o código conforme necessário.

## 👨‍💻 Autores
**[@Feliope](https://github.com/Feliope)**
**[@DaviLopes99](https://github.com/Davidlopes99)**
**[@felipemsalles](https://github.com/felipemsalles)**
