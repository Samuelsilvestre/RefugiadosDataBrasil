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

### Fonte e Tecnologias de Processamento

* **Fonte Original dos Dados:** Governo Brasileiro - Ministério da Justiça e Segurança Pública (dados sobre Refúgio em Números).
* **Link da Fonte:** [https://www.gov.br/mj/pt-br/assuntos/seus-direitos/refugio/refugio-em-numeros-e-publicacoes](https://www.gov.br/mj/pt-br/assuntos/seus-direitos/refugio/refugio-em-numeros-e-publicacoes)
* **Tecnologias Usadas:** Os dados foram extraídos, tratados (limpeza de metadados, remoção de separadores de milhar) e estruturados em formato CSV (separador `;`) por **IA Gemini**.
* **Observação:** Este é o sumário da primeira de várias tabelas a serem processadas.
