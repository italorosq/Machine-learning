# 🫀 Predição de Mortalidade em Insuficiência Cardíaca

Este repositório contém o projeto final da disciplina de **Aprendizagem de Máquina**.

O objetivo central é desenvolver e comparar modelos preditivos (**clusterização** . **Random Forest** e **MLP**) para identificar o risco de mortalidade em pacientes com insuficiência cardíaca, abordando o problema crítico de desbalanceamento de classes em dados médicos.

## 📂 Estrutura do Projeto

O repositório está organizado conforme a entrega dos três relatórios da disciplina.

```text
.
├── Notebooks desenvolvidos/
│   ├── código 1.ipynb    # Referente ao Relatório 1 (Clusterização)
│   ├── código 2.ipynb    # Referente ao Relatório 2 (Grid Search)
│   └── codigo 3.ipynb    # Referente ao Relatório 3 (Evolução Diferencial)
├── Relatorios/
│   ├── Relatorio 1.pdf
│   ├── Relatorio 2.pdf
│   └── relatorio 3.pdf
└── README.md
```

## 🧠 Metodologia e Desenvolvimento

O trabalho foi dividido em três entregas progressivas, onde cada notebook corresponde a uma etapa da análise:

### 📍 Relatório 1: Análise Exploratória e Não Supervisionada
* **Arquivo:** `Notebooks desenvolvidos/código 1.ipynb`
* **Foco:** Compreensão da estrutura da base de dados sem o uso de rótulos.
* **Atividades Principais:**
    * Pré-processamento, normalização e limpeza dos dados.
    * Estatística descritiva e análise de correlação entre variáveis.
    * Aplicação de PCA (Análise de Componentes Principais) para redução de dimensionalidade e visualização.
    * Agrupamento hierárquico (Clustering) e análise de dendrogramas para identificar perfis de pacientes.

### 📍 Relatório 2: Classificação Supervisionada (Baseline)
* **Arquivo:** `Notebooks desenvolvidos/código 2.ipynb`
* **Foco:** Estabelecimento de uma linha de base (baseline) com os dados originais desbalanceados e balanceados.
* **Atividades Principais:**
    * Aplicação da técnica **ADASYN** (Adaptive Synthetic Sampling) para balanceamento das classes.
    * Treinamento inicial dos classificadores Multilayer Perceptron (MLP).
    * Otimização de hiperparâmetros utilizando Grid Search (busca exaustiva).
    * **Diagnóstico:**
    

### 📍 Relatório 3: Otimização e Balanceamento (Final)
* **Arquivo:** `Notebooks desenvolvidos/codigo 3.ipynb`
* **Foco:** Correção de viés, otimização heurística e validação robusta.
* **Atividades Principais:**
    * Aplicação da técnica **ADASYN** (Adaptive Synthetic Sampling) para balanceamento das classes.
    * Implementação de **Evolução Diferencial** para otimização refinada dos hiperparâmetros, visando superar limitações do Grid Search.
    * Geração dos resultados finais com matrizes de confusão comparativas e testes estatísticos de validação.
    * **Diagnóstico:**

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Bibliotecas:**
    * Manipulação: `Pandas`, `Numpy`
    * Visualização: `Matplotlib`, `Seaborn`
    * Machine Learning: `Scikit-learn`, `Imbalanced-learn`
    * Otimização/Estatística: `Scipy`

## 🚀 Como Executar

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2.  **Instale as dependências:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn scipy
    ```

3.  **Execute os Notebooks:**
    Recomenda-se executar os arquivos na ordem numérica (1, 2, 3) localizada na pasta `Notebooks desenvolvidos` para acompanhar a evolução das análises.

## ✒️ Autor

**Ítalo Rosa Gonçalves**


