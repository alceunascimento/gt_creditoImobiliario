Este repositório contém o trabalho de produção de um relatório jurisprudencial para o Grupo Temático de Crédito Imobiliário da Comissão de Direito Imobiliário e da Construção Civil da Seção do Paraná da Ordem dos Advogados do Brasil.

# Introdução

O objetivo é produzir um relatório replicável de informações sobre a posição jurisprudencial do TJPR sobre determinados temas envolvendo crédito imobiliário. A função do relatório é permitir identificar a pacificação e percolação dos precedentes definidos pelo STJ no âmbito da corte estadual, analisando a posição de cada julgado em relação às teses fixadas pelo STJ. A metodologia deve ser clara, objetiva e replicável para facilitar a manutenção do relatório. Tanto para obtenção dos dados quanto para a produção do relatório, serão adotadas tecnologias para reduzir o trabalho manual, servindo para as possibilidade de utilização da tecnologia para o dia a dia do advogado.

No resultado do relatório será possível apurar:

-   A. (primário) Acórdãos do TJPR contrarias às teses do STJ (agravo e apelação);

-   B. (secundário) Decisões monocráticas da Vice Presidência em juízo de admissibilidade em REsp nas decisões identificadas como contrárias às teses do STJ;

Esboço do relatório final:

![](images/tabela_ref.png)

O numeros representam a quantidade de decisões de cada magistrado.

> Notas:

> a execução do Item B partiria apenas dos casos em que o julgado foi contrário à posição do STJ. Isto se dá porque a base de jurisprudência do TJPR não contém as decisões de admissibilidade. Será necessário entrar no processo e identificar se houve REsp e qual foi a decisão da Vice Presidência.

> a apuração das posições deverá adotar um dos critérios: (i) magistrado como relator; ou (ii) magistrado como integrante do julgado. Esta segunda posição implica num volume de trabalho manual maior, pois o dado não esta estruturado na base do TJPR, contudo, deixa o relatório muito mais robusto e completo.

# Cronograma e estrutura

## 1. Definição de parâmetros de pesquisa (até 27/03):

-   Definir as teses (aquisição, construção/incorporação, locação);
-   Definir os verbetes;
-   Definir o formato do relatório;
-   Definir os dados que serão analisados;
-   Definir se a posição do magistrado será computada apenas quando este for o relator ou não (esta definição é crucial, pois vai impactar no volume de trabalho);
-   Definir se serão adotados apenas precedentes qualificados ou não;

## 2. Obtenção dos dados (até 18/04):

-   Dados com acessibilidade (até 03/04):
    -   Produzir um script de obtenção dos dados (R ou pyhon);
    -   Executar o script e obter os dados;
    -   Criar um dataframe com os dados obtidos;
    -   Criar um arquivo de armazenagem dos dados (json);
-   Dados sem acessibilidade (até 18/04):
    -   Dos julgados obtidos, obter dados complementares;
    -   Criar um novo arquivo de armazenagem dos dados;

## 3. Refinamento dos dados (até 26/04):

-   Incluir dados complementares da base de dados;
-   Identificar erros nos dados e ajustar;

## 4. Produção do relatório (até 31/04):

-   Produzir o relatório;

# Referências
