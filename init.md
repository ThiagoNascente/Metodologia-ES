## ATIVIDADE

Green AI na Engenharia de Software: Eficiência Tokenômica, Custo Computacional e Impacto Ambiental de Agentes  

Escopo: Mapeamento sistemático do custo financeiro, pegada de carbono e consumo energético gerados por pipelines agênticos no ciclo de vida de software. Avalia o trade-off entre o ganho de acurácia obtido por estratégias de raciocínio profundo (ex.: Tree-of-Thoughts, loops iterativos de ReAct) e o volume excessivo de chamadas de inferência.  

Perguntas de Pesquisa (RQs): Qual é o custo financeiro e o consumo de tokens médio associado à resolução autônoma de um problema complexo (ex.: issues do SWE-bench)? Quais estratégias de otimização (poda de contexto, orquestração de SLMs/modelos menores e caches semânticos) reduzem os custos operacionais sem comprometer a qualidade do código produzido?  


## Resolução
Inicialmente, usando a string de busca "Green AI", na base de dados Scopus, foram selecionadas, com data de corte em setembro de 2026, todas as revisões que apresentavam o termo "Green AI" no Título, Abstract ou como palavra-chave, resultando em 43 trabalhos (bibitex dos 43 contido em `export_43.bib`). Desses, apenas 13 tratavam, de forma inequívoca, sobre "Green AI". Por exemplo, embora o trabalho "Green Energy Management in Manufacturing Based on Demand Prediction by Artificial Intelligence—A Review" (doi 10.3390/electronics13163338) estivesse contido entre os 43 iniciais, ele não trata a Green AI no sentido estrito de tornar o treinamento dos modelos de IA mais eficientes ou reduzir a pegada de água/carbono, mas sim em usar IA como uma ferramenta para ajudar fábricas e indústrias de manufatura a economizarem energia e gerenciarem seus recursos de forma mais limpa.  

Das 13 revisões analisadas (contidas em `artigos_usados_doi`), a maioria é sistemática (PRISMA), algumas são narrativas ou conceituais (doi 10.3390/en18112810 , 10.32388/8FB2P4.2 , e 10.1016/j.rser.2025.116231) e uma é prospectiva (doi 10.1016/j.adapen.2025.100243). Ademais, nenhuma delas realiza medições próprias de energia, visto que os números de redução são apurados dos estudos analisados. Por isso, os valores apresentados neste artigo são resultados relatados pelas revisões, com tarefas, linhas de base e métricas distintas, e não devem ser somados.

> O artigo criado está contido em `artigo_resolucao`