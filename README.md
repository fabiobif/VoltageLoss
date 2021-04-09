# **Prova prática**: Análise de Séries Temporais para a predição de perda em Rede Elétrica

Este notebook tem como objetivo apresentar a análise e proposta de solução (**prova prática**) para o problema descrito no processo seletivo do **Instituto Senai de Inovação em Sistemas Embarcados**, ao qual é requisito à vaga de Pesquisador em IA.

O repositório apresentada a seguinte estutura

| Notebook     |      Description      |   |
|:----------|:-------------|------:|
| [Análise exploratória dos dados](https://github.com/huggingface/transformers/blob/master/notebooks/01-training-tokenizers.ipynb)  | Apresenta a análise preliminar sobre os dados (notebook: Analise_SeriesTemporais_RedeEletrica)  |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/huggingface/transformers/blob/master/notebooks/01-training-tokenizers.ipynb) |
| [Solução](https://github.com/huggingface/transformers/blob/master/notebooks/05-benchmark.ipynb) | Apresenta uma modelo treinado para detectar perdas de tensão em uma linha de energia (notebook: Modelo_PredicaoFalha_Rede) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/huggingface/transformers/blob/master/notebooks/05-benchmark.ipynb)|
| [Dataset](https://github.com/huggingface/blog/blob/master/notebooks/03_reformer.ipynb) | Pasta que contém os datasets criados | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/patrickvonplaten/blog/blob/master/notebooks/03_reformer.ipynb)|



* **Análise exploratória dos dados**: apresenta análise preliminar sobre os dados (notebook: Analise_SeriesTemporais_RedeEletrica).
* **Solução**: apresenta uma modelo treinado para detectar perdas de tensão em uma linha de energia (notebook: Modelo_PredicaoFalha_Rede)  

---
### Definição do problema
> Linhas de tensão percorrem centenas de quilômetros para fornecer energia às cidades. Essas grandes distâncias tornam o trabalho de inspecionar manualmente as linhas em busca de danos uma tarefa complexa e cara. Esses danos levam a um fenômeno conhecido como descarga parcial - descargas parciais são descargas elétricas que ocorrem em defeitos no isolamento de cabos, também podem ocorrer nas suas interfaces (isolante e semicondutora) ou em emendas e terminais. Entre suas causas estão o envelhecimento dos componentes, contaminação do material isolante, falha de instalação, entre outras. As descargas parciais danificam gradativamente as linhas de tensão, portanto, se não forem reparadas, podem levar a uma queda de energia, danificar equipamentos ou provocar desastres ambientais.
