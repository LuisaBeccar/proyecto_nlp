Aqui estaré subiendo archivos para el trabajo practico del ultimo modulo del curso de Data Science que estoy haciendo den CoderHouse: NLP & Deep Learning aplicado a Ciencia de Datos.

------
Departamentos:
Al principio queria hacer un problema de clasificacion de descripcion de departamentos que predijera si tienen blacón o no. Para eso, como no encontre un datast con lo que yo necesitaba me propuse ver si podia crearlo yo usando chatGPT. 
La serie de prompts que use para llegar al csv que use fueron:
  "Quiero desarrollar un algoritmo de machine learning de clasificacion de texto. Para eso quiero que me crees una lista de 500 comentarios distintos de no mas de 100 palabras cada uno, que describan departamentos. la mitad que describan departamentos que tengan balcón y la otra mitad no. Dame la respuesta en formato de csv, con dos columnas, la primera que sea el comentario, y la segunda que diga 1 si tiene balcon y 0 si no tiene balcon."
  "Mirando el archivo, hay 4 comentarios distintos cada uno se repite 125 veces. No cumple con mi condicion de que cada comentario sea unico. Por favor corrige ese requerimineto y dame un csv con 500 comentarios unicos, distintos dentre si. 250 que incluyan en su descripcion la presencia de espacio exterior tipo balcon, usando sinonimos del mismo, y los otros 250 que no lo mencionen o que nieguen que posean balcon o sus sinonimos. El fomato de csv con la priemra columna llamada "comentario" y la segunda "balcon", donde si tiene balcón el valor sea 1 y si no lo tiene, sea 0."
  "Eso está mejor, ahora veo 16 comentarios diferentes, pero cada uno se repite varias veces... quiero que haya al menos 50 comentarios diferentes, unicos con las características que te describi arriba. Por favor construye más comentarios unicos distintos entre si para cumplir los objetivos 500 comentarios unico y distintos, de menos de 100 palabras sobre departamentos, para clasificar con o sin balcon"

Trabaje con el dataset creado en el colab "classification_apartments" pero por lo pequeño del dataset no me gustaban los resultados, claramente overfitteaba. Al introducir nuevos inputs con descripciones de departamentos, cometia errores muy grosos. 

--------
CoderHouseTP
Es por eso que para poder usar los modelos y desarrollar el trabajo mejor, me puse a buscar datasets, a ver si alguno me interasaba.
Encontré en Kaggle uno de enfermedades y descripcion de sintomas, que me parecio optimo.
De ahi desarrolle el nuevo trabajo en "classification_symptoms" que terminara siendo el TP_CDIII_...

En este trabajo, a partir del datast hago un desarrollo de herramientas de analisis detexto y luego aplico modelos de machine learning clasicos (Logistic Regression, Random Forest, Support Vector Machine y Gradient Boosing) para mi problema de clasificacion. Procedo a utilizar algoritmos de deepl learning con redes neuronales simples, con embeddings, convoluciones y pooling, y con LSTM. 
Finalmente prubeo un modelo de generacion de texto.
El mayor desafio que afecta mi trabajo es la baja cantidad de datos de la base y un posible sesgo de clasificacion.

