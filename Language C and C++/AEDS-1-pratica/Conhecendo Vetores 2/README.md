# Conhecendo Vetores 2 — Geração Pseudoaleatória e Buscas em Vetores

## Objetivo e Conceitos Aplicados
Manipulação de um vetor de `1.000` posições preenchido com inteiros pseudoaleatórios no intervalo $[100, 200]$:
- Inicialização de semente com `srand(time(NULL))` e `rand()`;
- Busca sequencial de índices, contagem de frequência de ocorrências e filtragem por subintervalo.

## Como Compilar e Executar
```bash
g++ main.cpp -o vetores2 -Wall
./vetores2
```