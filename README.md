# Sorting Algorithm Visualizer

## Description
Sorting algorithm visualizer developed in **Python** using the **Pygame** library.
The program displays, in real time, the operation of *in-place* sorting algorithms, showing each comparison and swap of elements using animated vertical bars.

The project currently implements:

-  Bubble Sort  
-  Insertion Sort  
- Ascending order
- Descending order
- Reset (generate a new random list)

## Requirements

- Python 3.8 or higher  
- `pygame` library

Install pygame with:

```bash
pip install pygame
```

## Execution
Save the code to a file (for example sorting.py) and run:

````bash
python sorting.py
````

## Controls

- R — Reset: generate a new random list
- SPACE — Start sorting (separate from selection mode)
- A — Ascending order
- D — Descending order
- I — Select Insertion Sort
- B — Select Bubble Sort

## Configurable parameters
At the beginning of the **main()** function you can find:

```python
n = 50        # número de elementos
min_val = 0   # valor mínimo
max_val = 100 # valor máximo
draw_info = DrawInformation(800, 600, lst) # largura x altura da janela
clock.tick(60) # FPS
```