# Projeto Final MBA em Ciência de Dados e Inteligência Artificial

## Predição do Risco de Incêndios Florestais utilizando Machine Learning

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como trabalho de conclusão do **MBA em Ciência de Dados e Inteligência Artificial**.

O objetivo foi construir uma **pipeline completa de Machine Learning**, desde a preparação e integração de múltiplas bases de dados até o treinamento, otimização e interpretação de modelos preditivos capazes de classificar o nível de risco de incêndios florestais.

Durante o desenvolvimento foram aplicadas técnicas de engenharia de dados, engenharia de atributos, análise exploratória, testes estatísticos, otimização de hiperparâmetros e interpretação de modelos, buscando produzir uma solução robusta e orientada ao problema de negócio.

---

# 🎯 Objetivo

Desenvolver um modelo de Machine Learning capaz de prever o nível de risco de incêndios florestais a partir da integração de informações provenientes de diferentes bases públicas, auxiliando gestores na tomada de decisão sobre ações preventivas e alocação de recursos.

---

# 💼 Problema de Negócio

Os incêndios florestais representam impactos ambientais, econômicos e sociais significativos.

A utilização de modelos preditivos permite antecipar regiões com maior probabilidade de ocorrência de incêndios, contribuindo para:

- redução de custos operacionais;
- planejamento de ações preventivas;
- melhor distribuição de equipes de fiscalização;
- apoio à tomada de decisão baseada em dados.

---

# 📊 Bases de Dados

O projeto utilizou quatro bases públicas:

- 🔥 Base de Queimadas
- 🌦 Base Meteorológica (BDMEP)
- 📍 Base das Estações Meteorológicas
- 🌱 Base MapBiomas

As bases foram integradas por meio de informações temporais e geográficas, formando uma base única utilizada na modelagem.

---

# ⚙️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- XGBoost
- LightGBM
- Optuna
- SHAP
- Google Colab

---

# 🔄 Pipeline do Projeto

O desenvolvimento do projeto foi estruturado nas seguintes etapas:

1. Definição do problema de negócio e dos indicadores de desempenho (KPIs);
2. Conhecimento inicial das bases de dados;
3. Limpeza e preparação dos dados;
4. Engenharia de Dados, incluindo a integração das bases de Queimadas, Meteorologia, Estações Meteorológicas e MapBiomas;
5. Engenharia de Atributos (Feature Engineering);
6. Construção e validação da variável-alvo;
7. Separação dos conjuntos de treinamento, validação e teste;
8. Treinamento e avaliação dos modelos de Machine Learning;
9. Comparação dos modelos e seleção da melhor abordagem;
10. Otimização dos hiperparâmetros utilizando RandomizedSearchCV e Optuna;
11. Interpretabilidade do modelo por meio da análise de importância das variáveis;
12. Avaliação do impacto do modelo no contexto do problema de negócio e elaboração das conclusões.

# 🤖 Modelos Avaliados

Foram treinados e comparados os seguintes algoritmos:

- Baseline
- Random Forest
- XGBoost
- LightGBM
- Regressão Logística

O modelo **XGBoost** apresentou o melhor desempenho e foi selecionado para otimização.

---

# 📈 Otimização

Foram comparadas duas estratégias de otimização de hiperparâmetros:

- RandomizedSearchCV
- Optuna

Após a comparação dos resultados, o **RandomizedSearchCV** apresentou desempenho ligeiramente superior para este conjunto de dados e foi mantido como modelo final.

---

# 📊 Principais Resultados

Modelo final:

- **XGBoost Otimizado**

Resultados obtidos:

- Acurácia: **83,27%**
- Precisão: **80,37%**
- Recall: **83,27%**
- F1-score: **81,16%**

Além das métricas tradicionais, foi realizado um cálculo ilustrativo de impacto demonstrando como o desempenho do modelo pode ser convertido em indicadores financeiros para apoio à tomada de decisão.

---

# 📂 Estrutura do Repositório

```
projeto-final-mba-ciencia-dados-ia/

│
├── notebooks/
├── datasets/
├── imagens/
├── Relatorios/
├── README.md
└── .gitignore
```

---

# 🚀 Como Executar

1. Clone este repositório.
2. Abra o notebook utilizando Jupyter Notebook ou Google Colab.
3. Instale as dependências necessárias.
4. Execute as células na ordem apresentada.

---

# 📚 Principais Técnicas Aplicadas

- Análise Exploratória de Dados (EDA)
- Engenharia de Dados
- Engenharia de Atributos
- Integração de Bases
- Teste de Hipótese Estatístico
- Comparação de Modelos
- Otimização de Hiperparâmetros
- Feature Importance
- Avaliação de Impacto no Negócio

---

# 👩‍💻 Autora

**Ana Paula Takezawa**

Projeto desenvolvido como requisito para conclusão do **MBA em Ciência de Dados e Inteligência Artificial**.
