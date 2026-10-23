# Computação Escalável — Processamento Paralelo e Distribuído de Dados

Repositório destinado ao trabalho prático da disciplina de **Computação Escalável** (6° semestre do curso de Ciência de Dados e Inteligência Artificial — Universidade Estadual de Londrina - UEL).

---

## Visão Geral do Projeto

O objetivo principal deste projeto é implementar dois algoritmos de mineração/processamento de dados em ambiente paralelo ou distribuído e realizar uma análise de **escalabilidade** e **eficiência** computacional conforme o volume de dados aumenta.

### Tarefa e Algoritmos Escolhidos
* **Tarefa:** Classificação Supervisionada
* **Algoritmos:**
    * **Naive Bayes**
    * **Regressão Logística**

A solução será submetida a testes de escalabilidade variando o tamanho das bases de dados (de 10.000 a 150.000 registros), avaliando o tempo de execução sob uma mesma interface padronizada.

---

## Integrantes e Divisão de Responsabilidades

Conforme os requisitos da disciplina, o desenvolvimento foi dividido em duplas responsáveis por cada algoritmo:

| Integrante | GitHub | Responsabilidade |
| :--- | :--- | :--- |
| **Guilherme Costanzi** | [@guihcostanzi](https://github.com/guihcostanzi) | Dupla 1 — Naive Bayes |
| **Rafael Figueiredo Cobo** | [@rfcob](https://github.com/rfcob) | Dupla 1 — Naive Bayes |
| **Mateus Panunci Gonçalves** | [@MateusPanunci](https://github.com/MateusPanunci) | Dupla 2 — Regressão Logística |
| **Alexandre da Silva Marchioli** | [@asmarchioli](https://github.com/asmarchioli) | Dupla 2 — Regressão Logística |

---

## Tecnologias e Ambiente

* **Linguagem / Framework:** *(A definir: Java com `ExecutorService`/`ForkJoin` ou Scala com Apache Spark)*
* **Ambiente de Execução:** Local (recursos e threads controlados na mesma máquina física)

---

## Cronograma e Entregas

* **25/10:** Submissão do repositório inicial e registro dos temas.
* **12/11:** Entrega do código-fonte, scripts de benchmark e relatório técnico final.
* **13/11:** Apresentação final do projeto em aula.

---

> *Nota: Os códigos de implementação dos algoritmos, os scripts de automação dos experimentos e as instruções detalhadas de compilação/execução serão disponibilizados neste repositório até o dia **12/11**.*
