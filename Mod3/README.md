# :books: Exercícios do Módulo 3

<br>

Para os exercícios 1 o 3 você precisará do arquivo alunos.csv.

<br>

> **1.** Neste exercício você deve criar um arquivo que abra o arquivo "alunos.csv" e imprima o conteúdo do arquivo linha a linha.
>
> Note que esse é o primeiro exercício de uma sequência, então o seu código pode ser reaproveitado nos exercícios seguintes. Dito isso, a recomendação é usar a biblioteca CSV para ler o arquivo mesmo que não seja realmente necessário para esse primeiro item.
> 
> [:mag: Ver código](Exercicio1.ipynb)
>    

<br>

> **2.** Para o segundo exercício, você deve criar um programa que realize uma cópia do arquivo "alunos.csv". Essa cópia deve ser um arquivo chamado "alunos_copia.csv".
>
> Aqui você também não precisa utilizar a biblioteca CSV novamente, mas se usar seu código pode ser reutilizado na próxima questão sem muitas modificações.
>
> [:mag: Ver código](Exercicio2.ipynb)
>  

<br>

> **3.** Neste exercício você deve criar um novo arquivo chamado "alunos_media.csv". Esse novo arquivo é uma cópia de "alunos.csv", porém com uma coluna a mais chamada "Média" que vai abrigar os valores das médias das provas de cada aluno da lista.
>
> Se você utilizou a biblioteca CSV para realizar os dois primeiros exercícios, muito será reaproveitado aqui. A biblioteca CSV permite a interpretação de cada linha como listas, que são fáceis de manipular.
>
> [:mag: Ver Código](Exercicio3.ipynb)
>  

<br>

> **4.** Você conhece Star Wars? Se trata, obviamente, da famosa saga espacial criada por George Lucas em 1977 e que deu origem a símbolos do cinema e da cultura pop com o imponente vilão Darth Vader ou o simpático robô R2-D2. A ideia desse exercício é justamente extrair informações do personagem Darth Vader através de uma API de Star Wars chamada SWAPI.
>
> Utilize a URL "https://swapi.dev/api/people/4/" para fazer a requisição dos dados de Darth Vader e extraia as informações "name" (nome), "height" (altura), "mass" (massa) e "birth_year" (ano de nascimento) e imprima cada dados em uma linha.
>
> __*Dica:*__ Caso não se lembre de como fazer isso, assista novamente a aula sobre API porque o exemplo da aula pode te ajudar.
>
> __*Observações:*__  
> A altura vem em centímetros, por isso o cálculo.  
>O ano de nascimento quer dizer:  
> __BBY__ = Before the Battle of Yavin
>
> [:mag: Ver Código](Exercicio4.ipynb)

<br>

> **5.** Em 2019 surgiram os primeiros casos de COVID-19 que se alastrou pelo mundo resultando em uma pandemia. A proposta deste exercício é utilizar uma API com informações de COVID-19 do mundo todo desde o início da proliferação e descobrir que dia o Brasil confirmou o primeiro caso de Coronavírus.
>
> Para fazer isso, utilize a URL "https://api.covid19api.com/country/brazil" em seu código. Ela retorna uma lista de dicionários, onde cada dicionário traz informações através das chaves:
>
> "ID", "Country", "CountryCode", "Province", "City", "CityCode", "Lat", "Lon", "Confirmed", "Deaths", "Recovered", "Active" e "Date".
>
> Utilize essas informações e retorne a data em que o Brasil confirmou o primeiro caso de COVID.
>
> [:mag: Ver Código](Exercicio5.ipynb)



