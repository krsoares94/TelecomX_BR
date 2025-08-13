# 📊 Telecom X – Análise de Churn de Clientes

Este projeto faz parte do desafio de Data Science do Programa ONE (Oracle Next Education) e tem como foco o processo de ETL e a análise exploratória de dados para compreender os fatores que influenciam a evasão de clientes na empresa fictícia de telecomunicações, Telecom X.

---

## 📌 Objetivo

O objetivo principal é identificar padrões de comportamento entre clientes que cancelaram o serviço (`Churn = 1`) e aqueles que permaneceram, por meio de técnicas de ETL, limpeza de dados, visualizações e análises descritivas.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Estrutura do Projeto

- `TelecomX_BR.ipynb`: notebook principal com todas as etapas do projeto.
- `README.md`: documento de apresentação do projeto.
- Fonte de Dados extraídos diretamente da [API JSON do GitHub](https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/main/TelecomX_Data.json)

---

## 🧪 Etapas Realizadas

1. **Extração dos Dados**: obtenção via API em formato JSON e carregamento com `pandas.read_json()`.
2. **Transformação**:
   - Normalização de colunas aninhadas
   - Limpeza e tratamento de inconsistências
   - Criação de novas variáveis (`Contas_Diarias`, `Qtd_Servicos`)
   - Conversão de categorias binárias para 0/1
   - Renomeação de colunas para melhor leitura
3. **Análise Exploratória (EDA)**:
   - Análise descritiva das variáveis
   - Visualização da distribuição de `Churn`
   - Análises por variáveis categóricas e numéricas
   - Correlação entre variáveis (extra)

---

## 📈 Resultados e Insights

- Clientes com menor tempo de contrato e faturas mais altas evadem mais.
- Contratos mensais e pagamento por `Electronic Check` têm maior associação com churn.
- A maioria dos clientes permanece com a empresa, mas há um padrão claro de risco entre perfis específicos.

---

## 👨‍💻 Autora
Este projeto foi desenvolvido por Karol Soares, participante do Programa ONE | Alura + Oracle.
