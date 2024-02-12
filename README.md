# PROMPT EGINEERING CON CHATGPT

**Este blog es de CusanoTech.**
Conoce la historia de OpenAI:
El éxito de OpenAI: Historia e innovación, año a año .

## ÍNDICE
**- Introducción:**

  ¿Que es ChatGPT?
  
  ¿Que significa prompt engineering y para qué sirve?
  
  ¿Por qué es importante la Ingeniería de Prompts?
  
**- Advertencias:**

  Advertencias en los LLM
  
  Principales precauciones
  
**-Estructura de un Prompt:**

  Los cuatro elementos principales de un prompt
  
  Ejemplos
  
  Detallando los cuatro elementos
  
  Consejos
  
**- Fin y despedida**

  Contacto y redes sociales

## INTRODUCCIÓN
**¿Que es ChatGPT?**
ChatGPT es un prototipo de chatbot de inteligencia artificial desarrollado en 2022 por OpenAI que se especializa en el diálogo. El chatbot es un gran modelo de lenguaje, ajustado con técnicas de aprendizaje tanto supervisadas como de refuerzo.​
Si nunca has probado ChatGPT, solo debes ingresar con tu correo y ya lo puedes utilizar haciendo clic AQUÍ.

**¿Qué significa Prompt Engineering y para qué sirve?**
Prompt Engineering es un concepto que consiste en las técnicas de descripción de tareas incrustadas en la entrada, para obtener una salida deseada por parte de los modelos de IAs, por ejemplo, una pregunta.

Este concepto se emplea en inteligencia artificial(IA) particularmente en el procesamiento de lenguaje natural (PNL, un subcampo interdisciplinario de la lingüística, la informática y la inteligencia artificial, que se ocupa de las interacciones entre las computadoras y el lenguaje humano, en particular, se enfoca en como programar a las computadoras para procesar y analizar grandes cantidades de datos del lenguaje natural (lenguaje humano)).

**¿Por qué es importante conocer la ingeniería de Prompts?**
La ingeniería de prompts es usada en la amplia variedad de procesamientos de lenguaje natural. Por ejemplo, en la creación de texto a imagen, texto a video y texto a texto.
Esta habilidad de comunicación con los modelos de lenguajes beneficia a todos. Ya estamos viendo beneficiado los sectores de Marketing, educación, negocios, software, salud y muchos más.

Adaptarnos a esta nueva revolución, donde los modelos de lenguaje están siendo cada vez más incorporados en las herramientas digitales que utiliza la gran mayoría de personas, sin importar rubros o especialización, es clave para no quedarnos fuera de lo que nos puede llegar a brindar.
Por ejemplo, una mayor productividad y automatización en nuestras tareas complejas.

## ADVERTENCIAS
**Advertencia en los LLM**
Estas herramientas como ChatGPT, Google Bard o el Chat de Bing, son herramientas útiles y seguras, pero debemos tener en cuenta que al final, es un software que está alojado en la web y que el riesgo de que tus datos sean comprometidos, aunque sea mínimo, siempre va a estar.

*Si no sabías:*
El 20 de marzo, ChatGPT tuvo un error en una de sus bibliotecas de código abierto, donde permitía a algunos usuarios a ver títulos del historial de chat de otros usuarios activos en la plataforma.
También, descubren que el mismo error pudo haber causado la visibilidad involuntaria de la información relacionada con los pagos de los suscriptores a ChatGPT Plus.
Cosa que OpenAI, luego, toma la medida de desconectar a ChatGPT por un día para resolver ese error, pudiendo más tarde restaurar el servicio y controlar la situación.

**Principales advertencias:**
- Evita compartir datos sensibles:
Evita la información sensible como contraseñas, nombres completos, dirección, número de seguro social, número telefónico, números de tarjetas financieras o cualquier información que pueda identificarte personalmente.
- Asegura tu entorno:
Evita el uso de estas LLM en redes públicas abiertas de Wi-Fi. Utiliza conexiones seguras y privadas. Puedes incluir la utilización de una VPN si lo deseas.
- No creas todo lo que dice:
La precaución de este punto es que la información médica, nutricional o de relaciones sociales, es mejor que las hables con especialistas.
Estos LLM, como sabemos, están entrenados con una inmensa cantidad de datos, pero estos datos no están supervisados en términos de su calidad o veracidad (ese es uno de los problemas que resaltan las instituciones que buscan regularización). Por otro parte, tampoco están entrenados con toda la información del universo, por eso muchas veces arrojan outputs con “delirio”, ya que inventa esas cadenas de texto recopilando lo que sí tiene en su base de datos.

## ELEMENTOS DE UN PROMPT
**Los cuatro elementos principales de un prompt**
Un buen prompt tiene una estructura, esta estructura está compuesta por cuatro elementos principales.

1. Instrucción: Una tarea o instrucción especifica que desea que el modelo realice.

2. Contexto: Adicionar información externa o contexto adicional que pueda orientar al modelo hacia mejores respuestas.

3. Datos de entrada: La entrada o pregunta para la que estamos interesados en encontrar una respuesta (el tema).

4. Indicador de salida: El tipo o formato de salida.

*No necesitas los cuatro elementos para un aviso y el formato depende de la tarea en cuestión*

Ejemplos
Ejemplos utilizando la estructura de un prompt de diferentes formas.


Ejemplo 1 y 2
En el ejemplo N1 le hicimos una pregunta simple, sin especificación ni estructura.
En el ejemplo N2 utilizamos la estructura de los cuatro elementos.
![IMAGEN](https://cdn-images-1.medium.com/max/960/1*5vyxP3bp0G9o-wbUWrogWA.png)

EJEMPLO N2

Elementos del prompt N2
Debemos saber que emplear los cuatro elementos de una estructura no significa que tendremos la mejor respuesta. Siempre dependerá el tipo de output que nosotros queramos recibir. Es decir, que en este ejemplo, la respuesta dada por ChatGPT es válida por igual.

Veamos más ejemplos


EJEMPLO N3

Elementos del prompt N3
En este ejemplo no usamos Contexto ni un formato de salida.
Más ejemplos…


EJEMPLO N4

Elementos del prompt N4
En este ejemplo sí usamos un formato de salida, pero sin contexto.
Último ejemplo…


EJEMPLO N5

Estructura del prompt N5
Aquí vemos claramente como el orden de los elementos puede variar. En este ejemplo no especificamos el dato de salida, pero sí, le dimos un contexto, el contexto de texto “formal” que le queremos dar al mensaje.
Como se ve claramente en los ejemplos, hay dos elementos que mayoritariamente no se dejan de lado. Estos son: INSTRUCCIÓN Y DATOS DE ENTRADA

Detallando los cuatro elementos de un Prompt
Elemento N1: La instrucción
Las instrucciones son comandos para indicarle al modelo lo que deseas lograr, como “Escribe”, “Clasifica”, “Resume”, “Traduce”, “Ordena”, “Crea”, “Explica”, etc.
Algunas personas recomiendan colocar las instrucciones al comienzo de la indicación. También muchas otras recomiendan utilizar separadores claros, como “###” para separar la instrucción del contexto.
### Instrucción ###
Extrae los nombres de lugares de este texto: -text-
Elemento N2: Contexto
Como ya sabemos, los modelos generativos funcionan por estadística, entonces que mejor que darles un buen contexto y aumentar la probabilidad de obtener un mejor resultado.
El contexto es igual a especificidad, cuanto más descriptivo y detallado es el prompt, mejor serán tus resultados.
También hay que saber que incluir demasiados detalles innecesarios no es necesariamente un buen enfoque. Los detalles deben ser relevantes y contribuir a la tarea en cuestión.
Elemento N3: Datos de entrada
En este elemento no hace falta explicar nada, ya lo dice el mismo nombre.
Elemento N4: Datos de salida
En este elemento no hace falta explicar nada, ya lo dice el mismo nombre.
Consejos
Tienes que empezar con la práctica. Comienza simplemente por lo simple, poco a poco puede ir armando tus prompt e ir experimentando como funciona el modelo. No hace falta ser un experto para empezar a comunicarte textualmente con ChatGPT.

Consejo N1: Cuando tienes una tarea grande que involucra muchas subtareas diferentes, puedes intentar dividir la tarea en subtareas más simples y seguir construyendo a medida que obtienes mejores resultados

Consejo N2: Comunicación efectiva; se especificó, conciso y lo más directo posible con el modelo.
Los mejores resultados que he obtenido en ChatGPT han sido cuando fui claro con lo que andaba buscando. Decirle si quiero un formato en items, la cantidad de palabras, que tema, quiero que resalte más, que estilo de texto, etc. es la clave para una comunicación efectiva.

Consejo N3: Este creo que es el consejo más importante (en mi opinión).
Al principio, cuando comencé, era muy común que el 90% de mi instrucción, era decirle que es lo que no quería. ¡Grave error!
Al diseñar prompts hay que evitar decir que es lo que no queremos que haga, en su lugar, hay que dar más énfasis a decir que es lo que si queremos que haga.

¡Gracias por llegar hasta aquí!
Espero que esta información haya sido de tu agrado.
¡Si así fue, te reto a que lo pongas en práctica y me comentes tus resultados!😄🚀
⋆ Lo que CusanoTech aprende, tú también lo aprendes ⋆
⮕ Medium / Instagram / Linkedin / Cusanotech.com
