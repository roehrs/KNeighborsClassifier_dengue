# Mineração de Dados de Dengue com KNeighborsClassifier

Este projeto apresenta um pipeline completo de pre-processamento e modelagem de dados para prever casos de dengue utilizando o algoritmo `KNeighborsClassifier` da biblioteca `scikit-learn`. O projeto foi desenvolvido no Google Colab.

## Estrutura do Projeto

1. Carregar e ajustar os dados
2. Pré-processamento dos dados
3. Divisão da base de dados em treinamento e teste
4. Treinamento do modelo com `KNeighborsClassifier`
5. Predição e avaliação do modelo
6. Apresentação da matriz de confusão e acurácia do modelo

## Requisitos

- Python 3.x (já disponível no Google Colab)
- Pandas (`pip install pandas`)
- NumPy (`pip install numpy`)
- scikit-learn (`pip install scikit-learn`)

## Como Rodar o Projeto

1. **Clone o Repositório para o Google Colab**:
   - Abra o Google Colab: [https://colab.research.google.com](https://colab.research.google.com)
   - No menu, clique em "File" > "Open notebook" > "GitHub"
   - Digite `https://github.com/roehrs/KNeighborsClassifier_dengue` e abra o notebook disponível.

2. **Executar o Notebook**:
   - Siga as etapas no notebook para carregar os dados, fazer o pré-processamento, treinar o modelo e avaliar os resultados. Cada célula de código pode ser executada clicando no botão de "play" à esquerda da célula.

## Estrutura do arquivo `arq_dengue.csv`

Link: `https://drive.google.com/file/d/12B5L6o_9pG7m2VVC5nHGi4ya8Tbjauae/view?usp=sharing`

O arquivo csv deve seguir a estrutura abaixo:

```plaintext
paciente;febre;dor_muscular;falta_apetite;manchas_vermelhas;dengue
0;38.6;sim;sim;sim;sim
1;36.4;nao;nao;nao;nao
2;37.5;sim;sim;nao;sim
3;38.9;sim;sim;sim;sim
4;39.3;sim;sim;sim;sim
