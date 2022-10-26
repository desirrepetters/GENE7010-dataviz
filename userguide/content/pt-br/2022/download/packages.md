---
title: "Pacotes para o R"
linkTitle: "Pacotes para o R"
weight: 6
description: >
  Como instalar os principais pacotes a serem utilizados durante a disciplina
---
<div align="justify">
À medida que trabalhamos com R, é comum elaborar funções que permitam obter os resultados desejados. Assim como em outras linguagens de programação, não é necessário elaborar tudo do zero. Existem vários pacotes que agrupam funções similares e relacionadas, os quais podem ser instaladas, carregadas durante uma sessão de trabalho, e incluídas em scripts.
<br><br>
Aqui listaremos alguns dos principais pacotes a serem utilizados durante as práticas da disciplina.
<br><br>
</div>

## Tidyverse

<div align="justify">
O <a href="https://www.tidyverse.org">Tidyverse</a> é uma coleção de pacotes do R elaborados para análises em data science, e que possuem uma filosofia de design similar (em termos de estrutura de dados e das funções).
<br><br>
Os pacotes incluídos no Tidyverse são:
<br><br>
</div>

<table>
  <tr>
    <th><strong><center>Pacote</center></strong></th>
	<th><strong><center>Descrição</center></strong></th>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/2c6239d311be6d037c251c71c3902792f8c4ddd2/12f67/css/images/hex/ggplot2.png" alt="Ícone ggplot2" align="center" heigth="250">
	</center></td>
	<td><center>ggplot2 é um sistema para criação de gráficos baseado em "The Grammar of Graphics". Você fornece o conjunto de dados, informa como mapear as variáveis à elementos estéticos e outros detalhes para que o ggplot2 produza o gráfico para você. Saiba mais sobre o ggplot <a href="https://ggplot2.tidyverse.org">aqui</a>.</center></td>
  </tr> 
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/621a9c8c5d7b47c4b6d72e8f01f28d14310e8370/193fc/css/images/hex/dplyr.png" alt="Ícone dplyr" align="center" heigth="250">
	</center></td>
    <td><center>dplyr fornece uma "gramática" para manipulação de dados, fornecendo um conjunto de verbos para resolver os principais problemas e realizar as principais operações para manipular diferentes conuntos de dados. Saiba mais sobre o dplyr <a href="https://dplyr.tidyverse.org/">aqui</a>.</center></td>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/476fa4025501dcec05be08248b32d390dd2337d5/574c6/css/images/hex/tidyr.png" alt="Ícone tidyr" align="center" heigth="250">
	</center></td>
    <td><center>tidyr fornece um conjunto de funções para obter dados no formato tidy, ou seja, dados num formato consistente: de forma resumida, cada variável corresponde a uma coluna, e cada linha corresponde a uma observação. Saiba mais sobre o tidyr <a href="https://tidyr.tidyverse.org/">aqui</a>.</center></td>
  </tr>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/c1c91484f898fe9d7d90a570900f1d5cd703fe2e/d7df4/css/images/hex/readr.png" alt="Ícone readr" align="center" heigth="250">
	</center></td>
    <td><center>readr fornece uma maneira rápida de ler conjuntos de dados e arquivos dispostos de forma "retangular" (como arquivos delimitados por vírgulas e tabulações, csv e tsv, respectivamente). readr está organizado para interpretar e realizar a leitura de vários tipos de arquivos comumente encontrados, e produz mensagens de erro informativas quando há falhas na leitura de arquivos com estruturas diferentes do esperado. Saiba mais sobre o readr <a href="https://readr.tidyverse.org/">aqui</a>.</center></td>
  </tr>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/2d0701b616efa7435cd5a94e703baa595a4f9ed0/d41b9/css/images/hex/purrr.png" alt="Ícone purrr" align="center" heigth="250">
	</center></td>
    <td><center>purrr melhora o toolkit de programação funcional do R, fornecendo diversas ferramentas para trabalhar com funções e vetores, permitindo a substituição de "for loops" por linhas de código mais simples e expressivas. Saiba mais sobre o purrr <a href="https://purrr.tidyverse.org/">aqui</a>.</center></td>
  </tr>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/c477d7eb7fdf2c3d75637cfe19ff4a4d0a107bcf/017d0/css/images/hex/tibble.png" alt="Ícone tibble" align="center" heigth="250">
	</center></td>
    <td><center>tibble é uma versão "repaginada" da data.frame tradicional, e que forçam você a lidar com problemas já no início do projeto, resultando em um código mais conciso e limpo. Por exemplo, tibbles não alteram nome e tipo de variáveis, não adicionam nomes às linhas e também apontam erros quando variáveis não existem. Saiba mais sobre o tibble <a href="https://tibble.tidyverse.org">aqui</a>.</center></td>
  </tr>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/45fd04ad9cdb2159fea08d07dbc11e742d68e4e3/df327/css/images/hex/stringr.png" alt="Ícone stringr" align="center" heigth="250">
	</center></td>
    <td><center>stringr fornece um conjunto de funções para trabalhar com strings de forma mais simplificada, implementando os procedimentos mais comuns de manipulação de strings. Saiba mais sobre o stringr <a href="https://stringr.tidyverse.org/">aqui</a>.</center></td>
  </tr>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/412a6f14518ab633a94221dda7e16cf22e43a763/91620/css/images/hex/forcats.png" alt="Ícone forcats" align="center" heigth="250">
	</center></td>
    <td><center>forcats fornece um conjunto de ferramentas que resolvem problemas comuns ao trabalhar com fatores, que são utilizados pelo R para manipulação de variáveis categóricas e/ou variáveis que possuem um conjunto fixo e conhecido de valores. Saiba mais sobre o forcats <a href="https://forcats.tidyverse.org/">aqui</a>.</center></td>
  </tr>   
</table> 
<br><br>
<div align="justify">
Para instalar o tidyverse, utilize o seguinte comando no R:
</div>

```
install.packages("tidyverse")
```

## Datasets

<div align="justify">
Ao estudar e aprender novas funções e testar implementação de scripts e geração de gráficos, muitas vezes é interessante realizar testes com conjuntos de dados já conhecidos. Ao utilizar conjuntos de dados que já estão caracterizados e cujo comportamento já é conhecido, torna-se mais fácil resolver problemas e também implementar melhoria nos códigos, e entender como elaborar diferentes tipos de gráficos.
<br><br> 
Por padrão, alguns pacotes do R ou do tidyverse possuem alguns conjuntos de dados que podem ser utilizados (por exemplo, os conjuntos "Iris", "cars", "mtcars", "ToothGrowth" do pacote "datasets" ou os conjuntos "diamonds" e "mpg" do ggplot2). Além destes conjuntos, existem outros que podem ser instalados à parte e são bastante úteis, como <a href="https://allisonhorst.github.io/palmerpenguins/">palmerpenguins </a> (diferentes medidas corporais de pinguins de três ilhas do arquipélago de Palmer, na Antártica) e <a href="https://www.rdocumentation.org/packages/mlbench/versions/2.1-3">mlbench</a> (vários conjuntos de dados utilizados para padronização de métodos de aprendizado de máquina).
<br><br>
Para instalar os pacotes palmerpenguins e mlbench utilize o seguinte comando no R:
<br><br>
</div>

```
install.packages("palmerpenguins")

install.packages("mlbench")

```

