# Sistema de Gerenciamento de Frota de Veículos (`struct Veiculo`)

## Objetivo e Conceitos Aplicados
Aplicação em C++ para gerenciamento de até 100 registros automotivos persistidos em `BD_veiculos.txt`:
- `struct Veiculo` com 14 atributos (modelo, marca, tipo, ano, quilometragem, potência, combustível, câmbio, direção, cor, portas, placa, valor e flag `valido`);
- Buscas por placa, tipo de carroceria, câmbio e faixa de preço `[min, max]`;
- Relatório estatístico com percentuais por categoria/combustível, veículo mais barato de potência $1.0$ e veículo mais caro com direção hidráulica e câmbio automático.

## Como Compilar e Executar
```bash
g++ main.cpp -o veiculos -Wall
./veiculos
```