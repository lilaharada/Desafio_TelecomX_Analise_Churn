# Desafio TelecomX - Análise de Churn
---

### Este desafio faz parte do curso de Data Science, do programa **Alura-ONE, T2025**, para que façamos uma análise de evasão de clientes.

## 📌 Proposta do desafio
Este desafio faz parte do curso de Data Science, do programa Alura-ONE, T2025, para realização de uma análise sobre a evasão de clientes da empresa Telecom X.


## 🎯 Objetivos
A empresa Telecom X está enfrentando um alto índice de cancelamentos e precisa entender os fatores que levam à perda de clientes. 
Este desafio tem por objetivo analisar os dados fornecidos pela empresa para extrair insights sobre por que está ocorrendo essa evasão de clientes, para que a equipe de Data Science possa criar modelos preditivos e desenvolver estratégias para reduzir a evasão.

## 🛠️ Tecnologias Utilizadas
-	Google Colab
-	Python 3.10+
-	Pandas
-	NumPy
-	Matplotlib
-	Seaborn
-	Plotl

## 📲 Etapas do projeto
-	Extração de dados de um arquivo JSON estruturado por API.
-	Tratamento e normalização dos dados 
-	Verificação e correção de inconsistências
-	Padronização de colunas e variáveis
-	Criação de colunas derivadas (contas_diarias) baseada na fatura mensal
-	Análise exploratória de dados (EDA):
-	Distribuição da Evasão
-	Contagem de Evasão por Variáveis Categóricas
-	Contagem de Evasão por Variáveis Numéricas
•	Análise de correlação entre as variáveis

## 📈 Análise de Dados
-	26,5% dos clientes em geral cancelaram o serviço, indicando alta rotatividade e necessidade de ações corretivas.

### Principais fatores relacionados ao Churn
-	Forma de pagamento: 45,3% dos que cancelam usam cheque eletrônico. Métodos automáticos têm menor churn.
-	Tipo de contrato: 42,7% dos cancelamentos vêm de clientes com contrato mensal.
-	Tipo de internet: 41,9% dos que cancelam usam fibra ótica — possível relação com custo ou qualidade.
-	Suporte técnico: 41,6% dos cancelamentos ocorrem entre clientes sem suporte.
-	Segurança online: 38,1% dos que cancelam não possuem esse serviço.
-	Tempo de contrato: Clientes mais novos têm maior propensão ao churn.
-	Gasto mensal e total: Valores altos estão associados à insatisfação e maior churn.

## 💡 Conclusão e insights
1.	Churn elevado (26,5%) indica uma perda significativa de clientes e potencial ameaça à sustentabilidade do negócio.
2.	Clientes com contrato mensal, pagamento via cheque eletrônico, e sem serviços adicionais (como segurança ou suporte técnico) têm maior propensão ao cancelamento.
3.	Clientes que gastam mais por mês ou que são novos na base tendem a sair mais rápido, sugerindo uma possível insatisfação com custo-benefício.
4.	Já os clientes com relacionamento mais longo (mais meses de contrato) e maior gasto acumulado demonstram maior lealdade.


## ✅ Recomendações
Com base nos insights, recomenda-se:
- Incentivar contratos de longo prazo: Oferecer descontos ou benefícios para clientes que optam por contratos anuais ou bienais.
- Melhorar a qualidade do serviço de fibra óptica: Investigar e resolver possíveis problemas com esse serviço específico.
- Programas de fidelização para clientes novos: Criar estratégias para reter clientes nos primeiros 12 meses.
- Revisão de preços: Analisar a estrutura de preços para serviços com maior taxa de churn.
- Melhorar serviços adicionais: Oferecer pacotes mais atrativos ou melhorar a qualidade dos serviços extras.

