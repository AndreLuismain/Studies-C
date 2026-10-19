# Atividade 5 — Banco de Dados em Memória com Vetor de Registros

## Objetivo e Conceitos Aplicados
Gerenciamento de até `1.000` contatos (`typedef struct Pessoa`) sincronizado com o arquivo `bancodedados.txt` (delimitado por `"FIM"`), suportando inserção, busca por nome, listagem, exclusão lógica (`valido = false`) e persistência ao encerrar.

## Como Compilar e Executar
```bash
g++ main.cpp -o a5_registros -Wall
./a5_registros
```
