# PuLP: Programação Linear em Python

## O que é PuLP?

PuLP é uma biblioteca Python usada para a **modelagem e solução de problemas de programação linear** (LP) e programação inteira (MILP). Com PuLP, é possível definir variáveis de decisão, uma função objetivo, e restrições de maneira simples, utilizando a interface Python para resolver problemas de otimização.

## Instalação

Instale o PuLP via pip:
```bash
pip install pulp
```

## Aplicações

PuLP é amplamente utilizado em problemas de otimização, como:

1. **Minimização de custos**: Exemplo clássico é o problema de otimização de produção, onde queremos minimizar o custo total de produção e armazenamento de produtos. O problema inclui:
   - Capacidade de produção limitada.
   - Demanda semanal variável.
   - Custos de produção e estoque.
   
2. **Maximização de lucros**: Empresas podem usar o PuLP para otimizar a alocação de recursos e maximizar a receita, respeitando restrições orçamentárias e de capacidade.

3. **Alocação de recursos**: Resolve problemas de distribuição de recursos, como o planejamento de horas de trabalho, estoque e produção.

## Exemplo de Uso

Neste exemplo, o PuLP foi utilizado para otimizar a produção de camisetas de uma fábrica durante um campeonato. O objetivo foi **minimizar os custos de produção e estocagem**, considerando:
- Capacidade máxima de produção.
- Custo adicional de horas extras.
- Custo de estocagem de produtos.
- Atender à demanda semanal com otimização do estoque.

## Como Funciona?

- **Definição do problema**: Definimos se o objetivo é minimizar ou maximizar algo.
- **Variáveis de decisão**: Modelam o que está sendo otimizado (por exemplo, quantidade de produtos a serem fabricados).
- **Função objetivo**: A fórmula que queremos otimizar (minimizar ou maximizar).
- **Restrições**: Condições que precisam ser respeitadas durante a otimização (como capacidade máxima de produção ou demanda a ser atendida).

## Documentação

Acesse a [documentação oficial do PuLP](https://coin-or.github.io/pulp/) para mais detalhes sobre sua utilização.

