# 🧠 MotoSync IA – Classificação de Pátios com Machine Learning

Projeto acadêmico desenvolvido para aplicar técnicas de Inteligência Artificial no contexto do sistema **MotoSync**, voltado à gestão logística de motos nos pátios da empresa Mottu.

---

## ❗ Problema

Atualmente, a organização dos pátios de motos da Mottu enfrenta desafios relacionados à desorganização, tempo de resposta operacional e falta de previsibilidade. Pátios sobrecarregados, outros subutilizados e a ausência de um controle analítico dificultam decisões estratégicas.

Para auxiliar nesse cenário, propusemos um modelo de **aprendizado de máquina** capaz de **classificar automaticamente os pátios** em três categorias:

- `alta_rotatividade`
- `baixa_utilizacao`
- `gargalo`

Essas classificações ajudam a entender o comportamento de cada pátio com base em dados como movimentações diárias, ocupação média e tempo médio de uso das vagas.

---

## ⚙️ Frameworks, Técnicas e Algoritmos Utilizados

### 📦 **Pandas**
Utilizado para carregamento, limpeza e manipulação dos dados tabulares simulados.

### 📊 **Seaborn, Matplotlib e Plotly**
Três bibliotecas de visualização utilizadas para análise exploratória, geração de gráficos estatísticos, mapa de calor de correlações e distribuição de variáveis.

### 🤖 **Scikit-learn**
Utilizado para todas as etapas de aprendizado de máquina:
- **Pré-processamento:** normalização com `StandardScaler`
- **Modelagem:** `RandomForestClassifier`
- **Avaliação:** `accuracy_score`, `classification_report` e `confusion_matrix`

### ✅ **Justificativa da Escolha do Modelo**
O **Random Forest** foi escolhido por sua robustez, boa performance em problemas com variáveis tabulares e facilidade de interpretação. Além disso, é menos sensível à escala dos dados e lida bem com features correlacionadas.

---

## 🧱 Arquitetura Desenvolvida

A estrutura do projeto segue um fluxo típico de aprendizado supervisionado:



## 📌 Observações

Este projeto faz parte de uma proposta acadêmica para aplicar conceitos de Inteligência Artificial no contexto de IoT e mobilidade urbana, com foco em eficiência operacional e organização logística.
