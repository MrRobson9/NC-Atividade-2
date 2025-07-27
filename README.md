# Tarefa Computacional 2: Otimização de Hiperparâmetros de Autoencoders com Meta-heurísticas

Repositório para a Tarefa Computacional 2 da disciplina de Computação Natural, referente à otimização de hiperparâmetros de um Autoencoder para extração de características e classificação de imagens.

## Descrição do Projeto

Este trabalho implementa e compara o uso de duas **Meta-heurísticas** — **Estratégia Evolutiva (ES)** e **Otimização por Enxame de Partículas (PSO)** — para encontrar a configuração ótima de um Autoencoder. O objetivo é otimizar os seguintes hiperparâmetros:

* A **arquitetura das camadas ocultas** do encoder (número de camadas e neurônios).
* A **taxa de aprendizado** do otimizador.

As características extraídas pelo melhor autoencoder encontrado são então utilizadas para treinar um classificador final de Regressão Logística. A abordagem foi avaliada no dataset **MNIST**, e o relatório científico apresenta uma análise detalhada da metodologia, uma discussão crítica sobre os resultados obtidos e recomendações para trabalhos futuros.

## Estrutura do Repositório

* **`Codigo/Tarefa Computacional 2 V2.ipynb`**: Jupyter Notebook contendo toda a implementação do código, os experimentos e a geração dos resultados e gráficos.
* **`Relatorio/NC___Atividade_2_V2.pdf`**: O relatório final em formato de artigo científico, detalhando a metodologia, a análise crítica e as conclusões.
* **`Relatorio/imagens/`**: Pasta contendo os gráficos de convergência (como `ES_PSO_v2.png`) gerados pelo notebook e utilizados no relatório.
* **`README.md`**: Este arquivo de descrição.

## Tecnologias Utilizadas

* Python 3
* Jupyter Notebook
* NumPy
* Scikit-learn
* DEAP (Distributed Evolutionary Algorithms in Python)
* Matplotlib

## Autor

* **Dylan Faria Robson**