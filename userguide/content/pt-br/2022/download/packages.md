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
O <a href="https://www.tidyverse.org">Tidyverse</a> é uma coleção de pacotes do R elaborados para análises em data science, e que possuem uma filosofia de design similar (em termos de estrutura de dados e das funções).:
<br><br>
Os pacotes incluídos no Tidyverse são:
<br><br>
</div>

<table>
  <tr>
    <th><strong>Pacote</th></strong></th>
	<th><strong>Descrição</strong></th>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/2c6239d311be6d037c251c71c3902792f8c4ddd2/12f67/css/images/hex/ggplot2.png" alt="Ícone ggplot2" align="center" heigth="250">
	</center></td>
	<td><center>ggplot2 é um sistema para criação de gráficos baseado em "The Grammar of Graphics". Você fornece o conjunto de dados, informa como mapear as variáveis à elementos estéticos e outros detalhes para que o ggplot2 produza o gráfico para você. Saiba mais sobre o ggplot <a href="https://ggplot2.tidyverse.org">aqui</a></center></td>
  </tr> 
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/621a9c8c5d7b47c4b6d72e8f01f28d14310e8370/193fc/css/images/hex/dplyr.png" alt="Ícone dplyr" align="center" heigth="250">
	</center></td>
    <td><center>dplyr fornece uma "gramática" para manipulação de dados, fornecendo um conjunto de verbos para resolver os principais problemas e realizar as principais operações para manipular diferentes conuntos de dados. Saiba mais sobre o dplyr <a href="https://dplyr.tidyverse.org/">aqui</a></center></td>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/476fa4025501dcec05be08248b32d390dd2337d5/574c6/css/images/hex/tidyr.png" alt="Ícone tidyr" align="center" heigth="250">
	</center></td>
    <td>tidyr fornece um conjunto de funções para obter dados no formato tidy, ou seja, dados num formato consistense: de forma resumida, cada variável corresponde a uma coluna, e cada linha corresponde a uma observação. Saiba mais sobre o tidyr <a href="https://tidyr.tidyverse.org/">aqui</a></td>
  </tr>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/c1c91484f898fe9d7d90a570900f1d5cd703fe2e/d7df4/css/images/hex/readr.png" alt="Ícone readr" align="center" heigth="250">
	</center></td>
    <td>readr fornece uma maneira rápida de ler conjuntos de dados e arquivos dispostos de forma "retangular" (como arquivos delimitados por vírgulas e tabulações, csv e tsv, respectivamente). readr está organizado para interpretar e realizar a leitura de vários tipos de arquivos comumente encontrados, e produz mensagens de erro informativas quando há falhas na leitura de arquivos com estruturas diferentes do esperado. Saiba mais sobre o readr <a href="https://readr.tidyverse.org/">aqui</a></td>
  </tr>
  <tr>
    <td><center>
	<img src="https://d33wubrfki0l68.cloudfront.net/2d0701b616efa7435cd5a94e703baa595a4f9ed0/d41b9/css/images/hex/purrr.png" alt="Ícone purrr" align="center" heigth="250">
	</center></td>
    <td>purrr melhora o toolkit de programação funcional do R, fornecendo diversas ferramentas para trabalhar com funções de vetores, permitindo a substituição de "for loops" com linhas de código mais simples e expressivas. Saiba mais sobre o purrr <a href="https://purrr.tidyverse.org/">aqui</a></td>
  </tr>
  <tr>
    <td>MACSE</td>
    <td>Ranwez V, Douzery EJP, Cambon C, Chantret N, Delsuc F, 2018. MACSE v2: Toolkit for the alignment of coding sequences accounting for frameshifts and stop codons. <b>Molecular Biology and Evolution</b> 35, 2582-2584. DOI: <a href="https://doi.org/10.1093/molbev/msy159">10.1093/molbev/msy159</a></td>
  </tr>
  <tr>
    <td>trimAL</td>
    <td>Capella-Gutierrez S, Silla-Martinez JM, Gabaldon T, 2009. trimAl: a tool for automated alignment trimming in large-scale phylogenetic analyses. <b>Bioinformatics</b> 25, 1972-1973. DOI: <a href="https://doi.org/10.1093/bioinformatics/btp348">10.1093/bioinformatics/btp348</a></td>
  </tr>    
</table> 

<div align="justify">


<center>
<img src="https://raw.githubusercontent.com/desirrepetters/GENE7010-dataviz/master/userguide/content/pt-br/2022/download/img/R_RStudio/R_RStudio_2.png" alt="Página de escolha dos espelhos de R" align="center">
</center>
<br><br>
Em seguida, escolha a opção correspondente ao seu sistema operacional. Neste exemplo, faremos a instalação em Windows. 
<br><br>
<center>
<img src="https://raw.githubusercontent.com/desirrepetters/GENE7010-dataviz/master/userguide/content/pt-br/2022/download/img/R_RStudio/R_RStudio_3.png" alt="Escolha de sistema operacional com destaque para Windows" align="center">
</center>
<br><br>
Na página seguinte, clique em "base":
<br><br>
<center>
<img src="https://raw.githubusercontent.com/desirrepetters/GENE7010-dataviz/master/userguide/content/pt-br/2022/download/img/R_RStudio/R_RStudio_4.png" alt="Escolha de página com destaque para base" align="center">
</center>
<br><br>
Após clicar em "base", clique na opção "Download R-4.2.1 for Windows" para instalar a versão mais atual do software R.
<br><br>
<center>
<img src="https://raw.githubusercontent.com/desirrepetters/GENE7010-dataviz/master/userguide/content/pt-br/2022/download/img/R_RStudio/R_RStudio_5.png" alt="Opção Download R-4.2.1 for Windows" align="center">
</center>
<br><br>
Após o download, basta executar o arquivo e a instalação segue o formato padrão de instalação de programas no Windows. Após a instalação, ao abrir o R, é possível perceber que a interface gráfica é bem simples, sem muitos recursos gráficos, pois o foco está na linguagem de programação em si. 
<br><br>
<center>
<img src="https://raw.githubusercontent.com/desirrepetters/GENE7010-dataviz/master/userguide/content/pt-br/2022/download/img/R_RStudio/R_RStudio_6.png" alt="Interface gráfica do R" align="center">
</center>
<br><br>
Para facilitar o controle e visualização do código sendo elaborado, existem softwares à parte que fornecem uma interface gráfica para o R, sem alterar o funcionamento do programa e da linguagem de programação. Uma das interfaces mais utilizadas é o RStudio, que também utilizaremos no contexto da disciplina.
</div>

## Download e Instalação do RStudio

<div align="justify">
Para instalar o RStudio, clique <a href="https://www.rstudio.com">aqui</a> para acessar a página principal do projeto, e na parte inferior da página, clique em "Products" e depois em "RStudio Desktop":
<br><br>
<center>
<img src="https://raw.githubusercontent.com/desirrepetters/GENE7010-dataviz/master/userguide/content/pt-br/2022/download/img/R_RStudio/R_RStudio_7.png" alt="Opção Products e RStudio Desktop" align="center">
</center>
<br><br>
Em seguida, selecione a opção "Download RStudio Desktop":
<br><br>
<center>
<img src="https://raw.githubusercontent.com/desirrepetters/GENE7010-dataviz/master/userguide/content/pt-br/2022/download/img/R_RStudio/R_RStudio_8.png" alt="Opção Download RStudio Desktop" align="center">
</center>
<br><br>
Na página seguinte, escolha a opção "Download" sob o item "RStudio Desktop Free":
<br><br>
<center>
<img src="https://raw.githubusercontent.com/desirrepetters/GENE7010-dataviz/master/userguide/content/pt-br/2022/download/img/R_RStudio/R_RStudio_9.png" alt="Opção RStudio Desktop Free" align="center">
</center>
<br><br>
Em seguida, clique em "Download RStudio for Windows". Caso esteja utiizando outro sistema operacional, há outras opções logo abaixo sob a seção "All Installers":
<br><br>
<center>
<img src="https://raw.githubusercontent.com/desirrepetters/GENE7010-dataviz/master/userguide/content/pt-br/2022/download/img/R_RStudio/R_RStudio_10.png" alt="Opção Download RStudio for Windows" align="center">
</center>
<br><br>
Após o download, basta executar o arquivo e a instalação segue o formato padrão de instalação de programas no Windows.
</div>