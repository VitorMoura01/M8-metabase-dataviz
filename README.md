# M8-metabase-dataviz

## Barema

- Criacão de Data Visualization com Metabase, Grafana ou PowerBl
- Escolha e justificativa da ferramenta de visualização de dados (Metabase, Grafana ou PowerBi) para o
projeto;
- Configuração correta da ferramenta escolhida para importar e processar os dados;
- Desenvolvimento de um dashboard ou visualizaçao de dados que represente de forma eficaz as
informações do dataset;
- Aplicacão de técnicas adequadas de visualização para facilitar a interpretação e analise dos dados.
- Documentação completa da visualizaçáo, incluindo legenda, rótulos uma interpretação clara dos
dados apresentados;
- Explicação detalhada no readme do processo de escolha da ferramenta, configuração, criação da
visualização e análise dos dados;
- A clareza e precisão na documentação e explicação serao avaliadas. Erros ortograficos e gramaticais
serāo penalizados, com desconto de até 20% dos pontos.
 - - Avancado (9,1 - 10): cumpriu todos os 6 itens descritos acima;
 - - Intermediário (7,1 - 9):cumpriu 5 dos 6 itens descritos acima;
 - - Básico (4,] - 7): cumpriu 4 dos 6 itens descritos acima
 - - Insuficiente (0- 4): cumpriu menos que 3 itens descritos acima."

## Introdução
O Metabase oferece uma interface intuitiva e amigável, facilitando a criação de visualizações de dados mesmo para usuários não técnicos, como pode ser o caso de algum consultor cliente. Além disso, sua integração fácil com diversas fontes de dados permite uma análise abrangente em um único ambiente. Assim, temos uma fácil usabilidade e integração com os bancos de dados do Redshift que está sendo utilizado na arquitetura da solução, tornando-o uma escolha eficiente para a visualização de dados para o projeto. Para fins de demonstração, foi desenvolvida a partir do Metabase a visualização de uma VIEW criada no Redshift, essa que ajudará a encontrar o estabelecimentos com o maior volume de vendas de acordo com os dados fornecidos.

## Visualização
Para acessar a visualização do gráfico clique nesse link: 
http://ec2-52-3-247-124.compute-1.amazonaws.com/question/77-valor-vendido-por-nome-fantasia 

![image](https://github.com/VitorMoura01/M8-metabase-dataviz/assets/99188092/d2ef5d46-d5ec-4f70-8475-66f5a936e005)

Nesse gráfico é possível visualizar os nomes fantasias com maior número de vendas. Como pode se observar, as empresas com maior volume de vendas são
- Sabor caseiro
- Restaurante bom sabor
- Restaurante sabor caseiro

O gráfico tem sua visualização configurada usando um função logarítimica, escolha feita considerando a grande variação de valor entre os dados de estabelecimentos e a variável Outro, com volume de 36,556,361 reais. Assim, a visualização das distâncias de volume pela diferença de tamanho das barras torna-se mais visível. 

