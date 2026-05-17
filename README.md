# Markdown1
## Segundo 
### Tercero


#### Lista Desordenada
* Elemmentos
* En una lista
* Muy desordenada

#### Lista Ordenada
1. Esta es la lista ordenada
2. Cada punto con su numero
3. Para que se entienda el orden

#### Tabla
| Columna 1 | Columna 2 | Columna 3|
| --- | --- | --- |
| 1 | 2 | 3 |
| 4 | 5 | 6 |
| elementos | en una | tabla |


#### Imágenes 

**Acceso Local**
![Captura del Repositorio](imagen/repo_actualizado.png)

**Acceso Externo**
![Logo Markdown](https://markdown-here.com/img/icon256.png)

#### Accesos a Páginas Web
* web de [GitHub](https://github.com) 
* Consulta el [Markdown Cheatsheet oficial](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 

#### Citas
_me cito a mi mismo_
> "Lo importante es saber para no ser."
> 
> "Escuchamos el silencio mas no es un sonido."

#### Secciones de Código Fuente

**Código Python**
```python
frase = input("Escribe una frase: ")

palabras = 0
es_palabra = False 
for palabra in frase:
    if palabra == ' ':
        es_palabra = False

    else:
        if not es_palabra:
            palabras +=1
            es_palabra = True

print(palabras)
```
**Código xml**
```xml
<?xml version="1.0" encoding="UTF-8"?>
<practica>
    <nombre>markdown1</nombre>
    <autor>Marcos</autor>
    <estudios>DAW</estudios>
</practica>