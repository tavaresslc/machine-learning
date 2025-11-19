# Machine Learning: MNIST Classification & Ticket Priority Prediction

Este repositório contém um notebook desenvolvido em Google Colab com dois experimentos principais:

1. **Classificação binária no MNIST (5 vs 7)**  
2. **Predição de prioridade de chamados (NLP)**

O foco é demonstrar pré-processamento, modelagem, comparação de algoritmos e avaliação objetiva.

---

## 1. MNIST — Binary Classification (5 vs 7)

**Modelos testados:**
- `SGDClassifier`
- `GaussianNB`

**Pipeline:**
- Download do dataset MNIST  
- Separação treino/teste  
- Treinamento e avaliação  
- Métricas: matriz de confusão, precisão e revocação  

**Resumo:**
- **SGDClassifier** → melhor desempenho geral  
- **GaussianNB** → alta revocação, baixa precisão (limitado para dados visuais)

---

## 2. Predição de Prioridade de Chamados (NLP)

Dataset real contendo descrições de chamados de manutenção predial.

**Pré-processamento:**
- Limpeza de colunas
- Remoção de duplicados/deletados
- Correção de datas
- Seleção das features relevantes

**Modelagem:**
- Vetorização com **TF-IDF**
- Treino/teste (80/20)
- Modelo: **Multinomial Naive Bayes**

**Resultado:**  
- **Acurácia ≈ 93%** na predição de `des_prioridade` a partir de `des_chamado`.

---

## Tecnologias
- Python  
- Scikit-learn  
- Pandas / NumPy  
- NLTK  
- Matplotlib  
- Google Colab  

---

## Objetivo do Notebook
- Demonstrar domínio em pré-processamento (numérico e textual)  
- Comparar algoritmos supervisionados  
- Utilizar métricas adequadas de classificação  
- Aplicar NLP com TF-IDF em dados reais  
- Apresentar um fluxo completo e reprodutível de Machine Learning  

---

