# Aula Invertida 1 — Manipulação de Cadeias de Caracteres (`char[]` e ASCII)

## Objetivo e Conceitos Aplicados
Implementação manual de algoritmos de processamento de strings em C (`char[]` terminado em nulo `'\0'`) sem funções prontas de `<string.h>`:
- Concatenação manual de nome e sobrenome;
- Conversão entre maiúsculas e minúsculas via aritmética direta na **Tabela ASCII** ($\pm 32$);
- Capitalização seletiva de iniciais e busca posicional de caracteres.

## Como Compilar e Executar
```bash
gcc main.cpp -o caracteres -Wall
./caracteres
```