
# PLN - Projeto de Análise de Sentimentos

Este projeto tem como objetivo realizar **análise de sentimentos** utilizando técnicas de **Processamento de Linguagem Natural (PLN)** com o modelo BERT e bibliotecas de aprendizado de máquina.

## 🔍 Descrição
O projeto carrega dados textuais, executa pré-processamento, divide os dados em conjuntos de treino e teste, e utiliza o modelo `TFBertForSequenceClassification` da biblioteca `transformers` para classificar sentimentos.

Também são geradas visualizações com `matplotlib`, `seaborn` e `wordcloud` para análise exploratória dos dados.

## 📦 Requisitos

Instale as dependências com:

```bash
pip install -r requirements.txt
```

## 🛠 Tecnologias utilizadas

- `pandas`, `numpy` – Manipulação de dados
- `matplotlib`, `seaborn`, `wordcloud` – Visualização de dados
- `scikit-learn` – Divisão dos dados
- `transformers` – Tokenização e modelo BERT
- `tensorflow` – Treinamento do modelo

## 🚀 Execução

1. Clone o repositório:

```bash
git clone https://github.com/iaracampos/sentiment_analysis_NLP.git
cd sentiment_analysis_NLP
```

2. Instale os requisitos:

```bash
pip install -r requirements.txt
```

3. Execute o notebook ou script principal com:

```bash
jupyter lab
```

ou

```bash
python nome_do_script.py
```

## 🧠 Modelo Utilizado
O modelo utilizado é o `TFBertForSequenceClassification` da biblioteca `transformers`, que permite treinar classificadores baseados na arquitetura BERT com TensorFlow.

## 📁 Estrutura do Projeto

```
sentiment_analysis_NLP/
│
├── data/                 # Dados brutos e tratados
├── notebooks/            # Jupyter Notebooks
├── models/               # Modelos salvos
├── requirements.txt      # Arquivo de requisitos
└── README.md             # Este arquivo
```

## 👩‍💻 Autora

Iara Campos  
[GitHub](https://github.com/iaracampos) | [LinkedIn](https://www.linkedin.com/in/iara-campos-51643220b)

---

Este projeto foi desenvolvido como parte de estudos em PLN e modelos de linguagem.
