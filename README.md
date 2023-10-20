# curso_python

#  Lunes 2.10.23
  
# ·SergioCaruncho M4 - 01 - Python Notebook
  
  -Introducción
  
  -Comentarios
  
  -Errores
  
  -Tipos de objetos
  
  -Tipos de números
  
  -Conversión de tipos de objetos a otros
  
  -Booleanos
  
  # -Ejercicios
  
# ·SergioCaruncho M4 - 02 - Python Notebook
  
  -Print
  
  -Variables y tipos
  
  -Listas (iterar, for)
  
  -Operadores
  
  -Condiciones
  
  -Bucles
  
  -Funciones
  
  -Diccionarios
  
  -Módulos y paquetes
  
  -Cadenas
  
  -Generadores
  
  -Tuplas
  
  -Funciones
  
  -Avanzado Iteradores
  
  -Funciones Lambda
  
  -Funciones map, filter y reduce

 # Martes 3.10.23
  
# ·SergioCaruncho M4 - 03 - Condicionales
  
  -Condicionales
  
    -Operadores de comparación
    
  -¿Qué es cierto? (if,else)
  
  #  -Ejercicios
  
      -Superheroes
      -Años bisiestos
      -Palíndromos
    
# ·SergioCaruncho M4 - 06 - Bucles

  -Bucles
  
      -while (desuso, difícil)
      -Break
      -Continue
      
    -Iterar con for
    
  #  -Ejercicios 
    
      - 1 Contar las vocales que contiene una palabra
      
    -Generar secuencias de números
    
    -Bucles anidados
    
  #  -Ejercicios
    
      - 1 bucle con for números entre -5 y 5
      
      - 2 Imprime los elementos de la siguiente lista: Genres=[ 'rock', 'R&B', 'Soundtrack', 'R&B', 'soul', 'pop']
      
      - 3 Escribe un blucle for que imprima la siguiente lista: squares=['red', 'yellow', 'green', 'purple', 'blue']
      
      - 4 Escribe un bucle while para mostrar los valores del Rating de una lista de reproducción de un álbum almacenada en la lista PlayListRatings. Si la puntuación es inferior a 6, sal del bucle. La lista PlayListRatings está dada por: PlayListRatings = [10, 9.5, 10, 8, 7.5, 5, 10, 10]
      
      - 5 Escribe un bucle while para copiar los string 'orange' de la lista squares a la lista new_squares. Para y sal del bucle si el valor de la lista no es 'orange'
      
      - 6 Imprima los 100 primeros números de la secuencia de Fibonacci

# ·SergioCaruncho M4 - 10 - Pandas

#  -Ejercicios
  
    - 1 Obtener las primeras 3 filas de un objeto DataFrame.
    
    - 2 Obtener las últimas 3 filas de un objeto DataFrame.
    
    - 3 Seleccionar las columnas ['nombre', 'califico'] de un objeto DataFrame.
    
    - 4 Comprobar si este objeto DataFrame está vacío con empty.
    
    - 5 ..............
    
    - 6 Determinar los datos en un DataFrame que son nulos (NaN).

    -7 Modificar un valor o entrada específico de un objeto DataFrame usando loc.

    -8 Acceder a un valor o entrada específico de un objeto DataFrame usando loc.

    -9 Sumar los valores de la columna intentos con sum.

    -10 Agregar una nueva fila a un objeto DataFrame por medio de loc.

    -11 Eliminar una fila de un DataFrame con la función drop.

    -12 Mostrar los n primeros y últimos registros de un objeto DataFrame con head y tail.

    -13 Agregar una nueva columna a un DataFrame con notación de slicing.

    Recorrer un Df: Para iterar cada una de las filas de un DataFrame utilizamos la función iterrows.

    -14 Obtener como una lista Python los nombres de las columnas de un DataFrame.

    -15 Renombrar las columnas de un objeto DataFrame a partir del diccionario dado.

    -16 ·Guardar los registros de un DataFrame en un archivo de formato CSV.
        ·Prueba a descargarlos en tu PC.

#  Miercoles 4.10.23

#  ·SergioCaruncho Prophet v2 - Predecir el valor de Bitcoin

  -Cargar histórico de datos

  -Crear la gráfica del precio de apertura

  -Entrenar y predecir el modelo

  -Gráfica con el modelo entrenado y los valores de un año en futuro predecidos.

#  ·SergioCaruncho M5 - 09 - Folium (mapas)

#  -Ejercicios 

    Sabiendo que las coordinadas de Canadá son [56.130, -106.35] realiza un mapa centrado en Canadá. Elige un valor para el parámetro zoom_start que permita visualizar correctamente el país entero.

    Utiliza la página geodatos para averiguar las coordenadas de España y así realizar un mapa centrado en España.

  -Stamen Toner Maps

  -Stamen Terrain Maps

#  -Ejercicios

    Crea dos mapas centrados en España siguiendo los diferentes estilos estudiados en los ejemplos anteriores.
  
  -Mapas con indicadores (crimenes EEUU)
 
  -Mapas de Coropletas (mapa temático en el que las áreas están sombreadas o modeladas en proporción a la medida de la variable estadística que se muestra en el mapa, como la densidad de población o el ingreso per cápita)

#  Jueves 5.10.23

·SergioCaruncho SpaceX - 1 - Data Collection Api v2

  -Etapa 1: Obtencion de datos

  -Importación de librerias.

    ·Parte 1: Obtén los datos mediante peticiones GET y crea un dataframe

    Pasar datos JSON a DataFrame

    Reducir el DF a lo esencial 

    Crear nuevo DF con los datos 

    Completar las listas anteriores(launchpad, payload y core) 

    Llama ahora la función getBoosterVersion. (No devuelve nada así que no hace falta asignarle una variable. Solo instanciamos la funcion.)

    Muestra los primeros 5 valores de la lista BoosterVersion

    Aplica el resto de funciones: (No devuelven nada así que no hace falta asignarles una variable. Solo instanciamos a las funciones.)

    Finalmente creamos un dataframe desde las listas anteriores. Primero convirtámolos en un diccionario:

    Y ahora crea un dataframe de Pandas desde el diccionario. Llámalo launch_data

    Finalmente, muestra las primeras 5 filas del dataframe.

    ·Parte 2: Filtra el dataframe para que solo incluya los lanzamientos de falcon 9

    Eliminar lanzamientos del falcon 1 y quedarnos solo con los del 9

    Ahora que hemos eliminado los lanzamientos de Falcon 1 la columna FlightNumber está desajustada. Vamos a volver a ordenarla:

    ·Parte 3: Ajustes finales

    Completar valores inexistentes

    Transformar la lista Costumers en un string para que sea mas compatible con SQL 

    Ahora exporta el dataset en formato .csv con index=False y llámalo dataset_part_1.csv. Descarga el archivo porque será necesario en      la siguiente práctica.

  -Etapa 3: Análisis de datos utilizando SQL

    Tarea 1: Subir los datos a la base de datos: primero cargamos el archivo de datos dataset_part_2.csv

    Tarea 2: Queries con SQL

#  -Ejercicios

    1 Muestra las diferentes plataformas de lanzamiento

    2 Muestra 5 lanzamientos cuya plataforma empiece por 'CCS'

    3 Mustra el la masa total transportada por los lanzamientos realizados donde el cliente es NASA (CRS)

    4 Muestra la masa media tranportada por lanzamientos con serie que comienza por B1

    5 Muestra la fecha donde se realizo el primer aterrizaje exitoso sobre terreno (TRUE RTLS)

    6 Muestra las series de los cohetes que aterrizaron sobre portaviones (TRUE ASDS) con una masa entre 4000 y 6000

    7 Muestra el numero de lanzamientos que completaron su mision correctamente y aquellos que fallaron

    8 Muestra las series de los cohetes que transportaron la masa máxima

    9 Muestra los el resultados del aterrizaje, la serie del cohete y las plataforma de lanzamiento de aquellos lanzamientos fallidos o no intentados en el año 2015

    10 Muestra los resultados y la frecuencia de estos resultados entre 2010-06-04 y 2017-03-20 ordenados en orden descendiente según la frecuencia


#  Viernes  6.10.23 

    -Repaso teoría Python

    -Repaso ejercicios Python 

#  Lunes 16.10.23

·SergioCaruncho M6 - 01 - Funciones.ipynb
    
    -Funciones 

·SergioCaruncho M6 - 02 - Clases.ipynb

    -Clases

#   -Ejercicios

    1 Clases

    2 Funciones 

#  Martes 17.10.23    

    -Programación funcional

#  Miércoles 18.10.23    
    
    -RDD's

    -SparkSpy

    -Transformaciones y acciones sobre RDD's
    
#  Jueves 19.10.23    

#    -Ejercicios

      1 Transformaciones y acciones sobre RDD's
    
  
    
