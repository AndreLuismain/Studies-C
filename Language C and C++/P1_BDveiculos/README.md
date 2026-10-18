# Projeto 1 (P1) — Sistema de Banco de Dados de Veículos (`P1_BDveiculos`)

Aplicação console desenvolvida em **C++** para gerenciamento persistente e análise estatística de uma base de até 100 veículos automotores (`BD_veiculos.txt`).

---

## 1. Objetivo e Funcionalidades

Implementar um sistema completo de cadastro, consulta, filtragem e persistência em arquivo texto plano utilizando vetores de registros (`typedef struct Veiculo`), atendendo aos seguintes requisitos:

1. **Inclusão de Veículo:** Cadastro de novos registros no vetor em memória.
2. **Busca por Placa com Exclusão:** Localização exata pela chave `placa` e remoção lógica (`valido = false`).
3. **Filtro por Tipo:** Listagem de veículos por categoria (`Hatch`, `Sedan`, `SUV`, `Picape`, etc.).
4. **Filtro por Câmbio:** Listagem por modalidade de transmissão (`Manual`, `Automatico`).
5. **Filtro por Faixa de Valor:** Busca por intervalo fechado $[\text{valor}_{\min}, \text{valor}_{\max}]$.
6. **Relatório Estatístico da Base:** Contabilização percentual por tipo, câmbio e métricas financeiras da frota.

---

## 2. Conceitos de Engenharia Aplicados

* **Modelagem Heterogênea (`struct`):** Agrupamento de 14 atributos (`modelo`, `marca`, `tipo`, `ano`, `quilometragem`, `potencia`, `combustivel`, `cambio`, `direcao`, `cor`, `portas`, `placa`, `valor`, `valido`).
* **Persistência em Arquivo (`<fstream>`):** Carga inicial via `ifstream("BD_veiculos.txt")` com sentinela `"FIM"` e regravação atualizada via `ofstream` ao encerrar a sessão.
* **Exclusão Lógica (Tombstone Flag):** Uso do campo booleano `valido` para desativar registros excluídos em $O(1)$ sem necessidade de deslocamento imediato em memória, filtrando-os no momento da serialização final.

---

## 3. Como Compilar e Executar

```powershell
cd "Language C and C++/P1_BDveiculos"
g++ main.cpp -o bd_veiculos -Wall
./bd_veiculos
```
*(Certifique-se de executar o binário no mesmo diretório do arquivo `BD_veiculos.txt`).*
