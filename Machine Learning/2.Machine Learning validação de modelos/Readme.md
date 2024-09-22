# Machine Learning validação de modelos

Bem-vindo ao curso de ** Machine Learning validação de modelos**! Neste curso, você aprenderá a importância de utilizar técnicas avançadas de validação de modelos para garantir que seu modelo generalize bem para novos dados, evitando os perigos de overfitting e subfitting.

## 📚 Conteúdo

### 1. **Entendendo os Perigos do Hold-Out**
   - O que é a técnica de hold-out?
   - Riscos e limitações do hold-out em cenários complexos
   - Quando evitar o uso de hold-out e optar por validação mais robusta

### 2. **Técnicas de Validação Cruzada (Cross Validation)**
   - Introdução à validação cruzada
   - Vantagens de aplicar cross-validation sobre hold-out
   - Exemplos práticos com **KFold**, **StratifiedKFold**, e **GroupKFold**

### 3. **Aleatoriedade a Seu Favor**
   - A importância da aleatoriedade na separação de dados
   - Como evitar vieses e garantir a representatividade dos seus dados no treino/teste
   - Aplicação de técnicas de shuffle e random state

### 4. **Estratégias de Validação Cruzada**
   - Quando usar **KFold**: Distribuição balanceada de dados
   - Quando usar **StratifiedKFold**: Validação estratificada para classes desbalanceadas
   - Quando usar **GroupKFold**: Separação baseada em grupos independentes de dados
   - Exemplos de cenários reais para aplicar cada técnica

### 5. **Previsão de Novos Grupos com Dependências de Dados**
   - Trabalhando com dados que possuem dependências (ex: leituras de sensores, séries temporais)
   - Técnicas para prever corretamente novos grupos de dados correlacionados
   - Aplicação prática com **GroupKFold**

### 6. **Uso de Pipelines para Treino e Validação**
   - Introdução ao conceito de pipelines em Machine Learning
   - Como construir pipelines que incluam pré-processamento, treino e validação
   - Uso de **Scikit-learn** pipelines para automatizar o processo de validação

## 🚀 Objetivo

Este curso foi criado para fornecer uma compreensão sólida das melhores práticas de validação em **Machine Learning**. Você será capaz de escolher a estratégia de validação ideal para o seu problema, garantindo que o modelo não apenas funcione bem nos dados de treino, mas também se generalize adequadamente para novos dados.

## 🛠 Tecnologias Utilizadas

- **Python**
- **Scikit-learn** para implementação de técnicas de validação cruzada e pipelines
- **Pandas** para manipulação de dados
- **NumPy** para operações numéricas
- **Matplotlib** e **Seaborn** para visualização de resultados

