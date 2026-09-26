
# Deep Generative Models – Atividade Prática (Autoregressive Models & VAE)

Este repositório contém a implementação da atividade prática da disciplina **Deep Generative Models**, desenvolvida no âmbito do Programa de Pós-Graduação em Ciência da Computação (PPGCC) do Instituto Federal do Ceará (IFCE).

## 🚀 Sobre o Projeto

O projeto está dividido em duas partes fundamentais de Modelos Generativos Profundos:

1. **Parte A (Modelo Auto-Regressivo):** Implementação de um modelo auto-regressivo baseado em máxima verossimilhança com camadas lineares em PyTorch (`nn.Linear`) aplicado ao conjunto de dados *German Credit*, com detecção de outliers e visualização analítica via PCA.


2. **Parte B (Variational Autoencoder - VAE):** Treinamento de um VAE utilizando o *Fashion MNIST* (`torchvision.datasets`), detecção de anomalias por erro de reconstrução, extração de representações latentes para classificação linear, comparação de desempenho com uma CNN supervisionada de referência e síntese de novas imagens via *Decoder*.



## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Python**

* **PyTorch** & **Torchvision**

* **Scikit-Learn** (PCA, StandardScaler, LogisticRegression)


* **Pandas** & **NumPy**

* **Matplotlib**


## 📦 Como Executar

O código principal foi desenvolvido estruturado para execução direta em ambientes com suporte a GPU (como o **Google Colab**):

1. Abra o notebook ou script em Python.
2. Certifique-se de que o ambiente possui o PyTorch e as bibliotecas auxiliares instaladas.
3. Execute as células sequencialmente para rodar os treinamentos da Parte A e da Parte B, gerar as métricas de acurácia/outliers e visualizar os gráficos e amostras sintéticas geradas.
