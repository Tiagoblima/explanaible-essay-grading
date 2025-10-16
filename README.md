# Métodos de XAI para Explicação de Incerteza em Modelos de Automatic Essay Scoring (AES) 

## 📘 Descrição do Projeto
Este projeto explora métodos de **Explainable Artificial Intelligence (XAI)** aplicados para explicar a incerteza ou erro de modelos de **machine learning** no contexto de **Automatic Essay Scoring (AES)**. A incerteza pode surgir devido à variação nos dados ou limitações do modelo, sendo essencial para compreender as limitações das predições e melhorar a confiabilidade do sistema.

## 🎯 Objetivo
Adaptar e aplicar métodos de XAI para explicar a incerteza dos modelos construídos através de **modelos surrogate**, considerando dois tipos de incerteza:

- **Incerteza Aleatória (Aleatoric Uncertainty):** média das incertezas de diferentes classificadores, representando variações intrínsecas dos dados.  
- **Incerteza Epistêmica (Epistemic Uncertainty):** variância das incertezas entre os modelos, refletindo a incerteza na própria modelagem.

## 🧠 Problema Abordado
O **Automatic Essay Scoring (AES)** consiste em avaliar e pontuar automaticamente redações, reduzindo tempo e custo em avaliações de larga escala (por exemplo, ENEM). Neste trabalho, a tarefa foi simplificada para classificar redações em cinco categorias de pontuação: **0, 50, 100, 150 e 200**.

Para isso, foram extraídas características como **legibilidade, coesão e coerência** para prever a nota final. Múltiplos modelos foram treinados e utilizados para calcular a incerteza de cada predição.

## 📊 Conjunto de Dados
O dataset utilizado contém **4570 redações do UOL**, com notas atribuídas com base em aspectos gerais do texto. Os atributos incluem métricas relacionadas à **estrutura textual** e **argumentação**.  

Optou-se por usar uma versão **balanceada do dataset** para evitar vieses decorrentes do desbalanceamento e focar no impacto das **features mais relevantes** e da **modelagem do problema**.

## 🛠️ Metodologia
1. Pré-processamento dos textos e extração de características textuais relevantes.  
2. Treinamento de múltiplos modelos de machine learning para previsão da pontuação.  
3. Aplicação de **métodos XAI** para explicar a incerteza das predições:
   - Aleatória (Aleatoric)  
   - Epistêmica (Epistemic)  
4. Análise dos resultados para identificar limitações e insights do modelo.

## 📚 Bibliotecas Utilizadas
- `pandas`  
- `numpy`  
- `scikit-learn`  
- `matplotlib` / `seaborn`  
- Bibliotecas XAI específicas (como `SHAP`, `LIME` ou similares)  

## 🚀 Como Executar
1. Clone o repositório:  
   ```bash
   git clone <URL_DO_REPOSITORIO>

[IA Generated]
