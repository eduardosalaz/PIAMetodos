# PIA Métodos Numéricos LMV V6
Proyecto Final de la Materia de Métodos Numéricos FIME UANL

## JupyterLab:
* Crear la tabla de contenidos de Lab y de cada Libreta

## General:
* Validar todas las entradas por su TIPO (strings, menos las no lineales)
* Interpolación:
    * Validar que el valor ingresado esté dentro del rango (no extrapolar)
* No Lineales:
    * Checar que onda con Secante
* Lineales:
    * Validar inputs en general (paridad de la matriz, que no sean multiplos las lineas, ceros)
    * Generalizar Montante, Jacobi, arreglar el mugrero que tengo en Jacobi para la salida(imprimir solo los elementos de la primera columna de todas las filas?)

## Métodos a implementar:
* Interpolación:
    - [x] Lineal
    - [x] Newton Adelante
    - [x] Newton Atras
    - [x] Newton Diferencias Divididas
    - [x] Lagrange
    
* Ecuaciones no lineales:
    - [x] Gráfico
    - [x] Bisectriz
    - [x] Punto Fijo
    - [x] Newton Raphson
    - [x] Falsa posición
    - [x] Secante
    
* Ecuaciones lineales:
    - [x] Montante
    - [x] Gauss Jordan
    - [x] Eliminación Gaussiana
    - [x] Gauss Seidel
    - [x] Jacobi
    
* Mínimos Cuadrados:
    - [x] Línea recta
    - [ ] Cuadrática
    - [ ] Cúbica 
    - [ ] Lineal con función
    - [ ] Cuadrática con función

* Integración:
    - [ ] Regla Trapezoidal
    - [ ] Newton Cotes Cerradas
    - [ ] Newton Cotes Abiertas
    - [ ] 1/3 de Simpson
    - [ ] 3/8 de Simpson

* Ecuaciones Diferenciales Ordinarias
    - [ ] Euler Adelante
    - [ ] Euler Atras
    - [ ] Euler Modificado
    * Runge Kutta:
        - [ ] 2do orden
        - [ ] 3er orden
        - [ ] 4to orden:
            - [ ] 1/3 Simpson
            - [ ] 3/8 Simpson
        - [ ] Orden Superior
