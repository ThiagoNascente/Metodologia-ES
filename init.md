## ATIVIDADE

Green AI na Engenharia de Software: Eficiência Tokenômica, Custo Computacional e Impacto Ambiental de Agentes  

Escopo: Mapeamento sistemático do custo financeiro, pegada de carbono e consumo energético gerados por pipelines agênticos no ciclo de vida de software. Avalia o trade-off entre o ganho de acurácia obtido por estratégias de raciocínio profundo (ex.: Tree-of-Thoughts, loops iterativos de ReAct) e o volume excessivo de chamadas de inferência.  

Perguntas de Pesquisa (RQs): Qual é o custo financeiro e o consumo de tokens médio associado à resolução autônoma de um problema complexo (ex.: issues do SWE-bench)? Quais estratégias de otimização (poda de contexto, orquestração de SLMs/modelos menores e caches semânticos) reduzem os custos operacionais sem comprometer a qualidade do código produzido?  


## IDEIA INICIAL
Será usada apenas literatura com validação por pares. Para tal: por meio da busca na Web of science pelo termo "Green AI" no Abstrct ou keyword o bibitex foi baixado e armazenado em `bibitex_web_of_science.bib` na pasta raiz do projeto.

## PARA O FUTURO
1 - Avaliar a troca de base para a Scopus ou alguma outra. Apenas como prova de conceito, aqui foi usada a Web of science para mostrar que é viável.  

2 - Analisar o bibitex para:
- Selecionar o contexto de busca (quais artigos usar)  
- Se necessário, enriquecer a string de busca
- Com base nos pontos acima, decidir quais perguntas iremos responder em nosso artigo. Ou seja, antes de decidir o que perguntar, queremos avaliar que material temos.