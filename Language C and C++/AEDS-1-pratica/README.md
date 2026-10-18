# Algoritmos e Estruturas de Dados I — Laboratórios Práticos (`AEDS-1-pratica`)

Este diretório reúne os projetos práticos de laboratório desenvolvidos em **C e C++** na disciplina de **Algoritmos e Estruturas de Dados I (AEDS I)**, abordando entrada/saída de arquivos (`ifstream`/`ofstream`), registros (`struct`), manipulação de vetores estáticos, operações de conjuntos e geração de números pseudo-aleatórios.

---

## 🧭 Catálogo de Projetos do Diretório

| Subpasta / Projeto | Arquivo Principal | Objetivo e Lógica Implementada | Conceitos Aplicados | Comando de Compilação e Execução |
|---|---|---|---|---|
| **[`Agenda Incluir, Excluir e buscar/`](./Agenda%20Incluir,%20Excluir%20e%20buscar/)** | `main.cpp`, `agenda.txt` | Sistema CRUD de agenda de contatos persistido em arquivo texto (`agenda.txt`) utilizando `struct Amigo` e exclusão lógica (`bool valido`). | `struct`, `ifstream`/`ofstream`, Vetor de Registros, Exclusão Lógica. | `g++ main.cpp -o agenda && ./agenda` |
| **[`Banco de Dados de veiculos/`](./Banco%20de%20Dados%20de%20veiculos/)** | `main.cpp`, `BD_veiculos.txt` | Sistema gerenciador de frota de até 100 veículos (`struct Veiculo`) com inclusão, busca por placa, exclusão, filtros por tipo/câmbio/faixa de preço e relatório estatístico. | `struct` Composta (14 campos), Persistência em Arquivo, Filtros Multi-Critério. | `g++ main.cpp -o veiculos && ./veiculos` |
| **[`Calculadora de Formas Geomtricas/`](./Calculadora%20de%20Formas%20Geomtricas/)** | `main.cpp`, `cenegrafia.txt.txt` | Processador geométrico em lote que lê descrições de cenas gráficas 2D e 3D de arquivo texto e calcula áreas totais e volumes (`calcular_area`, `calcular_volume`). | Modularização por Funções, Passagem por Referência `const string&`, Leitura de Fluxo (`stringstream`). | `g++ main.cpp -o geometria && ./geometria` |
| **[`Conhecendo Vetores 1/`](./Conhecendo%20Vetores%201/)** | `main.cpp` | Implementa operações de Teoria dos Conjuntos sobre dois vetores de inteiros: remoção manual de duplicatas, conjunto união e conjunto interseção. | Algoritmos em Arrays, Remoção de Duplicatas $O(n^2)$, União e Interseção de Conjuntos. | `g++ main.cpp -o vetores1 && ./vetores1` |
| **[`Conhecendo Vetores 2/`](./Conhecendo%20Vetores%202/)** | `main.cpp` | Preenche um vetor de 1.000 posições com inteiros pseudo-aleatórios no intervalo $[100, 200]$ e disponibiliza menu de busca posicional, contagem de frequência e filtro por intervalo. | `srand(time(NULL))`, Busca Sequencial, Contagem de Frequência em Arrays. | `g++ main.cpp -o vetores2 && ./vetores2` |
| **[`média de 1000 valores/`](./média%20de%201000%20valores/)** | `main.cpp` | Simula a geração de 1.000 alturas humanas no intervalo $[1.50\text{m}, 2.30\text{m}]$ e calcula média aritmética, extremos (máximo/mínimo) e contagem acima de $2.00\text{m}$. | Ponto Flutuante (`float`), Estatística Descritiva em Vetores, Geração Pseudo-Aleatória. | `g++ main.cpp -o media1000 && ./media1000` |
| **[`adivinhe o numero/`](./adivinhe%20o%20numero/)** | `main.cpp` | Jogo interativo de adivinhação numérica no intervalo $[1, 100]$ com validação de domínio de entrada (`while`), dicas de limite superior/inferior e contador de tentativas. | Laços Condicionais (`while`), Validação de Input (`cin`), `rand() % 100`. | `g++ main.cpp -o adivinhe && ./adivinhe` |
| **[`teste/`](./teste/)** | `EStudo 1.c` | Script inicial de estudo de estruturas de repetição (`for`) e controle de fluxo (`continue`) em linguagem C. | Sintaxe Básica C (`stdio.h`), Laço `for` e desvio `continue`. | `gcc "EStudo 1.c" -o estudo1 && ./estudo1` |
