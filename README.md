# Machine-Learning-para-clasificar-el-alfabeto-de-lenguaje-de-senales

En este código se trabajó con los datos de Lenguaje de Señas. 

Cada muestra tiene 5 características correspondientes a las flexiones de los dedos para realizar la seña del carácter correspondiente. 

Las muestras incluyen una serie de 40 a 50 muestras por cada letra del alfabeto castellano. 

Estas características no son suficientes para la clasificación de todas las letras, 
pues no es posible discriminar entre letras cuya flexión en los dedos es similar, pero difieren en el movimiento de la mano (e.g. 'i' y 'j' o 'n', 'u' y 'v').

En este repositirio se encuentra el archivo "Datos_labels.CSV" donde se encuentras las observaciones de cada variable, 
ordenadas en columna, D1 es la variable que contiene las observaciones para el dedo pulgar, D2 para el dedo indice, 
hasta llegar a D5 que corresponde a los movimientos del dedo pulgar.

Para la discriminar cada letra del alfabeto determinada por el lenguaje de señas se utilizo una red neuronal con dos capas internas de 100 nodos, 
con función de activación sigmoidal.
