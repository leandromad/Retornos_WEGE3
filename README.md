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

O mesmo que foi realizado com os dados da WEGE3 será feito com os dados do índice ibovespa para serem comparados no final.
O primeiro passo é pegar obter os dados do IBOVESPA:

<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/215885086-1f2cc000-ee93-43bf-a8c0-7e0bf31a3a8e.png" />
</p>

Assim obtemos o seguinte dataframe:

<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/215885345-043e0afb-a74c-4aac-a845-13027fca9877.png" />
</p>

Transformando em retornos mensais:
<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/216373078-449a2ef0-70d9-4360-a8c5-96c750f0db8b.png" />
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/215887823-13d8e2a5-1968-408b-9c54-c72c20a04f5e.png" />
</p>

Unindo-se os dados de retornos de WEGE3 e do IBOV:

<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/216373606-6c1d60ae-cc55-4254-b9f1-2fbb6356dda9.png" />
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/216373810-428cb11c-db16-4f13-8dd4-0d72a6f98d09.png" />
</p>

E finalmente plotando o gráfico de calor para os retornos de WEGE3 e do IBOV:

<p align="center">
  <img src="https://user-images.githubusercontent.com/82683162/216374732-d5550b19-b720-459b-8618-72a845abb557.png" />
</p>

Para os retornos da WEGE3 obteve-se:



