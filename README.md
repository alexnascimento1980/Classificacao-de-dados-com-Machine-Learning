# 📊 Classificação de Dados com Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Sobre o Projeto

Este repositório contém o desenvolvimento e a prática do curso **"Classificação de Dados com Machine Learning"** da Alura. O foco principal é a construção, o treinamento e a avaliação de modelos preditivos utilizando Python para solucionar desafios, como a previsão de evasão de clientes (Churn) e a análise de retorno sobre investimentos.

Embora as bases de dados deste repositório lidem com cenários de marketing, os algoritmos de classificação abordados formam um raciocínio analítico altamente versátil. Essa mesma base algorítmica é perfeitamente aplicável a operações complexas de transporte e logística — por exemplo, ao prever a probabilidade de atrasos de entregas, modelar manutenções preventivas de frotas ou identificar padrões de gargalos na distribuição de cargas.

## 🚀 O Que Você Vai Encontrar Aqui

- **Engenharia de Recursos:** Transformação de variáveis categóricas com o uso de One-Hot Encoding (modelo exportado no arquivo `modelo_onehotenc.pkl`).
- **Modelagem Preditiva:** Treinamento de algoritmos de classificação baseados em Árvores de Decisão (`modelo_arvore.pkl`).
- **Análise de Churn:** Estudo de caso para entender e prever cancelamentos através do dataset `churn.csv`.
- **Estratégia de Marketing:** Classificação de perfis de retorno utilizando os dados de `marketing_investimento.csv`.
- **Métricas de Avaliação:** Validação da performance e acurácia dos modelos gerados.

## 📁 Estrutura de Arquivos

- 📓 `projeto inicial-classificacao_ Primeiros passos.ipynb`: Guia inicial e primeiros comandos na criação dos modelos.
- 📓 `Desafios_+Hora+da+prática.ipynb`: Resoluções de desafios e exercícios para fixação do conhecimento.
- 📓 `para usar no colab web.ipynb`: Versão do notebook otimizada para ser executada em nuvem.
- 💾 `churn.csv` | `marketing_investimento.csv`: Datasets utilizados para treino e teste.
- 📦 `modelo_arvore.pkl` | `modelo_onehotenc.pkl`: Arquivos serializados com os modelos já treinados.
- 📄 `requirements.txt`: Dependências e bibliotecas necessárias para rodar o ambiente.

## 🛠️ Como Executar o Projeto Localmente

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/alexnascimento1980/Classificacao-de-dados-com-Machine-Learning.git](https://github.com/alexnascimento1980/Classificacao-de-dados-com-Machine-Learning.git)
   ```
2. **Acesse o diretório do projeto:**

   ```bash
   cd Classificacao-de-dados-com-Machine-Learning
   ```

3. **Instale as dependências requeridas:**

   ```bash
   pip install -r requirements.txt
   bash

   ```

4. **Execute os Notebooks:**

   ```bash
   Inicie o ambiente utilizando jupyter notebook no terminal ou faça o upload do arquivo para usar no colab web.ipynb diretamente no Google Colab.
   ```

## 📈 Possibilidades de Expansão

A prática em Machine Learning é uma porta de entrada para aplicações extremamente diversificadas. Dominar a construção e a exportação de modelos em Python pavimenta o caminho para a integração dessas ferramentas ao desenvolvimento de software tradicional, permitindo a criação de APIs que consumam os arquivos .pkl para automação.

A aplicação de modelos de classificação também desempenha um papel fundamental na cibersegurança moderna, auxiliando na categorização de ameaças e detecção de anomalias em redes. Para quem busca solidificar o rigor analítico, revisitar os conceitos de álgebra que embasam o funcionamento interno desses algoritmos é um passo excelente e natural para o aprofundamento na Ciência de Dados.
