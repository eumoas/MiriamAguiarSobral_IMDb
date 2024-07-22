# Desafio Ciência de Dados - Lighthouse 2024

![indicium (1)](https://github.com/user-attachments/assets/fd6834e0-8b0f-45b2-a739-16daead80523)


# Sobre o projeto

Olá! Seja bem vindo a este repositório do desafio de ciência de dados da Indicium. Nele você vai encontrar uma solução para te ajudar na tomada de decisões da indústria cinematográfica.

## Metodologia Crisp DM Model
Foi objeto de estudo um conjunto de dados cinematográfico com notas do IMDb - que é uma sigla para Internet Movie Database -  como o nome sugere, uma base de dados sobre todo tipo de produção audiovisual. É um site que está na ativa desde 1990, quando ainda era operado por um grupo de cinéfilos, e que hoje se tornou uma verdadeira ajuda para todo apaixonado por seriados, filmes e mais.

Utilizou-se a metodologia Crisp DM - Cross Industry Standard Process for Data Mining, que em português significa algo como “Processo Padrão Inter-Indústrias para Mineração de Dados”. O objetivo é desenvolver modelos a partir da análise de informações e dados de um negócio para prever futuras falhas e soluções. 

Composta por 6 etapas, ela inclui descrições das fases típicas de um projeto, as tarefas envolvidas em cada fase e uma explicação dos relacionamentos entre essas tarefas. Como um modelo de processo, o CRISP-DM fornece uma visão geral do ciclo de vida da mineração de dados.

![IMAG1](https://github.com/user-attachments/assets/d09b1e6a-42a0-42f0-9336-9aa17cee8036)


## O problema do Negócio

A indústria cinematográfica enfrenta uma grande crise. De acordo com os dados divulgados durante a CinemaCon 2024, a consultoria Gower Street Analytics prevê que o mercado cinematográfico mundial movimentará US 32,3𝑏𝑖𝑙ℎõ𝑒𝑠(𝑅  165,7 bilhões) em 2024, uma queda de US 1𝑏𝑖𝑙ℎã𝑜(𝑅  5,15 bilhões) ou 3% em relação a 2023. 

Essa diminuição, embora pareça pequena, é um golpe significativo para uma indústria que ainda tenta retornar aos níveis de bilheteria pré-pandêmicos. Em 2019, o mercado cinematográfico global movimentou US 42,5𝑏𝑖𝑙ℎõ𝑒𝑠(𝑅  218 bilhões), de acordo com dados da Comscore. Portanto, a projeção de 2024 representa uma queda de aproximadamente 24% em relação ao período anterior à pandemia (UOL, 2024).

Para enfrentar esse cenário desafiador, muitas produtoras têm utilizado a ciência de dados para projetar propostas de filmes que alcancem sucesso de bilheteria nos próximos meses. O uso de big data pode ser determinante para o sucesso na escolha do gênero, classificação etária e elenco de estrelas, visando atrair o público-alvo e maximizar o retorno financeiro.

Através da análise de dados históricos de bilheteria, preferências do público, tendências de mercado e outros insights valiosos, as produtoras podem tomar decisões mais embasadas e estratégicas na seleção de projetos cinematográficos. Essa abordagem baseada em dados pode ajudar a indústria a se adaptar mais rapidamente às mudanças no comportamento do consumidor e a oferecer conteúdo que realmente atenda às expectativas do público.

Referências:
Portal Uol: https://www.uol.com.br/splash/colunas/na-sua-tela/2024/05/19/cinema-queda-bilheteria-publico-2024.htm?cmpid=copiaecola

## Dicionário

Id Colunas: Descrição
01 Series_Title: Nome do filme
02 Released_Year: Ano de lançamento
03 Certificate: Classificação etária
04 Runtime: Tempo de duração
05 Genre: Gênero
06 IMDB_Rating: Nota do IMDB
07 Overview: Overview do filme
08 Meta_score: Média ponderada de todas as críticas
09 Director: Diretor
10 Star1: Ator/atriz #1
11 Star2: Ator/atriz #2
12 Star3: Ator/atriz #3
13 Star4: Ator/atriz #4
14 No_of_Votes: Número de votos
15 Gross: Faturamento


## Entregas do projeto

Produto A: Análise exploratória de dados (EDA)
Produto B: Achados e insights
Produto C: Modelagem Preditiva
Produto D: Teste do modelo
Produto E: Arquivo salvo.pkl
Produto F: Repositório GITHUB


# Tecnologias utilizadas

## Código
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)


## Como executar o projeto

Você pode abrir diretamente no [Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]https://colab.research.google.com/drive/1HltbtqTZrbNjZ7cC2vGoNdjkIzjPBJyO#scrollTo=GdvReh0gXD5w


Certifique-se de ajustar a variável filepath de acordo com onde salvou o arquivo de teste 'desafio_indicium_imdb.csv'

OU

```bash
# clonar repositório

[https://github.com/eumoas/LH_CD_MiriamAguiarSobral_IMDb]

# Criando ambientes virtuais (Opcional):
python -m venv venv

# Ativar o ambiente virtual:
Após criar o ambiente virtual, é necessário ativá-lo.

.\venv\Scripts\Active.ps1 no Windows PowerShell ou VsCode;
source venv/bin/activate no Linux;
source venv/Scripts/activate em bash no Windows.
Quando ativado irá aparecer uma flag como o nome do ambiente virtual na frente do nome do usuário.

# Instale as dependências
 pip install -r requirements.txt

```
# Relatório

- Relatório Canva https://www.canva.com/design/DAGLVuQC59s/pxiw7R0T4bMHJ_XAOLiTcQ/edit
  
# Autor

Miriam O. A . Sobral

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miriamaguiarsobral/)

[![Gmail](https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:eumoas@gmail.com)
