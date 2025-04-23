# 💳 Credit Card Fraud Detection

Este projeto realiza uma análise de dados de transações com cartão de crédito, com o objetivo de identificar possíveis fraudes utilizando algoritmos de machine learning supervisionado, como Árvores de Decisão, Random Forest e AdaBoost.

---

## 🎯 Objetivos

- Detectar transações fraudulentas com base em dados reais.
- Avaliar e comparar modelos de classificação supervisionados.
- Visualizar o desempenho de cada modelo com gráficos gerados no notebook.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** – Manipulação de dados
- **NumPy** – Operações numéricas
- **Scikit-learn** – Modelagem preditiva
- **Matplotlib** e **Seaborn** – Visualização de dados
- **Jupyter Notebook** – Ambiente interativo para desenvolvimento

---

## 📁 Estrutura do Projeto

```
📦 credit-card-fraud-detection/
├── data/                       
│   └── creditcard.csv (adicionado manualmente) 
│
├── images/                      # Imagens dos gráficos gerados
│   ├── adaboost1.png
│   ├── adaboost2.png
│   ├── arvore_decisao1.png
│   ├── arvore_decisao2.png
│   ├── random_forest1.png
│   ├── random_forest2.png
│   ├── random_forest3.png
│   └── random_forest4.png
│
├── credit_card_fraud_analysis.ipynb  # Notebook com a análise completa
├── requirements.txt             # Dependências do projeto
├── README.md                    # Este arquivo
└── LICENSE                      # Licença do projeto
```

---

## ⚙️ Como Executar

1. **Clone o repositório:**

```bash
git clone https://github.com/seunome/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

2. **Baixe o dataset manualmente:**

- Acesse o link: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Faça o download do arquivo `creditcard.csv`
- Coloque o arquivo na pasta `data/` do projeto

3. **Crie um ambiente virtual e ative-o:**

```bash
python -m venv venv
source venv/bin/activate        # No Windows: venv\Scripts\activate
```

4. **Instale as dependências:**

```bash
pip install -r requirements.txt
```

5. **Execute o Jupyter Notebook:**

```bash
jupyter notebook
```

Abra o arquivo `credit_card_fraud_analysis.ipynb` para explorar a análise.

---

## 📊 Exemplos de Análises Realizadas

- Comparação de desempenho entre algoritmos (Acurácia, Precisão, Recall)
- Matrizes de confusão
- Gráficos de importância de variáveis
- Visualização da curva ROC

---

## 📚 Fonte de Dados

- [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## 🙋‍♂️ Autor

**Raike Fernandes**  
🔗 [LinkedIn](https://www.linkedin.com/in/raike-fernandes/)  
📧 fernandesraike4@gmail.com

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Sinta-se à vontade para dar uma ⭐ ou contribuir com melhorias!
