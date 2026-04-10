# Análise de Decisão com Simulação de Monte Carlo
## 📌 Sobre o Projeto

Este projeto aplica Simulação de Monte Carlo para apoiar a tomada de decisão estratégica no lançamento de um novo drone pela empresa fictícia TechToy.

A análise compara duas abordagens de mercado, uma conservadora e outra agressiva, considerando incertezas em vendas e custos, com o objetivo de entender não apenas o retorno esperado, mas também os riscos envolvidos.

## Problema de Negócio
A empresa precisa decidir entre duas estratégias:

* Estratégia A (Conservadora): menor risco, maior previsibilidade
* Estratégia B (Agressiva): maior potencial de lucro, porém com alta incerteza

O desafio é tomar uma decisão baseada em dados, considerando:
* Variabilidade das vendas
* Oscilação dos custos
* Impacto do investimento inicial

## Solução Proposta
Foi utilizada a Simulação de Monte Carlo para gerar 10.000 cenários possíveis para cada estratégia, permitindo:
* Estimar o lucro médio esperado
*  Calcular a probabilidade de prejuízo
* Analisar a distribuição dos lucros
* Comparar risco vs. retorno

## Principais Resultados
| Métrica                   | Estratégia A | Estratégia B |
| ------------------------- | ------------ | ------------ |
| Lucro Médio               | R$ 224 mil   | R$ 167 mil   |
| Probabilidade de Prejuízo | 0%           | 9,31%        |
| Perfil                    | Seguro       | Arriscado    |

## 📊 Visualização


🛠️ Tecnologias Utilizadas
* Python
* NumPy (Biblioteca Python)
* Matplotlib (Bibliotaca Python)
