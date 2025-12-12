# David Carral -- Adán -- Nezha -- Xabier

## 2º Sistemas Microinformáticos y Redes

### **Unidad: 4**   

### **Práctica Nº: 42**  

### **Título: Cifrados de la antiguedad**   

### **Fecha: 10/12/2025**  


<p align="center">
  <a href="https://centros.edu.xunta.gal/iesloispenanovo/aulavirtual/course/view.php?id=460" target="_blank">
    <img src="img/logoies.jpg" alt="IES Lois Peña Novo" width="180"/>
  </a>
</p>

<p align="center">
  <a href="https://centros.edu.xunta.gal/iesloispenanovo/aulavirtual/course/view.php?id=460" target="_blank"><b>Seguridad Informática</b></a>
</p>

<div style="page-break-after: always;"></div>

---

# Índice



Lista de cifrados de la antiguedad y la edad media

cuando, por que, ejemplo


# 1. Playfair

## 1.1. Que es?

Playfair, es un método de **cifrado** inventado por el físico *Charles Wheatstone*. Fué uno de los primeros métodos utilizados en los que el cifrado no se hacía letra a letra, sino con **grupos de dos** letras.


## 1.2. Como funciona?

En una tabla cuadrada (generalmente de 5x5), se escriben al azar las 25 letras del alfabeto que se van a utilizar.

Agrupamos el texto que vamos a cifrar en letras de dos en dos, y en caso de que quede en un número impar, se añade una **x** al final.

Cada pareja de letras se puede encuadrar según los siguientes cuatro casos:

1. Las dos letras están en la misma fila del cuadro.
2. Las dos letras están en la misma columna.
3. Las dos letras no están en la misma columna.
4. Las dos letras son iguales.

## 1.3. Funcionamiento

Este método codifica mal los pares de letras repetidas. Esto se puede solucionar *añadiendo un nulo*:

*Para evitar que se produzca el caso 4, cambiamos una de las letras por una x, el cual sería el nulo.

<br>

Si la pareja de letras a cifrar están en la misma fila, se substituyen por las letras situadas a su derecha.

<br>

Si las letras están en la misma columna, pillamos la letra inferior.

<br>

Si no están ni en la misma fila, ni en la misma columna, seleccionaremos la letra que coincida en el punto medio bloqueando los ejes en línea recta, priorizando el eje horizontal de la letra que toque en ese momento.

<br>

## 1.4. Ejemplo

| | | | | |
|-|-|-|-|-|
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |


# 2. Metodo polibios
# 3. Cifrado cesar
# 4. Cifrado de vingenenere

















