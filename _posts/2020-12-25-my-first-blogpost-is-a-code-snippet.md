--- 
title: My first blogpost is a code snippet 
author: SciDroid
date: 2020-12-25 22:45:00 -0500 
categories: [Code, Snippets] 
tags: [snippet, python] 
toc: true
img: https://yohago.tech/assets/img/sample/gist.png
typeog: article
url: https://yohago.tech/posts/my-first-blogpost-is-a-code-snippet
description: This is the first blogpost in Yo  Hago Tech my personal blog of tech and other interesting things, i...
timeiso: 2020-12-15
ogsection: code
ogtag: python
---

## Information

This is the first blogpost in Yo  Hago Tech my personal blog of tech and other interesting things, in this blogpost i go to publish a random code snippet of my gist profile.

![My Gist Profile](https://yohago.tech/assets/img/sample/gist.png) _Gist Profile_

## Snippet

```python
# importa la librería time que permite trabajar con la fecha y hora del sistema
from time import sleep

# Pregunta cuantas veces se quiere repetir el proceso.
n = int(input("Ingrese cuantas veces quiere repetir el proceso: "))

while n >= 0:  # Habilita el ciclo While

    # Pide el valor a calcular al Usuario
    valor = int(input("Ingrese el monto de dinero a calcular: "))

    n -= 1

    if valor // 50000 >= 1:  # Imprime la condición del billete de 50 mil
        billetes_de_50 = valor // 50000
        valor = valor % 50000
        # Imprime los billetes de 50 mil
        print(f"Billetes de 50 mil: {billetes_de_50}")
        sleep(2)  # Para que se espere 2 segundo y despues imprima el siguiente billete

    if valor // 20000 >= 1:  # Imprime la condición del billete de 20 mil
        billetes_de_20 = valor // 20000
        valor = valor % 20000
        # Imprime los billetes de 20 mil
        print(f"Billetes de 20 mil: {billetes_de_20}")
        sleep(2)  # Para que se espere 2 segundo y despues imprima el siguiente billete

    if valor // 10000 >= 1:  # Imprime la condición del billete de 10 mil
        billetes_de_10 = valor // 10000
        valor = valor % 10000
        # Imprime los billetes de 10 mil
        print(f"Billetes de 10 mil: {billetes_de_10}")
        sleep(2)  # Para que se espere 2 segundo y despues imprima el siguiente billete

    if valor // 5000 >= 1:  # Imprime la condición del billete de 5 mil
        billetes_de_5 = valor // 5000
        valor = valor % 5000
        # Imprime los billetes de 5 mil
        print(f"Billetes de 5 mil: {billetes_de_5}")
        sleep(2)  # Para que se espere 2 segundo y despues imprima el siguiente billete

    if valor // 2000 >= 1:  # Imprime la condición del billete de 2 mil
        billetes_de_2 = valor // 2000
        valor = valor % 2000
        # Imprime los billetes de 2 mil
        print(f"Billetes de 2 mil: {billetes_de_2}")
        sleep(2)  # Para que se espere 2 segundo y despues imprima el siguiente billete

    if valor // 1000 >= 1:  # Imprime la condición del billete de mil
        billetes_de_1 = valor // 1000
        valor = valor % 1000
        # Imprime los billetes de mil
        print(f"Billetes de mil: {billetes_de_1}")
        sleep(2)  # Para que se espere 2 segundo y despues imprima el siguiente billete

    if valor > 0:
        print(f"Quedan {valor} colones.")
        sleep(3)
```

Thanks for reading.
