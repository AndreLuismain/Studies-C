# Sistema CRUD de Agenda de Contatos (`struct Amigo`)

## Objetivo e Conceitos Aplicados
Implementação em C++ de um gerenciador de contatos persistido em arquivo texto (`agenda.txt`), utilizando:
- Modelagem de registro heterogêneo (`struct Amigo`) com flag de controle (`bool valido`) para **exclusão lógica** (*tombstone*);
- Leitura e gravação sequencial via `<fstream>` (`ifstream` e `ofstream`);
- Menu interativo para inclusão, busca por nome, listagem de registros ativos e remoção lógica.

## Como Compilar e Executar
```bash
g++ main.cpp -o agenda -Wall
./agenda
```