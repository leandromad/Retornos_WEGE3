# Retornos_WEGE3
Pegando dados de cotações de WEGE3 desde seu ipo em 2000 e calculando retornos mensais comparando-os com retornos mensais do ibovespa
------
Inicialmente importa-se as seguintes bibliotecas que serão utilizadas na construção do projeto dos retornos:
<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/215821521-18f62639-08af-4b50-b036-167c4b128a4e.png" />
</p>
O próximo passo é obter os valores de cotações, podemos obter os valores de cotações ajustadas da WEGE3 através da utilização da API da yahoo finance, conforme a imagem:
<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/215821702-0d527583-21db-4e0d-a1f0-2e4262533832.png" />
</p>
E obtemos o dataframe: 
<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/215883138-c1043717-3af3-4091-8fee-0c719e01636f.png" />
</p>
Com o nosso dataframe podemos calcular os retornos mensais da WEGE3 da seguinte forma:
<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/215832146-24e5933c-8b84-46b5-87ef-3b2e0b0fdb4b.png" />
</p>
E o dataframe com os retornos mensais:
<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/215883570-45847a91-b734-4ced-8077-e00555599ed8.png" />
</p>

