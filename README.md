**Estágio em Bioinformática no LGHM**
_________________________________________________________
- Genética de populações
- Investigação da fibrose cistíca no Pará

1. Feito:
   - visualização dos dados gnomad.lof (loss of function) e procura dos genes CFTR
   - a partir dos genes CFTR, retornar quais e quantas variantes por consequência (patogenicidade)

2. Falta:
    - heatmap relacionando variante x consequência x transcritos
    - sendo uma matriz (6, 140): 6 transcritos e 140 variantes, enquanto que a consequência são as cores do mapa de calor
      que relacionam variante e transcritos, e variar de 0 (nenhuma relação), 1 (frameshift), 2 (stop gained), 3 (splice donor) e 4 (splice acceptor)
        
        - 2.1. Dificuldades:
            - os transcritos estão mal organizados, de forma que 3 transcritos diferentes (de uma mesma variante) formam uma única string, dificultando
          o acesso individual para fazer a comparação com outras variantes.

