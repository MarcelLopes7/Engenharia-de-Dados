<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1 align="center">🏗️ Pipeline de Dados - Análise Histórica do Futebol de Seleções</h1>

<p align="center">
  <strong>Introdução:</strong> Este repositório contém os arquivos e notebooks utilizados 
  na construção de um pipeline de dados em nuvem, como parte do MVP da Sprint de 
  Engenharia de Dados da Pós-Graduação em Ciência de Dados e Analytics da PUC-RJ.
</p>

<h2>📖 Projeto</h2>
<p>
    O projeto consiste na construção de um pipeline de dados utilizando a plataforma 
    Databricks Community, com foco na análise histórica da dominância das seleções 
    nacionais masculinas de futebol. Os dados utilizados provêm de diferentes arquivos 
    públicos do Kaggle, contendo informações sobre partidas internacionais, rankings da 
    FIFA, marcadores de gols e disputas de pênaltis entre seleções, com registros que 
    datam desde 1872 até os dias atuais.
</p>
<p>
    O objetivo principal é responder a perguntas relevantes sobre desempenho histórico 
    das seleções, como a que mais venceu, a mais dominante em finais, rankings de 
    artilheiros, maior invencibilidade, entre outros, por meio de um modelo estrela 
    com tabelas na camada Gold.
</p>
<p>
    O pipeline foi estruturado segundo uma arquitetura em camadas: 
    <strong>Bronze (dados brutos)</strong>, 
    <strong>Silver (dados limpos e transformados)</strong> e 
    <strong>Gold (modelo analítico dimensional)</strong>.
</p>
<p>
    As principais etapas do projeto incluem:
</p>
<ul>
    <li>Ingestão dos arquivos CSV na camada Bronze;</li>
    <li>Limpeza, padronização e integração dos dados na camada Silver;</li>
    <li>Modelagem dimensional (modelo estrela) com tabelas fato e dimensões na camada Gold;</li>
    <li>Construção de consultas SQL e visualizações para responder perguntas analíticas.</li>
</ul>

<h2>🚀 Execução do Projeto</h2>
<p>
    Todo o projeto foi executado na plataforma Databricks Community, com notebooks em Python 
    e SQL. Os notebooks com todo o roteiro do trabalho estão organizados no repositório. O notebook "MVP 
    - Engeharia de Dados - parte 1" contém a introdução, busca e coleta dos dados, além da construção do
    pipeline. O notebook "MVP - Engenharia de Dados - parte 2 - Análise e Solução do Problema" contém as
    respostas para as perguntas do problema e análises conclusivas do trabalho.
</p>

<h2>💻 Tecnologias</h2>
<p>
    <strong>Principais ferramentas utilizadas:</strong>
</p>
<ul>
    <i> Databricks Community</li>
    <i> Apache Spark (PySpark e Spark SQL)</li>
    <i> Python</li>
    <i> SQL</li>
    <i> Delta Lake</li>
    <i> Pandas, Matplotlib, Seaborn (para análises locais e visualizações complementares)</li>
</ul>

<h2>🧑‍💻 Autor</h2>
<p>
    Marcel Antonio Lopes Pereira
</p>

<h2>📄 Licença</h2>
<p>
    Feito por Marcel Antonio Lopes Pereira. Entre em contato!<br>
    <a href="https://www.linkedin.com/in/marcel-lopes-7a292b124" target="_blank">
        www.linkedin.com/in/marcel-lopes-7a292b124
    </a>
</p>

</body>
</html>
