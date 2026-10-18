# Atividade 1 — Existência e Classificação de Triângulos

## Objetivo e Conceitos Aplicados
Algoritmo em C++ que valida 3 comprimentos positivos, verifica a **Desigualdade Triangular** ($a + b > c \land a + c > b \land b + c > a$) e classifica o triângulo:
- **Quanto aos lados:** Equilátero, Isósceles ou Escaleno;
- **Quanto aos ângulos (Teorema de Pitágoras):** Retângulo ($a^2 = b^2 + c^2$), Acutângulo ($a^2 < b^2 + c^2$) ou Obtusângulo ($a^2 > b^2 + c^2$).

## Como Compilar e Executar
```bash
g++ main.cpp -o a1_triangulos -Wall
./a1_triangulos
```