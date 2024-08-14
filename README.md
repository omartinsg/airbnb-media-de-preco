# Airbnb Média de Preço
Este projeto utiliza uma rede neural para estimar o preço médio que pode ser cobrado por uma diária no Airbnb, com base em dados fornecidos pelo locador ou locatário. Após o treinamento, a rede neural é hospedada em um site do Streamlit, permitindo que os usuários façam previsões facilmente.

## Funcionalidades
  - Treinamento da Rede Neural: O modelo é treinado utilizando uma base de dados contendo informações relevantes sobre propriedades no Airbnb, como localização, tipo de propriedade, número de quartos, etc.
  - Previsão de Preço: O modelo treinado pode prever o preço médio que pode ser cobrado por uma diária, com base nas informações fornecidas pelo usuário.
  - Interface Web com Streamlit: Após o treinamento, o modelo é disponibilizado em uma interface web simples e interativa, construída com Streamlit.

##  Requisitos
  - Python 3.x
  - Bibliotecas:
  - TensorFlow
  - Pandas
  - NumPy
  - Scikit-learn
  - Streamlit

### Certifique-se de que você possui a base de dados no formato adequado. O projeto inclui um exemplo de base de dados para treinamento (data.csv). Você pode substituir esse arquivo pelo seu próprio dataset.

### Inicie o Aplicativo Streamlit
  - Para iniciar o aplicativo web que permite prever o preço médio, execute:
     streamlit run app.py

## Contribuições
  Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.
