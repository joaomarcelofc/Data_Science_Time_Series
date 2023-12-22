[![author](https://img.shields.io/badge/author-jaomarcelofc-red.svg)](https://www.linkedin.com/in/joao-marcelo-fonseca-cunha) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/)

# Data Science Séries Temporais

Séries temporais em data science são conjuntos de dados que representam a evolução de uma variável ao longo do tempo. Esses dados são coletados em intervalos regulares (por exemplo, diariamente, semanalmente, mensalmente) e cada observação é registrada com uma marca de tempo.

As séries temporais são comumente usadas em diversas áreas, como finanças, economia, ciências sociais, climatologia, entre outras, para analisar e prever comportamentos e tendências ao longo do tempo.

A análise de séries temporais envolve a aplicação de técnicas estatísticas e matemáticas para identificar padrões, detectar sazonalidades, avaliar a presença de tendências e fazer previsões futuras com base em dados históricos.

imagem

Nosso dataset é bastante simples e relaciona o histórico de produção de eletricidade nos Estados Unidos em um intervalo de datas entre 1985 e 2018. Escolhemos esse dataset para fins de estudo de times series, por se tratar de um conjunto bastante simples, com apenas duas features.

# Séries Temporais - Prophet

imagem

Prophet é uma biblioteca de previsão de séries temporais desenvolvida pelo Facebook. Ele permite aos usuários modelar tendências sazonais e de longo prazo, bem como eventos e feriados específicos que podem afetar as séries temporais.

O Prophet é bastante robusto, simples e fácil de usar. É possível encontrar na internet exemplos de código utilizando o Prophet sem nem se preoucupar se a Série Temporal é estacionária. Em alguns casos o resultado é bom, mas nem sempre.
