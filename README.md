# Random Forest Classifier
Este projeto foi desenvolvido com intuito de verificar a precisão de uma Random Forest na predição de tendência de preço do par de moedas EUR/USD em timeframe de 60 segundos. O passo a passo **detalhado**, está presente no arquivo `Random Forest Classifier.ipynb`, **não deixe de conferir**.

**Este projeto esta concluído.** ✅ ✔️☑️

## Como executar o algoritmo
Este algoritmo pode ser executado com **[Jupyter Notebook](https://jupyter.org/)** ou no **[Google Colab](https://colab.research.google.com/)**, recomendo a segunda opção, pois não precisa instalar nada em seu computador. No  **Colab**,  basta importar o arquivo `.ipynb` e o `EURUSD` para o ambiente e executar, ao final sera gerado um arquivo `RF_EURUSD` contendo a Random Forest.

## Tecnologias Utilizadas
- **Python**
- **Numpy**
- **Pickle**
- **TALib**
- **Pandas**
- **Sklearn**

## Etapas

 1. ETL
 2. Divisão
 3. Treinamento
 4. Teste
 5. Validação(Hold-Out / Cross-Validation)

## Conclusão
O algoritmo conseguiu uma precisão de 79% em hold-out e 78% em cross-validation, porem não foi testada em ambiente real.
