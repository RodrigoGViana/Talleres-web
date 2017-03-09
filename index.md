# Motivación
Con la intención de promover la participación activa de los alumnos en su formación, mostrando nuevas herramientas y desarrollando competencias, el centro de estudiantes de la Facultad Regional Resistencia ha decidido conformar un equipo de trabajo destinado a la planificación y ejecución de talleres y cursos. 

Las actividades que este equipo de trabajo ha preparado buscan crear escenarios donde los alumnos se sientan protagonistas y puedan ensayar sin miedo a equivocarse para poder aprender.

# Introducción a Python
El taller de Python pretende mostrar un poco de la sintaxis básica de Python junto con algunos paquetes comúnmente utilizados, mediante la resolución de diferentes ejercicios. 

Las entradas mostradas a continuación son un material complementario a lo desarrollado en clase.

- [Primeros pasos](pages/Python1.html)
- [Definiciones y operaciones básicas](pages/Python2.html)
- [Paquetes](pages/Python3.html)

Python cuenta con funciones predefinidas que con frecuencia son de gran utilidad pero a continuación veremos como definir correctamente nuestra propia función. Los operadores matemáticosmás comunes son: +, -, * y /.

```python
def reynolds(v, D, rho, mu):
    Re_out = v*D*rho / mu
    return Re_out
```

La función que acabamos de definir lleva el nombre de **reynolds** y sus argumentos se escriben entre paréntesis. Para definir correctamente dicha función usamos el comando **def**. Es muy importante no olvidar los dos puntos al final de la sentencia.
	
Más adelante querremos hacer uso del valor que arroje nuestra función y por lo tanto es necesario que usemos el comando **return**. De acuerdo a lo definido hasta aquí la función reynolds devolverá un valor de nombre **Re_out** definido en la segunda línea. Es importante respetar la *identación* para obtener el resultado esperado y recordar que una vez devuelto el valor de una función esta dejará de ser ejecutada inmediatamente. Cualquier código luego de la sentencia return nunca ocurrirá.    
