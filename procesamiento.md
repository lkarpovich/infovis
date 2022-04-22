# Descripción de procesamiento de los datos personales
## Datos usados
Los datos personales para el TP se usaron crudos en su mayoría con la excepción de los datos de los géneros de los libros leídos.

En el Dataset principal se encuentran dos Sheets (o libros). La primera (Libros por día) tiene información de los libros y cantidad de páginas leídas por día. También tiene datos extra como género y puntuación pero no se usaron.

La segunda Sheet (Libros) tiene informacion más detallada de cada libro, pero no asociada al tiempo. Acá se encuentran cosas como autor, género, calificación, cantidad de días que tardé en leerlo, promedio de paginas por día.

## Procesamiento
Para algunos gráficos, como el de Flourish se necesitaba hacer más procesamiento de datos. Por lo cual se creo un nuevo dataset (Géneros).

El procesamiento implicó seprar por género los libros y hacer cálculos por cada genero. Estos cálculos son: Cantidad libros leidos por género, Total de páginas leídas por género, Promedio de páginas (longitud del libro) por género, Promedio de calificación asignada por género y Promedio de días que tardo en leer por género.

#### Nota
	Dentro del dataset principal (Libros) también hay un dato procesado. Como se menciono anteriormente, se usó el dato Páginas leídas por día. Este dato se obtuvo al dividir las páginas que tiene el libro por la cantidad de días que tomó leerlo.