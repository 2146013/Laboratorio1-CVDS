# **Kevin Garzón**
## *Estudiante* Ingenieria de sistemas

Estudio en la Escuela Ingenieria de Ingenieria Julio Garavito, actualmente voy en 8vo semestre con el plan de estudio numero 14 Y este semestre estoy cursando las siguientes asignaturas:

1. CVDS
2. AUPN
3. ACSO
4. EGI4
5. PSOC
6. ARTT

Las actividades que realizo a diario son:

* Estudio
* Salgo a correr
* Paseo a mi mascota


### Aquí tenemos el algoritmo recursivo correspondiente a las torres de hanoi escrito en lenguaje python:

`def hanoi(n, source, helper, target):
    if n > 0:
        # move tower of size n - 1 to helper:
        hanoi(n - 1, source, target, helper)
        # move disk from source peg to target peg
        if source:
            target.append(source.pop())
        # move tower of size n-1 from helper to target
        hanoi(n - 1, helper, source, target)`

[Página web ECI](https://www.escuelaing.edu.co/es/)
![alt](https://www.universidadesenbogota.com/wp-content/uploads/cache/images/logo-eci/logo-eci-2272543660.jpg)