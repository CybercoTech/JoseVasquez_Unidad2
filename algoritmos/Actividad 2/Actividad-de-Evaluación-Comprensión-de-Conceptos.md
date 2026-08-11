# Actividad de Evaluación: Comprensión de Conceptos


### Parte 1: Identificar Algoritmos
Responde si los siguientes enunciados representan un algoritmo. Justifica la respuesta:

1. **Una página web.**
   * **Falso.** Una página web es un documento hipertextual estructurado mediante lenguajes de marcado (HTML) y hojas de estilo (CSS). Constituye una estructura de datos e interfaz estática o dinámica, pero carece de un flujo de control imperativo y finito orientado a la resolución de un problema matemático o lógico autónomo.

2. **Una receta para hacer un pastel, donde se indican ingredientes y pasos a seguir.**
   * **Verdadero.** Es una analogía heurística exacta de un algoritmo. Posee un estado inicial o conjunto de entradas (ingredientes), ejecuta un procesamiento secuencial finito de instrucciones deterministas, y entrega un estado final o salida predecible (pastel). 

3. **"Piensa en un número y multiplícalo por otro".**
   * **Falso.** Carece de los principios fundamentales de definitud y finitud. La instrucción es inherentemente ambigua, no establece un dominio para el conjunto de entrada, no define el límite de la operación ni especifica el tratamiento del dato de salida o estado terminal.

4. **Un manual de instrucciones para armar un mueble, con pasos detallados y un orden claro.**
   * **Verdadero.** Representa un algoritmo puramente secuencial. Garantiza la finitud topológica transformando vectores de entrada (componentes desensamblados) en un vector de salida (estructura ensamblada) mediante operadores lógicos ordenados y no ambiguos.

5. **Una lista de compras organizada en orden alfabético.**
   * **Falso.** Es una estructura de datos unidimensional (arreglo/vector) previamente ordenada. No ejecuta acciones, evaluaciones ni contiene estructuras de control; es el resultado estático de un algoritmo de ordenamiento, no el algoritmo per se.



### Parte 2: Variables y Constantes
Indica si las siguientes afirmaciones describen una variable o una constante:

1. **El valor de la gravedad en la Tierra, $9.8 \text{ m/s}^2$.**
   * **Constante.** En el modelo cinemático estándar superficial, representa una magnitud física escalar invariable (parámetro de aceleración $g$) que no muta en el entorno de ejecución.

2. **La edad de una persona calculada con base en el año actual y su año de nacimiento.**
   * **Variable.** Representa un espacio de memoria cuyo valor flotante/entero está sujeto al diferencial temporal ($t_{\text{actual}} - t_{\text{nacimiento}}$), requiriendo asignación dinámica en tiempo de ejecución.

3. **La cantidad de dinero en una cuenta bancaria.**
   * **Variable.** El saldo es un registro numérico dinámico y transaccional, sometido a mutaciones algebraicas continuas mediante operaciones de crédito y débito.

4. **La velocidad de la luz en el vacío, $299,792,458 \text{ m/s}$.**
   * **Constante.** Es una magnitud física universal invariable ($c$) empleada como límite termodinámico absoluto en el procesamiento de modelos relativistas.

5. **El radio de un círculo.**
   * **Variable.** Representa un parámetro independiente de entrada ($r$) cuyo valor debe ser asignado arbitrariamente en la memoria para desencadenar el cálculo de variables dependientes (perímetro, área).



### Parte 3: Características de los Algoritmos
Responde si los siguientes enunciados cumplen con las características de un algoritmo. Justifica la respuesta:

1. **Para elegir la ruta más corta entre varias ciudades, el algoritmo examina rutas candidatas, deteniéndose cuando los cambios en la distancia parecen lo suficientemente pequeños.**
   * **Falso.** Viola el principio de exactitud y precisión. El predicado "parecen lo suficientemente pequeños" es una afirmación heurística ambigua. Un algoritmo estricto requiere una condición de parada fundamentada matemáticamente (ej., $\Delta x < \epsilon$, donde $\epsilon$ es una constante de tolerancia estricta).

2. **Suma los números ingresados y muestra el resultado.**
   * **Falso.** Es una declaración de intención, no un algoritmo estructurado. Carece del principio de finitud (no especifica la condición centinela o el límite del bucle de entrada) y omite la definición y almacenamiento temporal en variables acumuladoras.

3. **Un conjunto de pasos para calcular el área de un rectángulo dado su base y altura.**
   * **Verdadero.** Determina entradas exactas (base, altura), aplica un proceso unívoco mediante cálculo matricial algebraico simple ($A = b \times h$), y devuelve una salida finita.

4. **El algoritmo cuenta el número de votos obtenidos por cada uno de los candidatos de una elección para presidente. Empieza solicitando el nombre del candidato y finaliza cuando se ingresa el valor -1.**
   * **Verdadero.** Presenta una arquitectura de bucle iterativo controlado por bandera/centinela (condición de terminación explícita mediante el valor entero -1). Gestiona un acumulador y asegura la finitud del sistema, evitando bucles infinitos y desbordamientos de memoria.



### Parte 4: Comprensión de Herramientas
Indica si las siguientes afirmaciones son ciertas o falsas respecto al pseudocódigo y diagramas de flujo:

1. **El pseudocódigo utiliza símbolos estándar para representar las operaciones lógicas.**
   * **Falso.** El pseudocódigo emplea convenciones léxicas y gramaticales estructuradas bajo notación algorítmica textual (ej., SI-ENTONCES, MIENTRAS). Son los diagramas de flujo los que utilizan topología de grafos dirigidos con simbología geométrica estandarizada (norma ANSI/ISO).

2. **Los diagramas de flujo son una representación gráfica de un algoritmo.**
   * **Verdadero.** Son modelos visuales formados por grafos que mapean el vector direccional del flujo de control, la jerarquía de las variables y la estructura condicional de la lógica computacional.

3. **El pseudocódigo debe estar escrito en un lenguaje de programación específico.**
   * **Falso.** Por definición, el pseudocódigo es de semántica agnóstica. Su objetivo fundamental es estructurar lógicamente un problema sin acoplar el pensamiento a la sintaxis del compilador subyacente (C++, Python, ensamblador, etc.).

4. **Un diagrama de flujo siempre debe tener un inicio y un fin claramente definidos.**
   * **Verdadero.** Se alinea con la teoría de programación estructurada y grafos cíclicos dirigidos. Requiere un nodo absoluto de origen global (sumidero de inicio) y al menos un nodo sumidero terminal para certificar la detención absoluta de la ejecución (finitud topológica).



### Parte 5: Estructuras de Control

**Descripción Analítica:**
Las estructuras de control (secuenciales, condicionales e iterativas) son las primitivas lógicas que dirigen la ejecución topológica del procesador. Anulan la linealidad restrictiva de los programas, posibilitando bifurcaciones condicionales (mediante la evaluación de puertas booleanas AND/OR/NOT) y la recurrencia operacional (bucles para procesar bloques de código reiterativos). Minimizan la entropía de los módulos y optimizan el ancho de banda cognitivo del programador.

**Ejemplo Práctico 1: Condicional Diario (Árbol de Decisión Lógico)**
Evaluación y despliegue del subsistema de aislamiento térmico corporal dependiendo de la medición ambiental:
* `SI (Temperatura_Exterior < 15°C) ENTONCES { Ejecutar protocolo_aislamiento_termico_pesado } SINO { Ejecutar protocolo_vestimenta_estandar }`

**Ejemplo Práctico 2: Condicional Matemático (Gestión Operativa de Combustible)**
Cálculo algebraico para determinar la trayectoria de un vector aéreo considerando variables de telemetría, resultando en una bifurcación de navegación:
* `SI ( ((Distancia_Ruta / Velocidad_Crucero) * Consumo_Combustible_Horario) > Capacidad_Tanque_Actual ) ENTONCES { Desviar a Punto_Alterno_Repostaje } SINO { Proceder Directo al Fix_Final }`
