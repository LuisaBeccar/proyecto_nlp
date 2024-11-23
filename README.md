Aqui estaré subiendo archivos para el trabajo practico del ultimo modulo del curso de Data Science que estoy haciendo den CoderHouse: NLP & Deep Learning aplicado a ciencia de datos.

primero cree un csv con descripcion de departamentos para resolver un problema de clasificadcion: predecir segun el comentario si el depto tiene balcon o no.


La serie de prompts que use para llegar al csv que use fueron:

"Quiero desarrollar un algoritmo de machine learning de clasificacion de texto. Para eso quiero que me crees una lista de 500 comentarios distintos de no mas de 100 palabras cada uno, 
que describan departamentos. la mitad que describan departamentos que tengan balcón y la otra mitad no. Dame la respuesta en formato de csv, con dos columnas, la primera que sea el comentario, 
y la segunda que diga 1 si tiene balcon y 0 si no tiene balcon."

"Mirando el archivo, hay 4 comentarios distintos cada uno se repite 125 veces. No cumple con mi condicion de que cada comentario sea unico. Por favor corrige ese requerimineto y dame un csv 
con 500 comentarios unicos, distintos dentre si. 250 que incluyan en su descripcion la presencia de espacio exterior tipo balcon, usando sinonimos del mismo, y los otros 250 que no lo mencionen 
o que nieguen que posean balcon o sus sinonimos. El fomato de csv con la priemra columna llamada "comentario" y la segunda "balcon", donde si tiene balcón el valor sea 1 y si no lo tiene, sea 0."

"Eso está mejor, ahora veo 16 comentarios diferentes, pero cada uno se repite varias veces... quiero que haya al menos 50 comentarios diferentes, unicos con las características que te describi arriba. 
Por favor construye más comentarios unicos distintos entre si para cumplir los objetivos 500 comentarios unico y distintos, de menos de 100 palabras sobre departamentos, para clasificar con o sin balcon"
