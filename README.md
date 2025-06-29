# 📊 Análise de Evasão de Clientes - TelecomX

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)  
✅ **Status do Projeto:** Concluído

Este projeto tem como objetivo identificar padrões de comportamento relacionados à evasão (churn) de clientes em uma empresa de telecomunicações fictícia chamada **TelecomX**. A análise busca entender quais fatores influenciam a saída dos clientes e fornecer insights que auxiliem na retenção.

---

## 📁 Dados

Os dados foram obtidos a partir de um arquivo JSON com informações sobre clientes, planos, contratos e churn. Cada linha representa um cliente, contendo variáveis como:

- `gender`: Gênero do cliente  
- `SeniorCitizen`: Se o cliente é idoso (1) ou não (0)  
- `tenure`: Tempo de permanência em meses  
- `Churn`: Se o cliente saiu (`Yes`) ou permaneceu (`No`)  
- Outros dados relacionados ao tipo de plano e pagamento

---

## 🔍 Etapas da Análise

1. **Carregamento e limpeza dos dados**  
2. **Exploração de variáveis demográficas e contratuais**  
3. **Visualizações interativas com Plotly**  
4. **Cálculo de taxas de churn por tempo de permanência**  
5. **Geração de insights estratégicos**

---

## 📈 Principais Insights

- A **maior taxa de churn ocorre nos primeiros meses de contrato**, indicando que os clientes desistem rapidamente após contratar.
- O **fator "ser idoso" parece aumentar a chance de evasão**, o que pode refletir dificuldades com tecnologia ou insatisfação com o atendimento.
- O **gênero não tem impacto relevante** na saída de clientes.
- Clientes com **maior tempo de permanência tendem a continuar**, reforçando a importância de estratégias de retenção no início da jornada.

---

## 🛠 Tecnologias Utilizadas

- Python 3.10+
- Pandas
- Plotly Express
- Jupyter Notebook

---

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/paamelaamaro/Challenge_TelecomX.git
   cd Challenge_TelecomX
