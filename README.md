# A*

Projeto desenvolvido para disciplina de Complexidade de Algoritmos e Avaliação de Desempenho. 

Este é um programa Python que utiliza o algoritmo A* para encontrar o caminho mais curto em um mapa. O algoritmo A* é uma busca heurística que utiliza uma combinação de custo do caminho percorrido e uma estimativa heurística para guiar a busca até o destino.

## Sobre Programação Dinâmica

A programação dinâmica é uma técnica de otimização usada em problemas de otimização combinatória e de decisão. Ela envolve dividir um problema em subproblemas menores e resolver cada subproblema apenas uma vez, armazenando as soluções para evitar recálculos. No contexto deste programa, o algoritmo A* é uma abordagem que utiliza uma heurística para guiar eficientemente a busca pelo caminho mais curto em um grafo ou mapa.

## Como Utilizar o Programa

    Preparação do Mapa:

        Crie um arquivo de texto chamado map.txt com a definição do mapa. O arquivo deve ter pelo menos três linhas:
           
            A primeira linha deve conter as dimensões do mapa (largura e altura).
            
            A segunda linha deve indicar as coordenadas do ponto de partida.
            
            As linhas subsequentes representam a matriz de custos do mapa.

        Exemplo:

        5 5
        1 1
        0 1 0 0 0
        0 1 0 1 0
        0 0 0 1 0
        0 1 0 1 0
        0 0 0 0 0

## Execução do Programa:
   
* Execute o script Python com o comando (**python main py**) no terminal ou prompt de comando. 
    
* O programa solicitará as coordenadas do ponto de destino.

    Resultados:
        O programa exibirá o mapa com o caminho mais curto marcado com setas (← → ↑ ↓) e custos associados.
        
        A saída também indicará o custo total do caminho e as coordenadas visitadas.

### Requisitos

    Python 3.x

