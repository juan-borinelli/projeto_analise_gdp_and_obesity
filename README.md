# 📊 Análise de GDP e Obesidade Mundial

> 🚧 **Projeto em desenvolvimento**

Análise exploratória de dados correlacionando o PIB (GDP) per capita de países com suas taxas de obesidade, utilizando Python e Pandas.

## 📋 Sobre o Projeto

Este projeto investiga se existe relação entre a riqueza de um país (medida pelo GDP per capita) e seus índices de obesidade populacional. A análise utiliza técnicas de limpeza, transformação e visualização de dados para extrair padrões e conclusões a partir de datasets reais.

## 🎯 Perguntas de Negócio

- Países com maior GDP tendem a ter maiores índices de obesidade?
- Como a distribuição de obesidade varia por continente/região?
- Quais países apresentam comportamentos atípicos (alto GDP com baixa obesidade ou vice-versa)?

## 🛠️ Tecnologias

- Python 3
- Pandas
- Jupyter Notebook
- Matplotlib / Seaborn *(visualizações)*

## 📁 Estrutura do Projeto

```
projeto_analise_gdp_and_obesity/
├── arquivos_base/          # Datasets utilizados na análise
├── analise_gdp.ipynb       # Notebook de análise do GDP por país
└── analise_obesity.ipynb   # Notebook de análise dos índices de obesidade
```

## ▶️ Como Executar

**Pré-requisitos:** Python 3, Jupyter Notebook e as bibliotecas listadas.

```bash
# Clone o repositório
git clone https://github.com/juan-borinelli/projeto_analise_gdp_and_obesity.git
cd projeto_analise_gdp_and_obesity

# Instale as dependências
pip install pandas matplotlib seaborn jupyter

# Inicie o Jupyter
jupyter notebook
```

Abra os notebooks na seguinte ordem recomendada:
1. `analise_gdp.ipynb`
2. `analise_obesity.ipynb`

## 📊 O que está sendo analisado

**`analise_gdp.ipynb`**
- Leitura e limpeza do dataset de GDP
- Seleção e filtragem de países e períodos
- Transformações e agrupamentos com Pandas

**`analise_obesity.ipynb`**
- Leitura e limpeza do dataset de obesidade
- Análise de distribuição por país e região
- Exploração de padrões e outliers

## 🔜 Próximos Passos

- [ ] Cruzamento dos dois datasets (GDP × Obesidade)
- [ ] Visualizações comparativas (scatter plot, heatmap)
- [ ] Análise de correlação estatística
- [ ] Conclusões e interpretação dos resultados

## 📚 Aprendizados

- Limpeza e tratamento de dados com Pandas (`dropna`, `fillna`, `rename`, etc.)
- Filtragem e seleção de dados com condicionais
- Agrupamentos e sumarizações (`groupby`, `agg`)
- Exploração de datasets reais com estrutura irregular

---

Desenvolvido por [Juan Borinelli](https://github.com/juan-borinelli)