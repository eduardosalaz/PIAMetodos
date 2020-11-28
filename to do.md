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
* Mínimos:
   * Limpiar nombres de variables, hacerlas más comprensibles
* Integracion:
   * Validar limite inferior y superior, que n sea par o impar dependiendo del método
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
    - [x] Cuadrática
    - [x] Cúbica 
    - [x] Lineal con función
    - [x] Cuadrática con función

* Integración:
    - [x] Regla Trapezoidal
    - [x] Newton Cotes Cerradas
    - [x] Newton Cotes Abiertas
    - [x] 1/3 de Simpson
    - [x] 3/8 de Simpson

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
