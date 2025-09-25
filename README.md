# 📊 Análise do Índice de Reclamações (IGR) – ANS

## 🎯 Objetivo
Este projeto tem como objetivo analisar o **Índice de Reclamações (IGR)** divulgado pela **Agência Nacional de Saúde Suplementar (ANS)**, que mede a satisfação dos beneficiários de planos de saúde.  

O **IGR** é calculado a partir das reclamações registradas via **Notificação de Intermediação Preliminar (NIP)**, sendo **inversamente proporcional à satisfação dos clientes**.  
👉 Quanto **menor o IGR**, maior a satisfação dos beneficiários.

---

## 📂 Estrutura do Projeto
- `notebooks/` → Análise exploratória completa em Jupyter Notebook.  
- `data/` → Base de dados utilizada (IGR – ANS).  
- `README.md` → Explicação do projeto e principais resultados.  

---

## 🔍 Metodologia
1. **Coleta dos Dados**: dataset público da ANS com informações de operadoras, cobertura, porte e índice de reclamações.  
2. **Limpeza e Tratamento**: conversão de formatos, ajuste de variáveis numéricas e categóricas.  
3. **Análise Exploratória (EDA)**:
   - Distribuição do IGR.  
   - Comparação por porte da operadora (pequeno, médio, grande).  
   - Comparação por tipo de cobertura (assistência médica x odontológica).  
   - Relação entre beneficiários, reclamações e IGR.  
   - Ranking de melhores e piores operadoras.  
4. **Visualizações Gráficas**: gráficos em Matplotlib e Seaborn.  
5. **Insights de Negócio**: interpretação dos resultados.  

---

## 📈 Principais Gráficos
- Histograma e Boxplot do IGR.  
- Boxplot e média do IGR por porte da operadora.  
- Comparação do IGR por tipo de cobertura.  
- Dispersão: Beneficiários x Reclamações (tamanho = IGR).  
- Ranking das Top 10 melhores e piores operadoras.  

---

## 💡 Principais Insights (exemplos para adaptar)
- Operadoras **grandes** tendem a apresentar um IGR mais **estável**, mesmo com maior número de beneficiários.  
- Operadoras **pequenas** podem ter índices de reclamação desproporcionais ao seu tamanho, impactando negativamente no IGR.  
- Cobertura de **assistência médica** apresenta IGR mais elevado em média que planos **exclusivamente odontológicos**.  
- Algumas operadoras se destacam como **benchmark positivo**, com milhões de beneficiários e baixo IGR.  

---

## 🚀 Tecnologias Utilizadas
- Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-lear, IO (StringIO).  
- Jupyter Notebook.  

---

## 👨‍💻 Autor
**Alan da Costa Saucedo**  
- [LinkedIn](https://www.linkedin.com/in/alan-costa-saucedo)  
- [GitHub](https://github.com/alan002)  

