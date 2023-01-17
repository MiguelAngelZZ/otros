# otros

en python muestrame todas las maneras de filtrar un dataframe por texto 

1. Usar el método str.contains() para filtrar un dataframe por texto.
2. Usar el método str.startswith() para filtrar un dataframe por texto.
3. Usar el método str.endswith() para filtrar un dataframe por texto.
4. Usar el método str.match() para filtrar un dataframe por text

dame un ejemplo y explicación  de cada metodo anterior  y ademas explicar sus principales parametros 

1. str.contains(): Esta función busca una cadena de texto específica dentro de una columna de un dataframe. Por ejemplo, si queremos encontrar todas las filas que contengan la palabra "perro" en la columna "Animal", podemos usar el siguiente código:

df[df
  ['Animal']
  .str.contains('perro')]

Los principales parámetros de esta función son:

pat (str): La cadena de texto que se busca en la columna.
case (bool): Si es True, la búsqueda será sensible a mayúsculas y minúsculas. Si es False, la búsqueda no tendrá en cuenta mayúsculas y minúsculas.
flags (int): Una bandera para indicar cómo se realiza la búsqueda.
na (bool): Si es True, los valores NaN se tratarán como coincidencias. Si es False, los valores NaN no se tendrán en cuenta.

2. str.startswith(): Esta función busca una cadena de texto específica al principio de una columna de un dataframe. Por ejemplo, si queremos encontrar todas las filas que comiencen con la palabra "perro" en la columna "Animal", podemos usar el siguiente código:

df[df
  ['Animal']
  .str.startswith('perro')]

Los principales parámetros de esta función son:

pat (str): La cadena de texto que se busca al principio de la columna.
case (bool): Si es True, la búsqueda será sensible a mayúsculas y minúsculas. Si es False, la búsqueda no tendrá en cuenta mayúsculas y minúsculas.
flags (int): Una bandera para indicar cómo se realiza la búsqueda.
na (bool): Si es True, los valores NaN se tratarán como coincidencias. Si es False, los valores NaN no se tendrán en cuenta.

3. str.endswith(): Esta función busca una cadena de texto específica al final de una columna de un dataframe. Por ejemplo, si queremos encontrar todas las filas que terminen con la palabra "perro" en la columna "Animal", podemos usar el siguiente código:

df[df
  ['Animal']
  .str.endswith('perro')]

Los principales parámetros de esta función son:

pat (str): La cadena de texto que se busca al final de la columna.
case (bool): Si es True, la búsqueda será sensible a mayúsculas y minúsculas. Si es False, la búsqueda no tendrá en cuenta mayúsculas y minúsculas.
flags (int): Una bandera para indicar cómo se realiza la búsqueda.
na (bool): Si es True, los valores NaN se tratarán como coincidencias. Si es False, los valores NaN no se tendrán en cuenta.

4. str.match(): Esta función busca un patrón de texto específico dentro de una columna de un dataframe. Por ejemplo, si queremos encontrar todas las filas que contengan la palabra "perro" en la columna "Animal", podemos usar el siguiente código:

df[df
  ['Animal']
  .str.match('perro')]

Los principales parámetros de esta función son:

pat (str): El patrón de texto que se busca en la columna.
case (bool): Si es True, la búsqueda será sensible a mayúsculas y minúsculas. Si es False, la búsqueda no tendrá en cuenta mayúsculas y minúsculas.
flags (int): Una bandera para indicar cómo se realiza la búsqueda.
na (bool): Si es True, los valores NaN se tratarán como coincidencias. Si es False, los valores NaN no se tendrán en cuenta.
