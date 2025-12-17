## 💻 Projeto de Análise e Detecção de Shill Bidding em Leilões do eBay

Este repositório contém o código e a documentação do projeto de detecção de fraudes (*shill bidding*) em leilões de iPhone 7 no eBay.

### ⚙️ Tecnologias Utilizadas

O projeto foi desenvolvido em um ambiente de prototipagem e análise de dados robusto, utilizando:

* **Ambiente de Desenvolvimento:** Google Colaboratory (Colab)
* **Linguagem de Programação:** Python

### 📦 Bibliotecas Essenciais

As seguintes bibliotecas foram cruciais para a análise exploratória de dados (EDA), pré-processamento e modelagem:

| Categoria | Biblioteca | Uso Principal |
| --- | --- | --- |
| **Manipulação de Dados** | `pandas` | Estruturação, limpeza e manipulação do *SHillBidding dataset*. |
| **Visualização** | `matplotlib` | Geração de gráficos estáticos para visualizações customizadas. |
| **Visualização** | `seaborn` | Criação de visualizações estatísticas atrativas e informativas (EDA). |
| **Modelagem** | `scikit-learn` | Implementação dos modelos K-Means e Isolation Forest. |
| **Modelagem** | `tensorflow` ou `pytorch` | Implementação do modelo de Autoencoders (Deep Learning). |

### 🚀 Metodologia

O fluxo de trabalho seguiu as seguintes etapas:

1. **Aquisição e Preparação de Dados:** Utilização de um *dataset* preexistente de lances em leilões de iPhone 7.
2. **Análise Exploratória de Dados (EDA):** Investigação detalhada dos padrões de lance e comportamento dos usuários.
3. **Pré-processamento:** Normalização, tratamento de valores omissos e codificação de variáveis.
4. **Modelagem e Treinamento:**
* **K-Means:** Agrupamento de perfis de licitantes.
* **Isolation Forest:** Detecção rápida de *outliers* de lance.
* **Autoencoders:** Uso de redes neurais para identificar anomalias através do erro de reconstrução.


5. **Detecção de Shill Bidders:** Diferenciação entre licitantes normais e aqueles com comportamento anômalo (*shill bidding*).

### 📂 Como Executar

1. Abra o arquivo principal do projeto (geralmente um *notebook* com extensão `.ipynb`) no **Google Colab**.
2. Instale quaisquer bibliotecas não padrão, se necessário (geralmente via `!pip install ...`).
3. Execute as células em ordem para reproduzir a EDA, o pré-processamento e o treinamento dos modelos.

