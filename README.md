📊 TelecomX - Análise de Evasão de Clientes (Churn)
Este projeto tem como objetivo analisar os dados de clientes da empresa fictícia TelecomX e prever quais clientes têm maior probabilidade de cancelar o serviço (churn), utilizando técnicas de ciência de dados e machine learning.

🎯 Objetivo
Entender os principais fatores que influenciam a evasão de clientes.
Criar visualizações para identificar padrões nos dados.
Treinar modelos de aprendizado de máquina para prever o churn.
Ajudar a empresa a tomar decisões estratégicas para retenção de clientes.
🗂 Estrutura do Projeto
📁 TelecomX_Churn/ │ ├── data/ # Dados brutos e tratados ├── TelecomX_Churn_P2.ipynb # Notebook principal do projeto ├── README.md # Documentação do projeto └── requirements.txt # Bibliotecas utilizadas

yaml Copiar Editar

⚙️ Como Executar
✅ Pré-requisitos
Python 3.10+
Jupyter Notebook
Bibliotecas listadas abaixo
📦 Instalação das dependências
```bash pip install -r requirements.txt Ou, instale manualmente:

bash Copiar Editar pip install pandas matplotlib seaborn scikit-learn numpy ▶️ Executar o notebook bash Copiar Editar jupyter notebook Abra o arquivo TelecomX_Churn_P2.ipynb e execute as células na ordem.

📚 Bibliotecas Utilizadas Pandas - Manipulação e limpeza de dados

Matplotlib & Seaborn - Visualização de dados

Scikit-learn - Modelagem preditiva

NumPy - Suporte numérico

📈 Etapas Realizadas Importação e visualização dos dados

Limpeza e tratamento de dados

Remoção de espaços em branco

Conversão de colunas categóricas

Transformação de dados numéricos

Análise Exploratória

Gráficos de barras, dispersão e correlação

Análise de churn por tipo de contrato, pagamento, serviços, etc.

Criação de variáveis

Colunas binárias

Normalização de dados

Modelagem Preditiva

Divisão entre treino e teste

Treinamento com algoritmos de classificação

Avaliação por métricas como acurácia, precisão e matriz de confusão

📊 Resultados Acurácia do modelo: 82%

Principais variáveis influentes:

Tipo de contrato

Pagamento automático

Fidelidade do cliente

Serviços adicionais ativados

🚀 Possíveis Melhorias Testar outros algoritmos como XGBoost ou Random Forest

Ajuste de hiperparâmetros com Grid Search

Implementação de interface com Streamlit para uso comercial

🧠 Insights do Projeto Clientes com contrato mensal e sem débito automático têm maior probabilidade de cancelar o serviço.

Planos com mais serviços agregados têm menor taxa de evasão.

Estratégias personalizadas podem reduzir churn com base no perfil de risco do cliente.

👨‍💻 Autor Feito com 💙 por Antonio Moreira Neto

📧 Email: netoirmao2020@gmail.com 🔗 LinkedIn: linkedin.com/in/antonio-moreiraneto

Atualiza README.md com descrição completa do projeto.
