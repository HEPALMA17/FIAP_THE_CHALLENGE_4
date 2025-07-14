# Sistema Preditivo de Obesidade - Tech Challenge F4

## 📋 Descrição do Projeto

Este projeto desenvolve um sistema completo de Machine Learning para auxiliar médicos e médicas na previsão de obesidade em pacientes. O sistema inclui:

- **Pipeline de Machine Learning** com feature engineering completo
- **Modelo preditivo** com assertividade acima de 75%
- **Aplicação Streamlit** para previsões em tempo real
- **Dashboard analítico** com insights para a equipe médica

## 🏗️ Estrutura do Projeto

```
├── data/
│   └── Obesity.csv                 # Dataset principal
├── models/
│   ├── modelo_obesidade.pkl        # Modelo treinado
│   └── encoders.pkl               # Encoders salvos
├── src/
│   ├── data_preprocessing.py       # Pré-processamento dos dados
│   ├── model_training.py          # Treinamento do modelo
│   ├── evaluation.py              # Avaliação do modelo
│   └── utils.py                   # Funções utilitárias
├── app/
│   ├── streamlit_app.py           # Aplicação Streamlit
│   └── dashboard.py               # Dashboard analítico
├── notebooks/
│   └── exploratory_analysis.ipynb  # Análise exploratória
├── requirements.txt                # Dependências
└── README.md                      # Documentação
```

## 🚀 Como Executar

### 1. Instalação das Dependências

```bash
pip install -r requirements.txt
```

### 2. Executar o Pipeline Completo

```bash
python src/data_preprocessing.py
python src/model_training.py
python src/evaluation.py
```

### 3. Executar a Aplicação Streamlit

```bash
streamlit run app/streamlit_app.py
```

## 📊 Dicionário de Dados

| Variável       | Descrição                                | Tipo       |
| -------------- | ---------------------------------------- | ---------- |
| Gender         | Gênero                                   | Categórica |
| Age            | Idade                                    | Numérica   |
| Height         | Altura em metros                         | Numérica   |
| Weight         | Peso em kg                               | Numérica   |
| family_history | Histórico familiar de excesso de peso    | Categórica |
| FAVC           | Consumo de alimentos altamente calóricos | Categórica |
| FCVC           | Consumo de vegetais nas refeições        | Categórica |
| NCP            | Número de refeições principais diárias   | Numérica   |
| CAEC           | Consumo entre refeições                  | Categórica |
| SMOKE          | Fumo                                     | Categórica |
| CH2O           | Consumo diário de água                   | Numérica   |
| SCC            | Monitoramento de calorias                | Categórica |
| FAF            | Frequência de atividade física           | Categórica |
| TER            | Tempo com dispositivos tecnológicos      | Numérica   |
| CALC           | Frequência de consumo de álcool          | Categórica |
| MTRANS         | Meio de transporte                       | Categórica |
| Obesity        | Nível de obesidade (target)              | Categórica |

## 🎯 Resultados

- **Acurácia do Modelo**: > 85%
- **Precisão**: > 80%
- **Recall**: > 75%

## 📈 Funcionalidades

### Sistema Preditivo

- Interface intuitiva para entrada de dados
- Previsão em tempo real
- Probabilidades por classe
- Explicação das previsões

### Dashboard Analítico

- Distribuição da variável alvo
- Análise de correlações
- Insights por variável
- Gráficos interativos

## 🔧 Tecnologias Utilizadas

- **Python 3.8+**
- **Scikit-learn**: Machine Learning
- **Streamlit**: Interface web
- **Pandas & NumPy**: Manipulação de dados
- **Matplotlib & Seaborn**: Visualizações
- **Plotly**: Gráficos interativos

## 👥 Autores

Desenvolvido para o Tech Challenge F4 - FIAP

## 📝 Licença

Este projeto é parte do Tech Challenge F4.
