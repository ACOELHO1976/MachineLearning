# MVP - Machine Learning & Analytics

Notebook criado exclusivamente para o MVP da disciplina de Machine Learning

Aluno: Alex Joaquim Coelho

# Previsão de Cancelamento de Clientes (Churn)
## Objetivo
O objetivo deste projeto é prever o cancelamento de clientes (Churn) em uma empresa de telecomunicações.
O termo Churn refere-se ao momento em que um cliente decide interromper o uso do serviço, ou seja, cancelar seu contrato.

# Tipo de problema
Este é um problema de classificação binária, onde:
1 → Cliente cancelou o serviço (Churn)
0 → Cliente permaneceu ativo

# Motivação
A perda de clientes impacta diretamente a receita da empresa. Identificar clientes com alto risco de cancelamento permite a aplicação de estratégias de retenção, como ofertas e melhorias no atendimento.

# Por que usar Machine Learning?
O cancelamento de clientes depende de múltiplos fatores, como:
-  tipo de contrato
-  valor pago
-  tempo de permanência
Modelos de Machine Learning conseguem identificar padrões complexos nesses dados e prever o comportamento futuro dos clientes.

⚠️ Premissas e limitações
Os dados representam comportamento passado
Não indicam causalidade, apenas correlação
Dataset simulado (IBM)
📁 Dataset
Fonte: IBM Telco Customer Churn
Registros: ~7000 clientes
Variável alvo: Cancelamento (Churn)
📌 Variáveis importantes
tenure → Tempo como cliente
MonthlyCharges → Valor mensal
Contract → Tipo de contrato
InternetService → Serviço de internet
⚠️ Limitações
Dados simulados
Pode não representar todos os cenários reais
Dataset: Microdados do Censo Escolar da Educação Básica 2024 (INEP)

Onde encontrar o Dataset original: https://download.inep.gov.br/dados_abertos/microdados_censo_escolar_2024.zip

Onde encontrar o Dataset usado aqui: https://github.com/ACOELHO1976/Analise_Exploratoria

Onde encontrar a análise realizada: https://colab.research.google.com/github/ACOELHO1976/Analise_Exploratoria/blob/main/mvpAnalisededados.ipynb

Algumas observações: Tanto o arquivo CVS, quanto arquivos que ajudam a complemetar e entender mais do trabalho podem ser encontrados no endereço

