[Página web ECI](https://www.escuelaing.edu.co/es/)

![alt](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQVLDsequ9PeRFTjD3td3zkx-6LIPCuO8Rd5g&usqp=CAU)

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

```python
def hanoi(n, source, helper, target):
    if n > 0:
        # move tower of size n - 1 to helper:
        hanoi(n - 1, source, target, helper)
        # move disk from source peg to target peg
        if source:
            target.append(source.pop())
        # move tower of size n-1 from helper to target
        hanoi(n - 1, helper, source, target)
```

## Tutorial git
![alt](git.png)