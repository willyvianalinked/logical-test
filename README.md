# logical-test

Informações Gerais 

A) Sobre a entrada 

1) A entrada de seu programa deve ser lida da entrada padrão. (importados de um arquivo texto delimitado por ",")
2) A entrada é composta por vários casos de teste, cada um descrito em um número de linhas que depende do problema. 
3) Quando uma linha da entrada contém vários valores, estes são separados por um único espaço em branco; a entrada não contém nenhum outro espaço em branco. 
4) Cada linha, incluindo a última, contém o caractere final-de-linha. 
5) O final da entrada coincide com o final do arquivo. 

 


B) Sobre a saída 
1 - A saída de seu programa deve ser escrita na saída padrão. 
2 - Quando uma linha da saída contém vários valores, estes devem ser separados por um único espaço em branco; a saída não deve conter nenhum outro espaço em branco. 
3 - Cada linha, incluindo a última, deve conter o caractere final-de-linha. 
 
 
 
 
 
Problema UM  

A China está construindo um elevador espacial, que permitirá o lançamento de sondas e satélites a um custo muito mais baixo, viabilizando não só projetos de pesquisa científica como o turismo espacial. No entanto, os chineses são muito supersticiosos, e por isso têm um cuidado muito especial com a numeração dos andares do elevador: eles não usam nenhum número que contenha o dígito “4” ou a sequência de dígitos “13”. Assim, eles não usam o andar 4, nem o andar 13, nem o andar 134, nem o andar 113, mas usam o andar 103. Assim, os primeiros andares são numerados 1, 2, 3, 5, 6, 7, 8, 9, 10, 11, 12, 15, 16, . . .  Como o elevador espacial tem muitos andares, e eles precisam numerar todos os andares do elevador, os chineses pediram que você escrevesse um programa que, dado o andar, indica o número que deve ser atribuído a ele. 

Entrada  
- Cada caso de teste consiste de uma única linha, contendo um inteiro N que indica o andar cujo número deve ser determinado. 

Saída 
- Para cada caso de teste, imprima uma linha contendo um único número inteiro indicando o número. atribuído ao N-ésimo andar. 
 
Restrições 1 ≤ N ≤ 1018 
 
Exemplo 
 
Exemplo de entrada  -  Saída para o exemplo de entrada 
1                      1 
4                      5 
11                     12 
12                     15 
440                    666 
 
 




Problema DOIS 
 
 
No Brasil, vai ser realizada a sensacional final mundial da fórmula 17. Os competidores se alinham na largada e disputam a corrida. Você vai ter acesso aos grids de largada e de chegada. 
A questão é determinar o número mínimo de ultrapassagens que foram efetuadas durante a competição 
 
Entrada 
Cada caso de teste utiliza três linhas. A primeira linha de um caso de teste contém um inteiro N indicando o número de competidores. Cada competidor é identificado com um número de 1 a N. A segunda linha de cada caso tem os N competidores, em ordem do grid de largada. A terceira linha de cada caso tem os mesmos competidores, porém agora na ordem de chegada. 

Saída  
Para cada caso de teste imprima uma linha contendo um único número inteiro, que indica o número mínimo de ultrapassagens necessárias para se chegar do grid de largada ao grid de chegada. 
 
 
Restrições 
2 ≤ N ≤ 24 
 
Exemplos 
 
 
Exemplo de entrada        -     Saída para o exemplo de entrada 
5                               3        
12345                           3 
31254                           4
5  
31254  
12345  
5  
31254  
53214 
