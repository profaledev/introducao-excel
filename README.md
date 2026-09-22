# 📊 Introdução ao Microsoft Excel — Do Caderno ao Sistema

> **💡 Ideia Central:** Excel não é uma calculadora gigante. É o **cérebro das decisões** de uma empresa.

---

## 🧠 1. Por que Excel importa? (Conceito)

Imagine uma loja que anota tudo no caderno. Um dia são 10 vendas, no outro são 300. No caderno, encontrar o total do mês leva horas e um erro apaga o lucro.

O **Microsoft Excel** resolve isso porque ele é uma **Planilha Eletrônica** que, segundo Laudon & Laudon (SIG - Sistemas de Informação Gerencial), funciona como uma **ferramenta de suporte à decisão**.

Pense assim:

| No Caderno | No Excel |
| :--- | :--- |
| 📝 Você escreve o **RESULTADO** | 🧠 Você escreve a **LÓGICA** |
| 😴 Se mudar um número, recalcula tudo na mão | ⚡ Se mudar um número, **TUDO recalcula sozinho** |
| 📉 Erro escondido | 🔍 Erro rastreável |

**🎯 Transição de mentalidade que vamos fazer juntos:**

`😥 Operador` (digita) → `🤔 Analista` (pergunta, relaciona, decide)

> Para o curso de DS, Excel é seu **primeiro contato com Banco de Dados e Algoritmos**, sem precisar programar ainda.

---

## 🖥️ 2. A Interface — O Terreno do Jogo

O Excel é uma **matriz gigante**: linhas + colunas = células.

### 🔹 O Mapa

*   **📍 Colunas (A, B, C...)** e **📍 Linhas (1, 2, 3...)** formam um plano cartesiano.
*   **🟦 Célula:** Cruzamento, ex: `A1`. É a unidade básica. Tem um **endereço único**.
*   **🏷️ Caixa de Nome:** Mostra onde você está (ex: `C10`). Seu GPS na planilha.
*   **📊 Faixa de Opções (Ribbon):** Seus botões de ferramentas.
*   **🔬 Barra de Fórmulas:** O lugar mais importante! O que você **VÊ na célula é o RESULTADO**, o que você **VÊ na Barra é a LÓGICA**.

> **👉 Teste de 30 segundos:** Digite `100` em `A1`, `50` em `B1` e `=A1+B1` em `C1`. `C1` mostra `150`, mas a Barra mostra `=A1+B1`. Mude `A1` para `200`. Viu a mágica?

### 🔹 Tipos de Dados

*   **🔤 Texto:** Nomes, produtos (alinhado à esquerda)
*   **🔢 Número:** Valores, quantidades (alinhado à direita)
*   **💰 Moeda / 📅 Data:** Números com formato especial
*   **🧮 Fórmula:** Sempre começa com `=`

---

## 🧮 3. A Lógica do Cálculo — Como o Excel Pensa

O Excel não adivinha. Ele **interpreta instruções**.

### ⚡ O Gatilho: `=`

O sinal de `=` é o botão "EXECUTAR". Sem ele, `10+2` é só texto. Com ele, `=10+2` é conta e vira `12`.

### 🔢 Operadores e a Regra de Ouro (PEMDAS)

O Excel segue a hierarquia da matemática:

1.  `( )` **Parênteses** - Primeiro
2.  `^` **Potência** - Ex: `=10^2` → 100
3.  `*` e `/` **Multiplicação e Divisão**
4.  `+` e `-` **Adição e Subtração**

> **⚠️ Erro clássico:** `=10+2*3` = `16` (faz `2*3` primeiro). Se você queria `(10+2)*3 = 36`, TEM que usar parênteses!

| Operação | Como escreve no caderno | Como escreve no Excel |
| :--- | :--- | :--- |
| Soma | 10 + 2 | `=10+2` |
| Multiplicação | 10 x 2 | `=10*2` |
| Divisão | 10 ÷ 2 | `=10/2` |
| Potência | 10² | `=10^2` |
| Porcentagem | 10% de 100 | `=100*10%` |

### ✨ Funções: Atalhos Inteligentes

Em vez de `=A1+A2+A3+A4`, use `=SOMA(A1:A4)`. É mais rápido e não esquece ninguém.

*   `=SOMA(A1:A10)` → Soma tudo
*   `=MÉDIA(A1:A10)` → Média
*   `=MÁXIMO(A1:A10)` → Maior valor
*   `=MÍNIMO(A1:A10)` → Menor valor

> **💡 Dica de Ouro:** `:` significa **ATÉ** (intervalo contínuo `A1:A10`), `;` significa **E** (valores separados `A1;A10`). Trocar um pelo outro pode sumir com milhares de reais!

---

## 🎯 ATIVIDADES PRÁTICAS

> **📌 Instrução ao aluno:** Abaixo estão apenas os **enunciados**. Não há passo a passo. Use o que aprendeu na introdução + explore as ferramentas do Excel para descobrir como fazer.

### 🏠 ATIVIDADE 1 — Desenhar a Planta e Calcular a Metragem

> **🧩 Objetivo:** Explorar ferramentas de formatação e aplicar fórmulas simples para calcular áreas.

**📖 Enunciado:**

Você é o estagiário de uma imobiliária. O corretor te enviou as medidas de um apartamento e pediu para você entregar no Excel:

1.  **O desenho da planta** usando as próprias células do Excel como tijolos. Use bordas, cores e mesclagem para representar os 4 cômodos:
    *   Sala: 4m x 5m
    *   Quarto 1: 3m x 3m
    *   Cozinha: 3m x 2m
    *   Banheiro: 2m x 2m

2.  **A tabela de cálculo** logo abaixo do desenho, onde cada cômodo tem sua área calculada por fórmula (`Largura * Comprimento`) e no final o **TOTAL GERAL** da metragem do imóvel somando todas as áreas. Formate as áreas com unidade `m²` e descubra qual é o maior cômodo usando uma função.

3.  Entregue o arquivo `.xlsx` com a planta desenhada + tabela calculada. Mostre na prática a reatividade: o que acontece com o TOTAL se a Sala for ampliada?

**✅ Entregável:** `RA_Nome_Planta.xlsx` (planta desenhada + tabela com fórmulas)
**⭐ O que será avaliado:** Fidelidade do desenho, uso correto de fórmulas de multiplicação e soma, e formatação.

---

### 📄 ATIVIDADE 2 — Do CSV Bagunçado à Tabela Inteligente

> **🧩 Objetivo:** Identificar padrão em dados brutos e transformar em base analisável.

**📖 Enunciado:**

O sistema da loja exportou um arquivo `vendas_brutas_50.csv` (50 vendas, 6 colunas) mas ele veio **todo bagunçado em uma única coluna**, com os dados separados por `;` (ponto e vírgula). Seu chefe não consegue filtrar nem calcular nada assim.

Sua missão é:
1.  Identificar o padrão do arquivo e transformá-lo em uma **planilha organizada em colunas**.
2.  Converter essa planilha em uma **Tabela Formatada do Excel** (com estilo e filtros).
3.  Criar uma nova coluna calculada `Total` ( `Qtd * Preço_Unit` ) usando fórmula e calcular o **faturamento total** da lista com uma função de soma. Formate os valores como moeda `R$`.

*Arquivo para usar:* `vendas_brutas_50.csv` (disponível na pasta da aula - 50 linhas + cabeçalho, separador `;`)

**✅ Entregável:** `RA_Nome_CSV_Tabela.xlsx` (dados em colunas + Tabela formatada com filtros + coluna Total calculada)
**⭐ O que será avaliado:** Correta identificação do separador, organização em colunas, conversão para Tabela e aplicação correta das fórmulas.

---

## 🚀 Próximo Nível

Na próxima aula, vamos fazer essas tabelas **pensarem sozinhas** com lógica condicional (`SE`) e resumos automáticos (`Tabela Dinâmica`).

> **Frase para levar:** *"Quem domina a planilha, domina a decisão."*

---
*Prof. Alessandro Vitorio • ETEC Irmã Agostina • PTIC 2026*
