# Sistema de Recomendação de Investimentos com IA
Este projeto utiliza técnicas de Machine Learning para recomendar o melhor tipo de investimento (ações, títulos, fundos, etc.) com base no perfil do investidor, tolerância ao risco e previsão de retorno. O sistema é interativo e permite ajustes no nível de risco desejado.

## Informações principais

Relatório do Projeto: [Relatório - Sistema de recomendação de investimento]()
Github:
Base de Dados:


## Estrutura organizacional do projeto:

```
recomendador_investimento-IA/
├── data/                  # Bases de dados (originais e tratadas)
│   ├── lake/              # Dados brutos
│   └── warehouse/         # Dados limpos e prontos para modelagem
|   └──metadados/          # Metadados das bases de dados 
│
├── notebooks/             # Jupyter Notebooks para exploração e testes
│   └── analise_inicial.ipynb
|   └── etl_dados.ipynb
│
├── src/                   # Código-fonte principal
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── model_evaluation.py
│   ├── predictor.py       # Função principal de predição
│   └── utils.py           # Funções auxiliares
│
├── app/                   # Interface + deploy (Streamlit)
│   └── main.py
│
├── models/                # Modelos treinados (.pkl ou .joblib)
│
├── requirements.txt       # Dependências do projeto
├── .gitignore             # Ignorar arquivos 
└── README.md              # Documentação do projeto
```

## Funconalidades
- Classificação do tipo ideal de investimento: conservador, moderado ou arrojado.
- Previsão de retorno estimado com base em dados históricos.
- Interface interativa com Streamlit para simulação personalizada.


## Tecnologias Utilizadas
- Python
- scikit-learn
- Pandas & NumPy



## Como executar:

1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/investimento_recomendador.git
cd investimento_recomendador
```

2. Instalar dependências

```cmd
pip install -r requirements.txt
```

3. Rodar a aplicação (exemplo Streamlit)

```cmd
streamlit run app/main.py
```

