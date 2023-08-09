## Projeto 12: Análise de Performance e Eficiência de Turbinas Eólicas no Setor de Energia

Explorando a Eficiência de Turbinas Eólicas: Uma Análise de Dados Energéticos

Em um mundo cada vez mais voltado para fontes de energia sustentável, fiz um estudo para melhoria de performance e eficiência de turbinas eólicas! Combinando programação, análise de dados e técnicas de Data Vz, examinei dados do setor de energia para entender o desempenho dessas máquinas.
1. Preparando os Dados
Comecei importando os dados usando o Pandas, onde cada linha representa uma leitura de uma turbina eólica. Em seguida, fiz uma série de ajustes, renomeando colunas, convertendo formatos de data e removendo informações irrelevantes, deixando os dados prontos para análise.

2. Definindo Limite de Eficiência
Estabeleci uma regra: se a curva teórica da turbina for maior que a curva de erro aceitável (5% para cima ou para baixo), registrei o valor como 'Dentro'. Caso contrário, considerei 'Fora' ou 'Zero', dependendo do caso. Isso me permitiu identificar quando as turbinas estavam operando com eficiência ou não.

3. Exploração Visual em Formato de Dashboard
Para visualizar essas informações, criei um dashboard de gráficos usando o Seaborn e o Matplotlib. Coloquei lado a lado três gráficos essenciais: a relação entre a potência ativa e a velocidade do vento, a comparação da curva teórica com a velocidade do vento e uma visualização colorida da potência ativa com limites de eficiência para melhor distinção dos dados na perspectiva visual.

Link do Projeto no meu portfólio do GitHub: https://github.com/seppdaniel/project12-wind-turbine-analysis

#agro #eficienciaenergética #turbinaseolicas #analisededados #sustentabilidade 
