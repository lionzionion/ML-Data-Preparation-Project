# ML-Data-Preparation-Project

# Explorando e Preparando Dados para Machine Learning com Python e scikit-learn

Olá, pessoal! 👋 Neste projeto, exploramos e preparamos uma base de dados utilizando Python e a biblioteca scikit-learn. O objetivo é tornar a base adequada para treinamento de modelos de Machine Learning.

## Módulo 07, Tarefa 01: Avaliação Inicial da Base

Começamos carregando a base de dados a partir do arquivo "demo01.csv". Realizamos uma análise inicial para entender melhor nossos dados:

1. **Variáveis:** Visualizamos as primeiras linhas do DataFrame para identificar as variáveis presentes.
2. **Tipos de Dados:** Obtivemos informações sobre os tipos de dados de cada variável.
3. **Missings:** Verificamos a quantidade de valores ausentes em cada variável.
4. **Distribuição da Variável Resposta:** Exploramos a distribuição da variável resposta "mau".
   
## Módulo 07, Tarefa 02: Construindo Metadados

Construímos metadados para descrever cada variável em nosso conjunto de dados:

Variável: Nome de cada variável.
Tipo de Dados: Tipo de dados (int, float, string, etc.).
qtd_categorias: Número de categorias distintas para cada variável qualitativa.
Módulo 07, Tarefa 03: Variáveis Dummy para scikit-learn
Criamos variáveis dummy para as variáveis qualitativas, preparando assim a base para o uso no scikit-learn. O DataFrame resultante contém apenas as variáveis necessárias para treinamento de modelos.

## Módulo 07, Tarefa 04: Avaliação da Poder de Variáveis

Realizamos uma tabela cruzada entre as variáveis "possui_email" e "posse_de_veiculo", buscando entender qual delas parece ser mais poderosa para prever a probabilidade de "mau = 1".

## Módulo 07, Tarefa 05: Salvando a Base

Finalizamos salvando a base, que será utilizada nos próximos passos do projeto.

## Como Executar o Código

Clone este repositório.
Certifique-se de ter Python e as bibliotecas necessárias instaladas.
Execute o código em um ambiente Python (Jupyter Notebook, VSCode, etc.).
Explore os resultados e adapte conforme necessário.
Espero que este projeto seja útil para quem está aprendendo sobre preparação de dados para Machine Learning. Fique à vontade para contribuir e compartilhar suas sugestões! 🚀

**Happy coding! 🖥️🤖**





