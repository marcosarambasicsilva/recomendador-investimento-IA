# Sistema de recomendação de investimento

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

