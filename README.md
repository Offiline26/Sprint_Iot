# 🧠 MotoSync IA – Classificação Inteligente de Pátios

Este projeto aplica técnicas de Machine Learning para classificar pátios operacionais com base em seu comportamento diário. Com dados simulados, foram analisadas variáveis como movimentações de motos, ocupação média e tempo de uso das vagas, a fim de prever se um pátio é de **alta rotatividade**, **baixa utilização** ou um **gargalo logístico**.

---

## 📈 Objetivo

Desenvolver um modelo preditivo que classifique os pátios com base em dados operacionais, auxiliando na tomada de decisões logísticas da Mottu por meio de inteligência artificial aplicada.

---

## 🛠️ Tecnologias Utilizadas

- Python 3.11+
- Pandas
- Seaborn
- Matplotlib
- Plotly
- Scikit-learn

---

## 🔍 Principais Etapas

- Análise exploratória dos dados com gráficos visuais
- Reclassificação lógica dos pátios com base em regras operacionais
- Normalização dos dados numéricos
- Treinamento de modelo Random Forest
- Avaliação com métricas como acurácia, precisão e matriz de confusão

---

## 📊 Resultados

O modelo treinado atingiu uma acurácia de aproximadamente **XX,XX%**, demonstrando boa capacidade de prever corretamente o tipo de pátio com base nas variáveis analisadas.

---

## 📁 Estrutura do Projeto

├── data/ # Arquivos CSV simulados
├── images/ # Gráficos gerados (barras, boxplots, heatmaps)
├── notebook/ # Notebook do Google Colab com todo o processo
├── README.md # Documentação principal

---

## 🧠 Lógica de Classificação dos Pátios

Os pátios foram rotulados com base em regras simples:

- **Alta Rotatividade**: muitas movimentações e pouco tempo de ocupação
- **Gargalo**: ocupação muito alta e tempo longo de permanência
- **Baixa Utilização**: uso baixo ou instável

---

## 👥 Integrantes

- Thiago Mendes – RM 555352  
- Guilherme Gonçalves – RM 558475  
- Vinicius Banciela – RM 558117  

---

## 🚀 Próximos Passos

- Substituir os dados simulados por dados reais dos sensores RFID e LoRa
- Integrar o modelo a um painel analítico ou API para uso interno
- Testar outros algoritmos como XGBoost, SVM e KNN
- Aplicar aprendizado contínuo (online learning) com base no uso real dos pátios

---

## 📌 Observações

Este projeto faz parte de uma proposta acadêmica para aplicar conceitos de Inteligência Artificial no contexto de IoT e mobilidade urbana, com foco em eficiência operacional e organização logística.
