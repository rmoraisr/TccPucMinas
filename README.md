# Modelo Supervisionado de Classificação de Sentimentos de Texto

Trabalho de Conclusão de Curso apresentado ao Curso de Especialização em
Ciência de Dados e Big Data como requisito parcial à obtenção do título de
especialista.

![](https://github.com/rmoraisr/TccPucminas/blob/master/scripts/13_TCC/assets/fig/canvas_presentation.jpeg)

* Apresentação baseada no Data Science Workflow Canvas proposto por [Jasmine Vasandani
](https://towardsdatascience.com/a-data-science-workflow-canvas-to-kickstart-your-projects-db62556be4d0).

## Opção para execução dos Jupyter Notebooks

Opção experimental que dispensa fazer qualquer instalação na máquina local, pode ser executada a partir do repositório [Binder](https://mybinder.org/v2/gh/rmoraisr/TccPucminas/HEAD).

Na primeira execução tirar os comentários e executar os comandos da prmeira célula reproduzida a seguir:

```python
# Pacotes necessários (tirar o comentário para instalar)
!pip install pandas
!pip install matplotlib
!pip install sklearn
!pip install nltk
!pip install lime
!pip install seaborn
!pip install matplotlib_venn
```

É recomendável ainda, incluir o código a seguir no ínicio do jupyter notebook. Esse código impede de ser impresso os avisos de versão entre outros. São avisos que não interferem na execução do código.

```python
import warnings
warnings.filterwarnings("ignore")
```

