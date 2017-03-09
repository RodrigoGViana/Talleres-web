---
title: Definiciones y operaciones básicas
description: How to make an independent website with GitHub Pages.
---

A partir de la siguiente actividad, iremos presentando diferentes herramientas para llevar a cabo de las distintas tareas.

**Actividad 1**

***

Determine si el flujo es laminar o turbulento cuando fluye glicerina a 25 °C en una tubería cuyo diámetro interior es de 150 mm. La velocidad promedio es de 3.6 m/s.

***

Lo que debemos hacer en este caso es:
1. Definir una función, en este caso el número de Reynolds. 
2. Definir las variables a utilizar.
3. Introducir los valores correspondientes y calcular.
4. Dependiendo del valor, el programa debe generar un mensaje acorde al tipo de flujo de que se trate. 

### Funciones	
La ecuación para calcular el número de Reynolds es:

$$
\begin{aligned}
Re = \dfrac{vD \rho}{\mu}
\end{aligned}
$$

Python cuenta con funciones predefinidas que con frecuencia son de gran utilidad pero a continuación veremos como definir correctamente nuestra propia función. Los operadores matemáticosmás comunes son: +, -, * y /.

```python
def reynolds(v, D, rho, mu):
    Re_out = v*D*rho / mu
    return Re_out
```

La función que acabamos de definir lleva el nombre de **reynolds** y sus argumentos se escriben entre paréntesis. Para definir correctamente dicha función usamos el comando **def**. Es muy importante no olvidar los dos puntos al final de la sentencia.
	
Más adelante querremos hacer uso del valor que arroje nuestra función y por lo tanto es necesario que usemos el comando **return**. De acuerdo a lo definido hasta aquí la función reynolds devolverá un valor de nombre **Re_out** definido en la segunda línea. Es importante respetar la *identación* para obtener el resultado esperado y recordar que una vez devuelto el valor de una función esta dejará de ser ejecutada inmediatamente. Cualquier código luego de la sentencia return nunca ocurrirá.    
