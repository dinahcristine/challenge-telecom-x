📊 Análise de Evasão de Clientes (Churn) - Telecom X

Bem-vindo ao repositório do projeto de análise de evasão de clientes (Churn) da Telecom X! Este projeto tem como objetivo identificar padrões e fatores que influenciam a saída de clientes, fornecendo insights valiosos para reduzir a taxa de evasão e melhorar a retenção.


📌 Objetivo

O principal objetivo desta análise é:

Identificar os principais motivos que levam os clientes a cancelarem seus serviços.

Explorar relações entre características dos clientes (como tipo de contrato, gastos mensais e serviços utilizados) e a evasão.

Gerar recomendações estratégicas para reduzir o Churn.


🛠 Tecnologias Utilizadas

Python para manipulação e análise de dados.

Pandas para tratamento e organização dos dados.

Matplotlib/Seaborn para visualizações gráficas.

Jupyter Notebook para documentação interativa do projeto.


📂 Estrutura do Projeto

1️⃣ Carregamento e Pré-Processamento dos Dados
Os dados foram obtidos diretamente da API e convertidos em um DataFrame do Pandas.

Foram verificados tipos de dados, valores ausentes e inconsistências.

2️⃣ Limpeza e Tratamento
Correção de valores ausentes e duplicados.

Padronização de categorias (ex.: "Sim"/"Não" para 1/0).

Criação de novas variáveis, como "Contas_Diárias", para análise mais detalhada.

3️⃣ Análise Exploratória (EDA)
Distribuição do Churn: Proporção de clientes que cancelaram vs. permaneceram.

Análise por Variáveis Categóricas:

Gênero, tipo de contrato, método de pagamento, etc.

Análise por Variáveis Numéricas:

Total gasto, tempo de contrato (tenure), etc.

4️⃣ Visualizações e Insights
Gráficos como barras, boxplots e histogramas para identificar padrões.

Exemplo de insight:

Clientes com contratos mensais têm maior taxa de evasão.

Clientes que utilizam fibra óptica tendem a cancelar mais.

5️⃣ Conclusões e Recomendações
Principais Achados: Resumo dos fatores mais associados ao Churn.

Ações Recomendadas:

Oferecer incentivos para migração de contratos mensais para anuais.

Melhorar a qualidade do serviço de fibra óptica ou oferecer suporte técnico dedicado.


📊 Resultados Destacados

Taxa de Churn: X% dos clientes cancelaram o serviço.

Fatores Críticos:

Contrato "Month-to-month" tem Y% mais evasão.

Clientes com "Fibra Óptica" representam Z% dos cancelamentos.


👨‍💻 Como Executar o Projeto

Clone o repositório:

bash
git clone [URL do repositório]
Instale as dependências:

bash
pip install pandas matplotlib seaborn
Abra o Jupyter Notebook e execute as células para reproduzir a análise.

📄 Relatório Completo
O relatório detalhado com código, visualizações e explicações está disponível no arquivo:
🔹 TelecomX_Churn_Analysis.ipynb
