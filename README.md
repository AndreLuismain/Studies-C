# Fundamentos de Ciência da Computação e Algoritmos em C & C++ (`Studies-C`)

<div align="center">

[![C](https://img.shields.io/badge/C-ANSI%20%7C%20C11-A8B9CC.svg?style=for-the-badge&logo=c&logoColor=black)](https://en.cppreference.com/w/c)
[![C++](https://img.shields.io/badge/C%2B%2B-17%20%7C%20STL-00599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://en.cppreference.com/w/cpp)
[![GCC](https://img.shields.io/badge/Compiler-GCC%20%2F%20G%2B%2B-F05033.svg?style=for-the-badge&logo=gnu&logoColor=white)](https://gcc.gnu.org/)

</div>

Repositório de **Fundamentos de Ciência da Computação, Algoritmos e Estruturas de Dados I (AEDS I)** em **C e C++**, desenvolvido por **André Luís**. Documenta toda a trilha de base computacional: desde controle de fluxo elementar, manipulação direta de arrays de caracteres (`char[]` / ASCII) e operações de conjuntos até sistemas completos de gerenciamento de registros (`struct`) com persistência em arquivos e análise experimental de métodos de ordenação.

---

## 🧭 Catálogo Geral e Índice de Navegação

### 1. Projetos Práticos de Laboratório (`Language C and C++/AEDS-1-pratica`)
> Documentação consolidada do diretório: **[`AEDS-1-pratica/README.md`](./Language%20C%20and%20C++/AEDS-1-pratica/README.md)**

| Pasta / Projeto | Linguagem | Conceitos de Engenharia Aplicados | Status |
|---|---|---|---|
| **[`Banco de Dados de veiculos/`](./Language%20C%20and%20C++/AEDS-1-pratica/Banco%20de%20Dados%20de%20veiculos/)** | C++ | Modelagem de `struct Veiculo` (14 atributos), persistência em arquivo (`BD_veiculos.txt`), exclusão lógica (*tombstone flag*), buscas por placa/tipo/câmbio/faixa de preço e relatório estatístico. | ✅ Concluído |
| **[`Agenda Incluir, Excluir e buscar/`](./Language%20C%20and%20C++/AEDS-1-pratica/Agenda%20Incluir,%20Excluir%20e%20buscar/)** | C++ | Sistema CRUD de contatos (`struct Amigo`), leitura e escrita sequencial com `ifstream`/`ofstream` (`agenda.txt`) e remoção lógica sem realocação imediata. | ✅ Concluído |
| **[`Calculadora de Formas Geomtricas/`](./Language%20C%20and%20C++/AEDS-1-pratica/Calculadora%20de%20Formas%20Geomtricas/)** | C++ | Modularização com funções parametrizadas (`calcular_area`, `calcular_volume`), parsing de linhas via `stringstream` e processamento em lote de cenas gráficas 2D/3D. | ✅ Concluído |
| **[`Conhecendo Vetores 1/`](./Language%20C%20and%20C++/AEDS-1-pratica/Conhecendo%20Vetores%201/)** | C++ | Algoritmos de Teoria dos Conjuntos sobre arrays estáticos: deduplicação de elementos, conjunto **União** ($A \cup B$) e conjunto **Interseção** ($A \cap B$). | ✅ Concluído |
| **[`Conhecendo Vetores 2/`](./Language%20C%20and%20C++/AEDS-1-pratica/Conhecendo%20Vetores%202/)** | C++ | Geração pseudo-aleatória (`srand`/`rand`) de 1.000 elementos em $[100, 200]$, busca sequencial de índices, contagem de frequência e filtro por intervalo. | ✅ Concluído |
| **[`média de 1000 valores/`](./Language%20C%20and%20C++/AEDS-1-pratica/média%20de%201000%20valores/)** | C++ | Simulação estatística de 1.000 alturas em ponto flutuante (`float`), determinação de máximo/mínimo, média aritmética e filtragem condicional em $O(n)$. | ✅ Concluído |
| **[`adivinhe o numero/`](./Language%20C%20and%20C++/AEDS-1-pratica/adivinhe%20o%20numero/)** | C++ | Controle de fluxo interativo (`while`), validação de limites de entrada (`[1, 100]`), realimentação direcional (maior/menor) e contagem de iterações. | ✅ Concluído |
| **[`teste/`](./Language%20C%20and%20C++/AEDS-1-pratica/teste/)** | C | Exercício introdutório de sintaxe C (`stdio.h`), laço contado (`for`) e instrução de desvio de iteração (`continue`). | ✅ Concluído |

---

### 2. Atividades Avaliativas e Análise de Ordenação (`Language C and C++/xxx/Atividades`)
> Documentação consolidada do diretório: **[`xxx/Atividades/README.md`](./Language%20C%20and%20C++/xxx/Atividades/README.md)**

| Pasta / Projeto | Linguagem | Conceitos de Engenharia Aplicados | Status |
|---|---|---|---|
| **[`A1_Formartriangulos/`](./Language%20C%20and%20C++/xxx/Atividades/A1_Formartriangulos/)** | C++ | Validação de Desigualdade Triangular, classificação geométrica (Equilátero, Isósceles, Escaleno) e trigonométrica via Pitágoras (Retângulo, Acutângulo, Obtusângulo). | ✅ Concluído |
| **[`A2_Geradoralturas/`](./Language%20C%20and%20C++/xxx/Atividades/A2_Geradoralturas/)** | C++ | Geração estocástica de 1.000 amostras, acumuladores em passagem única ($O(n)$) e cálculo de distribuição percentual. | ✅ Concluído |
| **[`A3_Cenagrafica/`](./Language%20C%20and%20C++/xxx/Atividades/A3_Cenagrafica/)** | C++ | Leitura de especificações geométricas em arquivo (`cenagrafica.txt`) com sentinela `"fim"` e cálculo acumulado de áreas superficiais e volumes 3D. | ✅ Concluído |
| **[`A4_Opvetores/`](./Language%20C%20and%20C++/xxx/Atividades/A4_Opvetores/)** | C++ | Manipulação avançada de vetores (1.000 posições): inversão *in-place* ($O(n)$), exclusão de elemento com *left-shift* e eliminação de duplicatas. | ✅ Concluído |
| **[`A5_Vetoregistros/`](./Language%20C%20and%20C++/xxx/Atividades/A5_Vetoregistros/)** | C++ | Banco de dados em memória de até 1.000 registros (`typedef struct Pessoa`) sincronizado com `bancodedados.txt`. | ✅ Concluído |
| **[`AInvertida-1caracteres/`](./Language%20C%20and%20C++/xxx/Atividades/AInvertida-1caracteres/)** | C | Manipulação manual de strings C (`char[]` terminado em `'\0'`) sem `<string.h>`: concatenação manual e conversão de caixa via aritmética ASCII ($\pm 32$). | ✅ Concluído |
| **[`Ainvertida-2conjuntos/`](./Language%20C%20and%20C++/xxx/Atividades/Ainvertida-2conjuntos/)** | C++ | Deduplicação *in-place* com deslocamento de memória e construção de vetores de União e Interseção. | ✅ Concluído |
| **[`Relatório Métodos de Ordenação - AEDS I.pdf`](./Language%20C%20and%20C++/xxx/Atividades/Relatório%20Métodos%20de%20Ordenação%20-%20AEDS%20I.pdf)** | PDF | Estudo comparativo de complexidade e desempenho entre *Bubble Sort*, *Selection Sort* e *Insertion Sort*. | ✅ Concluído |

---

### 3. Outros Módulos e Acervo Teórico

| Diretório | Conteúdo |
|---|---|
| **[`Language C and C++/P1_BDveiculos/`](./Language%20C%20and%20C++/P1_BDveiculos/)** | Entrega principal (P1) do sistema de gerenciamento e estatísticas de base de dados de veículos em C++. |
| **[`Language C and C++/Projetos-1-2024/`](./Language%20C%20and%20C++/Projetos-1-2024/)** | Snapshot consolidado dos projetos práticos desenvolvidos no semestre 2024/1. |
| **[`Language C and C++/AEDS-1-teorico/`](./Language%20C%20and%20C++/AEDS-1-teorico/)** | Coleção de **19 apostilas teóricas em PDF** cobrindo desde Arquitetura Simplificada e Tipos Primitivos até Registros (`struct`), Arquivos, Modularização e Ponteiros (`01` a `18`). |

---

## 🚀 Como Compilar e Executar Qualquer Projeto

Certifique-se de possuir o compilador **GCC / G++** instalado (`g++ --version`).

```powershell
# Exemplo 1: Compilar e executar o Banco de Dados de Veículos (P1)
cd "Language C and C++/P1_BDveiculos"
g++ main.cpp -o bd_veiculos -Wall
./bd_veiculos

# Exemplo 2: Compilar e executar Operações em Vetores (Atividade 4)
cd "Language C and C++/xxx/Atividades/A4_Opvetores"
g++ main.cpp -o op_vetores -Wall
./op_vetores
```

---

## 👤 Autor

**André Luís da Silva Souza**  
Graduando em Sistemas de Informação — **ICMC · Universidade de São Paulo (USP)**  
- GitHub: [@AndreLuismain](https://github.com/AndreLuismain)
- Email: [andreluis.souza@usp.br](mailto:andreluis.souza@usp.br)
