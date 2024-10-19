<h1 align='center'> Sistema de predição de preço de venda de laptops Baseado em Regressão Linear </h1>

<p align='center'>Está aplicação é um projecto da cadeira de Machine Learning desenvolvido com vista a se aprofundar os conhecimentos obtido em sala de aulas sobre diversos algoritmos de machine learning. Tem como principal função informar ao utilizador o preço máximo que pode ser aplicado em um laptop de acoro com as suas caracteristicas.</p>

<div align='center'>
  <a href="https://spring.io/" target="_blank">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/44/Spring_Framework_Logo_2018.svg" width="150" height="150" />
  </a>

  <a href="https://ml.cms.waikato.ac.nz/index.html" target="_blank">
      <img src="https://waikato.github.io/weka-wiki/img/Weka%20%28software%29%20logo.png" width="150" height="150" />
  </a>

  <a href="https://www.kaggle.com/code/owm4096/laptop-prices-eda-w-ml-models-91-8-high/" target="_blank">
      <img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*JSbnt_mxpFfkGtNtGbR40g.png" width="150" height="150" />
  </a>

  <a href="https://bootstrapmade.com/personal-free-resume-bootstrap-template/" target="_blank">
      <img src="https://bootstrapmade.com/assets/img/logo.png" width="150" height="150" />
  </a>

</div>

## 🔧 Ferramentas

- `Spring Boot:` É uma framework Java que simplifica o desenvolvimento simples de aplicações web e microserviços provendo ferramentas para criar aplicações de produção prontas com o minimo de configuração.
- `Weka:` O Weka é uma coleção de algoritmos de aprendizagem automática para resolver problemas de extração de dados do mundo real. Está escrito em Java e é executado em quase todas as plataformas. Os algoritmos podem ser aplicados diretamente a um conjunto de dados ou chamados a partir do seu próprio código Java.
- `Kaggle:` É uma plataforma de competição de ciência de dados e comunidade online para cientistas de dados e profissionais de aprendizado de máquina da Google LLC
- `BootstrapMade:` É uma plataforma especializada na conceção e desenvolvimento de Templates Bootstrap e Templates de Website de alta qualidade, empenhados em impulsionar a presença online de empresas e indivíduos. 

## 📍 Serviço

O principal serviço oferecido pelo presente projecto é a predição do preço de venda de um laptop baseado nas suas caracteristicas.
As caracteristicas necessarias para a predição do preço são as descritas abaixo:

- `Marca`
- `Modelo`
- `Processador`
- `Memoria Ram`
- `Tipo de Tela`
- `Armazenamento`
- `Placa Grafica`
- `Tamanho da Tela`

## 📄 Dataset

Composto por 13 atributos dos quais até o momento são usados 9 para a criação do modelo e para a predição de preços o Dataset tem origem no <a href="https://www.kaggle.com/code/owm4096/laptop-prices-eda-w-ml-models-91-8-high/" target="_blank">
      `Kaggle`
  </a> que servio como base e inspiração para a criação do presente projecto ainda com previsões de alteração para melhor de adaptar a realidade Moçambicana no contexto de venda de laptops. A baixo a lista dos atributos originais do dataset:

- laptop_ID
- Laptop Manufacturer
- Brand and Model
- Type (Notebook, Ultrabook, Gaming, etc.)
- Screen Size
- Screen Resolution
- Central Processing Unit (CPU)
- Laptop RAM
- Hard Disk / SSD Memory
- Graphics Processing Units (GPU)
- Operating System
- Laptop Weight
- Price (Euro)

## 📄 Pré-Processamento os dados
O modelo de Aprendizado foi feito com um dataset que sofreu varias alterações iniciando por corrigir linhas defeituosas que tinham mais de 13 atributos coisa que impossibilitava a conversão do sataset de csv para arff. Depois de feita a converção foram feitas algumas modificações dentre as quais:

- Diminuição de 13 para 9 colunas
- Modificação da coluna de preços de Euro para Metical (MZN)

Para o pré-processamento foi utilizado o weka e alguns algoritmos em java no intellij 

## 💻 Como executar a aplicação

`Primeiro Como a aplicação funciona`

Trata-se de uma aplicação web composta por uma `interface interativa` e uma `API` que recebe as caracteristicas do laptop e devolve o preço atravéz de regressão linear um algoritmo de Matchine Learning.

`Siga os passos descritos asseguir para executar a aplicação:`

1. Clone este projecto:

  ```shell
  git clone https://github.com/BenildoMorais/LapValue.git
  ```
2. Navegue para o directorio principal:

  ```shell
  cd nomeDoProjecto/
  ```
3. Abra o fixeiro index.html


Até esse ponto é possiver visisitar a pagina localmente e ver como ela funciona. Existe outra possiblilidade de acessar atravéz do link: <a href="https://benildomorais.github.io/LapValue/" target="_blank">LapVaule</a>

`Sobre a API`

Trata-se de uma aplicação complementada por uma API fornece o principal serviço da aplicação, foi desenvolvido em um projecto diferente baseando em java, weka e Spring. Devemos inicializar a API para poder ter a aplicação a funcionar por completo para isso podemos aceder ao repositório onde ela encontra-se alojada atravéz do link: <a href="https://github.com/BenildoMorais/LaptopPriceAPI" target="_blank">LaptopPriceAPI</a> 
