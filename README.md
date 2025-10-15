# Processamento de Dados sobre Refugiados do Governo Brasileiro

## Sumário da Tabela: Menores Refugiados (2023-2024)

Este sumário refere-se à primeira tabela processada e estruturada, detalhando processos de refúgio deferidos para menores de idade no contexto de reunião familiar.

**Nome do Arquivo CSV:** `MenoresRefugiados2023-2024.csv`

---

### Estrutura de Dados da Tabela

A tabela final possui **4 colunas** e foi transformada (pivotada) a partir dos dados originais por Ano e Sexo.

| Coluna | Descrição | Tipo de Dado (Conteúdo) |
| :--- | :--- | :--- |
| **ano** | Ano em que o processo foi deferido (2023 ou 2024). | Numérico Categórico / Texto |
| **genero** | Sexo do refugiado menor de 17 anos (`masculino`, `feminino`, `nao informado`). | Texto (Categórico) |
| **pais** | País de nacionalidade ou residência habitual do refugiado. | Texto (Categórico) |
| **total\_processos\_deferidos** | Quantidade de processos de refúgio aprovados. | Numérico (Inteiro) |

---
## Sumário da Tabela: Refugiados Indeferidos Por Grupo Idade (2024)

### Panorama

Esta tabela detalha o **Número de processos de solicitação de reconhecimento da condição de refugiado que foram INDEFERIDOS (negados)** no Brasil durante o ano de **2024**, distribuídos por **grupo de idade** e **sexo**.

**Nome do Arquivo CSV:** `RefugiadosIndeferidosGrupoIdade2024.csv`

---

### Estrutura de Dados da Tabela

| Coluna | Descrição | Tipo de Dado (Conteúdo) |
| :--- | :--- | :--- |
| **grupo\_idade** | Faixa etária do solicitante. | Texto (Categórico) |
| **genero** | Sexo do solicitante (`masculino`, `feminino`). | Texto (Categórico) |
| **total\_processos\_indeferidos** | Quantidade de processos de refúgio negados. | Numérico (Inteiro) |

---
## Sumário da Tabela: Processos Extintos Por País (2024)

### Panorama

Esta tabela detalha o **Número de processos de solicitação de reconhecimento da condição de refugiado que foram EXTINTOS (encerrados sem decisão de mérito)** no Brasil durante o ano de **2024**.

Os dados estão distribuídos por **país de nacionalidade ou residência habitual** e **sexo**.

**Nome do Arquivo CSV:** `ProcessosRefugiadosExtintos2024.csv`

---

### Estrutura de Dados da Tabela

| Coluna | Descrição | Tipo de Dado (Conteúdo) |
| :--- | :--- | :--- |
| **pais** | País de nacionalidade ou residência habitual. | Texto (Categórico) |
| **genero** | Sexo do solicitante (`masculino`, `feminino`, `nao especificado`). | Texto (Categórico) |
| **total\_processos\_extintos** | Quantidade de processos de refúgio extintos. | Numérico (Inteiro) |
---
## Sumário da Tabela: Processos Extintos Por Idade (2024)

### Panorama

Esta tabela detalha o **Número de processos de solicitação de reconhecimento da condição de refugiado que foram EXTINTOS (encerrados sem decisão de mérito)** no Brasil durante o ano de **2024**.

Os dados estão distribuídos por **grupo de idade** e **sexo**.

**Nome do Arquivo CSV:** `ProcessosRefugiadosExtintosIdade2024.csv`

---

### Estrutura de Dados da Tabela

| Coluna | Descrição | Tipo de Dado (Conteúdo) |
| :--- | :--- | :--- |
| **grupo\_idade** | Faixa etária do solicitante. | Texto (Categórico) |
| **genero** | Sexo do solicitante (`masculino`, `feminino`, `nao especificado`). | Texto (Categórico) |
| **total\_processos\_extintos** | Quantidade de processos de refúgio extintos. | Numérico (Inteiro) |
---
## Sumário da Tabela: Processos Arquivados Por País (2024)

### Panorama

Esta tabela detalha o **Número de processos de solicitação de reconhecimento da condição de refugiado que foram ARQUIVADOS** no Brasil durante o ano de **2024**. Um processo arquivado é similar a um extinto, indicando o encerramento da solicitação sem uma decisão de mérito (deferimento ou indeferimento).

Os dados estão distribuídos por **país de nacionalidade ou residência habitual** e **sexo**.

**Nome do Arquivo CSV:** `ProcessosRefugiadosArquivados2024.csv`

---

### Estrutura de Dados da Tabela

| Coluna | Descrição | Tipo de Dado (Conteúdo) |
| :--- | :--- | :--- |
| **pais** | País de nacionalidade ou residência habitual. | Texto (Categórico) |
| **genero** | Sexo do solicitante (`masculino`, `feminino`, `nao especificado`). | Texto (Categórico) |
| **total\_processos\_arquivados** | Quantidade de processos de refúgio arquivados. | Numérico (Inteiro) |
---
## Sumário da Tabela: Menores Refugiados Deferidos Por Idade (2023-2024)

### Panorama

Esta tabela detalha o **Número de processos de solicitação de reconhecimento da condição de refugiado que foram DEFERIDOS (aprovados)** no Brasil para menores de idade (**idade $\leq$ 17 anos**), no contexto de **reunião familiar**, durante **2023 e 2024**.

Os dados estão distribuídos por **grupos de idade** (0 a 6, 7 a 11 e 12 a 17 anos), **ano** e **sexo**.

**Nome do Arquivo CSV:** `MenoresRefugiadosDeferidosIdade2023-2024.csv`

---

### Estrutura de Dados da Tabela

| Coluna | Descrição | Tipo de Dado (Conteúdo) |
| :--- | :--- | :--- |
| **ano** | Ano em que o processo foi deferido (2023 ou 2024). | Numérico Categórico / Texto |
| **genero** | Sexo do refugiado menor de 17 anos (`masculino`, `feminino`, `nao informado`). | Texto (Categórico) |
| **grupo\_idade** | Faixa etária do refugiado menor de 17 anos. | Texto (Categórico) |
| **total\_processos\_deferidos** | Quantidade de processos de refúgio aprovados. | Numérico (Inteiro) |
---
### Fonte e Tecnologias de Processamento

* **Fonte Original dos Dados:** Governo Brasileiro - Ministério da Justiça e Segurança Pública (dados sobre Refúgio em Números).
* **Link da Fonte:** [https://www.gov.br/mj/pt-br/assuntos/seus-direitos/refugio/refugio-em-numeros-e-publicacoes](https://www.gov.br/mj/pt-br/assuntos/seus-direitos/refugio/refugio-em-numeros-e-publicacoes)
* **Tecnologias Usadas:** Os dados foram extraídos, tratados (limpeza de metadados, remoção de separadores de milhar) e estruturados em formato CSV (separador `;`) por **IA Gemini**.
* **Observação:** Este é o sumário da primeira de várias tabelas a serem processadas.
