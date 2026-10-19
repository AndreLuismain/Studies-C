# Calculadora de Formas Geométricas Planas e Espaciais

## Objetivo e Conceitos Aplicados
Processador geométrico modularizado em C++ que lê descrições de cenas gráficas a partir de arquivo texto e calcula áreas superficiais e volumes:
- Modularização com funções dedicadas (`calcular_area`, `calcular_volume`);
- Parsing de parâmetros geométricos via `std::stringstream` e `<cmath>`.

## Como Compilar e Executar
```bash
g++ main.cpp -o geometria -Wall
./geometria
```
