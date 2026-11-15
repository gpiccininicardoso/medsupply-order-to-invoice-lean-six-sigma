# MedSupply Order-to-Invoice: diagnóstico com Lean e Six Sigma

Relatório executivo de decisão sobre o processo Order-to-Invoice (do pedido à nota fiscal) de uma distribuidora fictícia de materiais hospitalares. Caso de estudo, com empresa e dados de cenário didático.

## O problema

A MedSupply (R$ 480 milhões de faturamento anual) recebe reclamações porque os pedidos chegam antes das notas fiscais. O prazo médio de recebimento (DSO) subiu de 42 para 58 dias em oito meses. O lead time médio do processo é de 34 horas, e ninguém sabia dizer em números onde o tempo se perdia. A pergunta ao comitê executivo: **por qual metodologia começar, e com que impacto esperado?**

## O que foi entregue

1. Mapa de fluxo de valor do estado atual, com a eficiência do ciclo.
2. Classificação dos desperdícios com evidência do fluxo e dos dados.
3. Análise de variação de 60 pedidos, por canal de entrada e por aprovação comercial.
4. Diagrama de Ishikawa e as três causas-raiz mais prováveis.
5. Decisão fundamentada entre Lean, Six Sigma ou combinação.
6. Plano de ação priorizado, com projeção de impacto e pedidos ao comitê.

## Principais achados

- **88% do tempo mapeado é espera.** Só 97 dos 841 minutos mapeados são trabalho efetivo (eficiência do ciclo de 11,5%; 4,8% contra as 34 h reais).
- **A "variação enorme" são três processos diferentes.** O lead time médio é de 9,7 h no portal, 22,6 h no e-mail e 60,5 h no telefone. Dentro de cada canal, a variação é pequena (18% a 22% da média).
- **Causas-raiz mais prováveis:** aprovação comercial sem alçada definida, fila manual no fiscal e dados ruins na entrada (CFOP errado em cerca de 12% das notas).
- **Cerca de 20 das 34 horas não são explicadas pelo mapa do workshop**, por falta de medição por etapa.

## A decisão

Lean e Six Sigma em sequência, começando pelo Lean, com a disciplina de medição do DMAIC em um sprint de 3 semanas. O Six Sigma entra depois, de forma pontual, no erro de CFOP. A projeção para 90 dias vai de 27,8 h (piso) a cerca de 18 h (esperado), a validar com horários reais por etapa.

## Limites do estudo

- A amostra tem 60 pedidos e não traz horário por etapa nem a data em que a nota chega ao cliente.
- Canal, aprovação comercial e valor do pedido andam juntos na amostra, então ela não separa o efeito de cada um.
- Os números de DSO são ordem de grandeza, não economia atribuível ao projeto.

## Conteúdo do repositório

| Pasta | O que tem |
| --- | --- |
| `relatorio/` | Relatório executivo completo em PDF |
| `dados/` | Amostra de 60 pedidos usada na análise (arquivo CSV) |
| `imagens/` | Mapa de fluxo de valor e diagrama de Ishikawa |

## Autora

Gabriela Piccinini

Profissional com mais de 18 anos de experiência em gestão de operações complexas, liderança de equipes e fornecedores, estruturação de processos e gestão de resultados.

Com formação em Direito, especialização em Direito Empresarial e MBAs em Gestão de Negócios e Gestão Estratégica, Excelência Operacional e Métodos Ágeis (em andamento), direciona sua atuação à melhoria contínua, governança, eficiência operacional e tomada de decisão orientada por dados.

Acredito que a excelência operacional começa pela compreensão dos processos, mas se concretiza na capacidade de transformar diagnósticos em decisões e decisões em resultados sustentáveis.

Este projeto integra meu portfólio de estudos aplicados e traduz essa visão: utilizar dados, pensamento crítico e metodologias estruturadas para identificar oportunidades de melhoria e fundamentar decisões de gestão.

