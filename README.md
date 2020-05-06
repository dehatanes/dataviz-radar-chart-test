# [Teste] Visualização no estilo "Radar" de competências

|                |                                                            |
| -------------- | ----------------------------------------------------------:|
| Language       | [Python 3.7](https://www.python.org/ "Python's Homepage")  |

A ideia desse projeto é propor uma maneira diferente de analisar os resultados de uma avaliação de competências (genérica) onde são fornecidas perguntas a diferentes avaliadores que podem dar uma nota que varia de 0 a 5 para aquela questão.

## Setup

Para gerar a avaliação é necessário: 
- Ter [Python 3.7](https://www.python.org/ "Python's Homepage") instalado na sua maquina
- Ter uma IDE que abra arquivos `.ipynb` OU o [jupyter notebook](https://jupyter.org/ "Jupyter's Homepage") instalado
- Intalar as libs que estão no arquivo [requirements.txt](https://github.com/dehatanes/dataviz-radar-chart-test/blob/master/requirements.txt)
```
# Se você possuir pip na sua máquina, você pode instalar as libs facilmente com o comando:
pip install -r requirements.txt
```

## Rodando o projeto

Você pode rodar o script pelo notebook [radar_chart_viz](https://github.com/dehatanes/dataviz-radar-chart-test/blob/master/radar_chart_viz.ipynb) desse repo.

Se você realizou todo o setup corretamente e clonou esse repo sem alterações você deve conseguir rodar todas as células dele sem problemas você deve conseguir visualizar um gráfico parecido com esse:

![viz_sample](https://github.com/dehatanes/dataviz-radar-chart-test/blob/master/README_files/viz_sample.gif)

Altere o arquivo [data_example.csv](https://github.com/dehatanes/dataviz-radar-chart-test/blob/master/data_example.csv) para colocar seus dados de maneira customizada. A tabela pode ter a quantidade de linhas/colunas que você precisar, as únicas condições que devem ser seguidas são:
1. A primeira coluna deve conter o nome/identificação dos avaliadores
2. A primeira linha deve conter as perguntas/tópicos avaliados
3. O "meio" da tabela corresponde ao valor avaliado por cada avaliador a cada pergunta e deve conter apenas números (de 0 a 5)

Enjoy! 

---
Made with :heart: by @dehatanes