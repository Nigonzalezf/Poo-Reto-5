# Poo-Reto-5
Para este reto se busca organizar clases mediante la creación de paquetes y modulos.

## Con un modulo _Shape_ unico
En este caso se utiliza un paquete, que solo tiene un modulo, en donde se incluyen todas las clases de las figuras geometricas.

```
Shapes/
│   ├── __pyache__/
│   ├── __init__.py
│   ├── shape.py
└── main.py
```

## Modulos Individuales
En contraposición al primer metodo, en este se crean un paquete con multiples modulos, uno para cada tipod de figura y las clases creadas anteriormente mediante herencia.

```
Shapes/
│   ├── Shapes_types/
│   ├── __pyache__/
│   ├── __init__
│   ├── point.py
│   ├── line.py
│   ├── triangle.py
│   ├── square.py
│   ├── rectangle.py
└── main.py
```
