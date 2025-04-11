# MVP: Análise de Salários em IA e Ciência de Dados

Este repositório contém um projeto completo de análise exploratória de dados salariais de profissionais da área de dados e inteligência artificial. O objetivo principal é identificar padrões de remuneração com base em diferentes dimensões como localização, experiência, tipo de vínculo e modelo de trabalho.

---

## 🎯 Objetivo

Analisar o impacto da Inteligência Artificial (IA), Ciência de Dados e Machine Learning no mercado de trabalho global, com foco em **remuneração** e **condições de trabalho**. A partir da construção de um pipeline de dados com Python/Pandas, as perguntas respondidas incluem:

- Qual a variação salarial média entre níveis de experiência?
- Como o porte da empresa influencia o salário?
- Cargos mais bem pagos na área de dados?
- Diferenças salariais entre modelos de trabalho (remoto, híbrido, presencial)?
- Evolução da média salarial ao longo dos anos?
- Quais países mais contratam profissionais da área?

---

## 📂 Dataset

**Fonte:** Kaggle (https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)

- Nome: `ds_salaries.csv`
- Total de registros: 607
- Colunas: cargo, salário, tipo de vínculo, experiência, localização, tipo de trabalho
- Licença: Creative Commons (uso educacional permitido)

Incluído no repositório para facilitar reprodução dos experimentos.

---

## 🛠️ Tecnologias e Bibliotecas

- Python 3.11
- Pandas
- Matplotlib / Seaborn
- Plotly (para mapa interativo)
- Jupyter Notebook (ambiente de desenvolvimento)

---

## 📊 Análises Realizadas

- Limpeza e transformação de dados com mapeamento de siglas (país, experiência, empresa)
- Gráficos de barras com os cargos mais comuns e bem pagos
- Comparação de salário médio por:
  - Nível de experiência
  - Tipo de vínculo
  - Porte da empresa
  - Modelo de trabalho remoto
  - País (mapa interativo)
- Análise de dispersão salarial por desvio padrão (cargos com maior variação)
- Evolução salarial por ano (linha do tempo)

---

## 📁 Organização dos Arquivos

```
├── README.md            ← Descrição do projeto
├── ds_salaries.csv      ← Base de dados original
├── notebook.ipynb       ← Código completo com gráficos e análises
└── /figs                ← Pasta com imagens dos gráficos exportados
```

---

## ✅ Como executar localmente

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/mvp-salarios-dados.git
```
2. Instale os requisitos (recomenda-se uso de ambiente virtual):
```bash
pip install pandas matplotlib seaborn plotly
```
3. Execute o `notebook.ipynb` com Jupyter ou diretamente em VSCode/Google Colab.

---

## 📝 Catálogo de Dados

| Coluna               | Tipo    | Descrição                                                  |
|----------------------|---------|--------------------------------------------------------------|
| work_year            | int64   | Ano da coleta do dado                                       |
| experience_level     | string  | Nível de experiência (EN, MI, SE, EX)                       |
| employment_type      | string  | Tipo de vínculo (FT, PT, CT, FL)                           |
| job_title            | string  | Nome do cargo                                               |
| salary               | int64   | Salário bruto (moeda local)                                |
| salary_currency      | string  | Moeda do salário                                            |
| annual_salary_usd    | float64 | Salário anual convertido para USD                          |
| employee_residence   | string  | País de residência do funcionário                          |
| remote_ratio         | int64   | % de trabalho remoto (0, 50, 100)                          |
| company_location     | string  | Localização da sede da empresa                            |
| company_size         | string  | Tamanho da empresa (S, M, L)                               |

---

## 🙋‍♂️ Autor

- Nome: [Bruna Gonçalves]
- Curso: Engenharia de Dados
- Universidade: [PUC/RIO]


## 📌 Licença

Este projeto é apenas para fins educacionais, com base em dados públicos de uso livre.




