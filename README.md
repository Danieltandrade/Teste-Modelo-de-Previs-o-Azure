# Teste-Modelo-de-Previsão-Azure

Neste README explicarei resumidamente a criação de um modelo Machine Learning rodando no Microsoft Azure. O modelo prevê o número de aluguéis de bicicletas esperados num determinado dia, com base em características sazonais e meteorológicas .

Este conteúdo foi criado para o tópico "Trabalhando com Machine Learning na Prática no Azure ML", do curso "Microsoft Azure AI Fundamentals" da escola [DIO](https://web.dio.me/home)

## Criando Conta no Portal do Azure

Primeiramente criei minha conta no Portal do Microsoft Azure no link abaixo:

- [Azure](https://azure.microsoft.com/pt-br/free/search/?ef_id=_k_CjwKCAiA8sauBhB3EiwAruTRJnzgEATWA4zgvqMsGzCATTCNe6tyv5DOMnVDrmgcsh3iXGdTPgHb8RoCr4EQAvD_BwE_k_&OCID=AIDcmmzmnb0182_SEM__k_CjwKCAiA8sauBhB3EiwAruTRJnzgEATWA4zgvqMsGzCATTCNe6tyv5DOMnVDrmgcsh3iXGdTPgHb8RoCr4EQAvD_BwE_k_&gad_source=1&gclid=CjwKCAiA8sauBhB3EiwAruTRJnzgEATWA4zgvqMsGzCATTCNe6tyv5DOMnVDrmgcsh3iXGdTPgHb8RoCr4EQAvD_BwE)

## Acessando o serviço do Azure Machine-learning

Já dentro do Microsoft Azure fiz uma busca por "Machine Learning", aparecendo o serviço "Azure Machine Learning".


## Configurando Modelos e Conjunto de Dados

### Objetivo do Modelo

- Aprendizado de máquina automatizado para previsão de aluguel de bicicletas.

### Fonte de Dados

- [Capital Bikeshare](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)

### Passos

Dentro do serviço "Azure Machine Learning" foi criado um novo Recurso, com os campos preenchidos de acordo com modelo pedido pelo curso.

Após a criação do Recurso e todas as etapas cumpridas foi clicado no link que nos leva para outra página, chamado de "Lauch Studio". Este link nos leva para o [Studio do Azure Machine Learning](https://ml.azure.com), aonde serão realizados os passos para criação do Modelo de Teste.

Após a criação de um "Novo trabalho de ML automatizado e inseridas as informações pedidas.

Foi utilizado neste projeto o modelo "Regressão", tratando-se de um modelo supervisionado de aprendizado de máquina. Posteriormente foi realizada as configurações de tarefas e selecionado modelo de computação conforme documentação.

### Análise e teste de modelo

Terminado o trabalho automatizado de aprendizado de máquina, foi avaliado o melhor modelo treinado.

O próximo passo é __implantar__ e __testar o modelo__ seguindo os passos da documentação. Para isso será necessário modificar os dados de alguma linha de código em Python.

__Código resultado do Teste apresentado abaixo:__
```
{
  "Results": [
    356.82278374343275
  ]
}
```
## Resultado

356 bicicleta alugadas em 1 dia.

## Conclusão

Baseado no modelo de Machine Learning criado dentro o Azure, obtivemos o resultado de 356 biciletas alugadas em dia, de acordo com caracteristicas meteorológicas e dia escolhido.

## Referências

- [Cloud Computing Dictionary](https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-are-machine-learning-algorithms)

## Documentação

- [ML Learn AI Fundamentals](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)

## Ferramentas e Serviços

- ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

- ![Vscode](https://img.shields.io/badge/Vscode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

- ![Azure](https://img.shields.io/badge/Azure-blue?style=for-the-badge&logo=microsoft%20azure&logoColor=blue&labelColor=FFFFFF&link=https%3A%2F%2Fimages.app.goo.gl%2FK7PN1jYJd57x4q7A8)
