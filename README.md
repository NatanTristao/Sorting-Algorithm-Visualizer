# Sorting Algorithm Visualizer

## Descrição
Visualizador de algoritmos de ordenação desenvolvido em **Python** utilizando a biblioteca **Pygame**.  
O programa exibe, em tempo real, o funcionamento de algoritmos de ordenação *in-place*, mostrando cada comparação e troca de elementos através de barras verticais animadas.

Atualmente, o projeto implementa:

-  Bubble Sort  
-  Insertion Sort  
-  Ordenação crescente (Ascending)  
-  Ordenação decrescente (Descending)  
-  Reset da lista aleatória  

## Requisitos

- Python 3.8 ou superior  
- Biblioteca `pygame`

Instale o pygame com:

```bash
pip install pygame
```

## Execução
Salve o código em um arquivo (por exemplo sorting.py) e execute:
````bash
python sorting.py
````

## Controles 

- R — Reset: gera nova lista aleatória
- SPACE — Inicia a ordenação (separado do modo de seleção)
- A — Ordenação Ascending (crescente)
- D — Ordenação Descending (decrescente)
- I — Seleciona Insertion Sort
- B — Seleciona Bubble Sort

## Parâmetros configuráveis
No começo da função **main()** encontra-se

```python
n = 50        # número de elementos
min_val = 0   # valor mínimo
max_val = 100 # valor máximo
draw_info = DrawInformation(800, 600, lst) # largura x altura da janela
clock.tick(60) # FPS
```