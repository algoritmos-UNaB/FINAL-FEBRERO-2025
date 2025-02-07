# Algoritmos y Estructuras de Datos  
**FINAL – FEBRERO – 12 / 02 / 2025**  
**Examen Final: “El Imperio de Heisenberg en la Industria de la Metanfetamina”**

Completa los siguientes datos en la parte superior del archivo:

- **Nombre y Apellido:**
- **Email:**
- **Año, Cuatrimestre, Comisión:**
- **Carrera:**

---

## Modalidad

- **El examen es virtual pero sincrónico.**
- Los/as alumnos/as deberán conectarse al Meet, con la cámara encendida y mostrar una identificación válida (DNI/DNU).
- El examen se realizará mediante la plataforma de Github Classroom.
- Se deberá acceder al examen y al Meet sincrónico mediante el programa **Safe Exam Browser**.
- Dispondrán de **3:30 hs (tres horas y treinta minutos)** para realizar el examen.
- **Importante:** Redactar las resoluciones en los archivos correspondientes a cada ejercicio (por ejemplo: `ejercicio1.py`, `ejercicio2.py`, etc.).
- La entrega y corrección se realizará al momento de la entrega.

---

## Ejercicios

### Ejercicio 1: Listas por Comprensión  
**Tema:** Calidad de la “blue meth”  
Se tiene una lista con los porcentajes de pureza obtenidos en cada lote producido por Heisenberg. Utilizando listas por comprensión, filtra aquellos lotes cuya pureza sea **igual o superior a 95%**.

```python
# Ejemplo de lista de purezas:
purezas = [92, 96, 94, 98, 97, 90, 100, 93, 95]
```

---

### Ejercicio 2: Clases y Objetos  
**Tema:** Modelo de un laboratorio clandestino  
Implementa una clase `Laboratorio` que tenga los siguientes atributos:  
- `nombre` (nombre del laboratorio)  
- `ubicacion` (localización del laboratorio)  
- `capacidad_produccion` (cantidad máxima de producto que se puede producir en un día)

Además, implementa un método llamado `calcular_produccion` que reciba como parámetro un `factor_eficiencia` (un número decimal) y retorne la producción diaria calculada como el producto de la `capacidad_produccion` por el `factor_eficiencia`.

---

### Ejercicio 3: Teoría – Alcance y Tiempo de Vida de las Variables (Respuesta Subjetiva)  
**Tema:** La “cocina” de Heisenberg  
En el contexto de un laboratorio clandestino, la correcta gestión de la información es vital para mantener el secreto y la eficiencia de la operación. Desde tu experiencia y perspectiva, **explica cómo se podría interpretar el manejo de variables locales y globales en Python como una metáfora para el manejo de información confidencial en un laboratorio como el de Heisenberg**. En tu respuesta, aborda los siguientes puntos:  

- La diferencia entre variables locales y globales.  
- Cómo la encapsulación de información (variables locales) puede ayudar a proteger datos sensibles.  
- Las implicaciones de exponer información de manera global en contextos de alta seguridad.

---

### Ejercicio 4: Recursividad  
**Tema:** Cálculo de ganancias  
Heisenberg obtiene ganancias por cada lote vendido según la pureza del producto, siguiendo la siguiente tabla:  

- **100%:** \$1000  
- **99%:** \$800  
- **98%:** \$600  
- **97%:** \$400  
- **96%:** \$200  
- **Cualquier otro valor:** \$0  

Escribe una función recursiva que, dada una lista de purezas, calcule el total de ganancias acumuladas. La función debe tener la siguiente firma:

```python
def calcular_ganancias(purezas, n):
    # purezas: lista de enteros representando los porcentajes de pureza
    # n: cantidad de elementos a considerar (usualmente len(purezas))
    pass
```

*Ejemplo:*  
```python
purezas_lotes = [98, 100, 95, 97, 99]
total = calcular_ganancias(purezas_lotes, len(purezas_lotes))
print(total)  # Deberá imprimir la suma de las ganancias correspondientes, que en este caso de ejemplo sería: 2800
```

---

### Ejercicio 5: Pilas  
**Tema:** Registro de operaciones en el laboratorio  
Cada vez que se produce un lote, se registra una serie de eventos (por ejemplo: "mezcla de químicos", "ajuste de temperatura", "monitoreo de pureza") en una estructura de tipo pila. Implementa la funcionalidad de una pila utilizando listas enlazadas. Para ello, define la clase `Pila` que incluya:  

- Una clase interna `_Nodo` para representar cada nodo de la lista enlazada.  
- Los métodos `push` (para agregar un elemento) y `pop` (para extraer el último elemento ingresado).

---

### Ejercicio 6: Ordenamiento  
**Tema:** Ordenando lotes por pureza  
Utilizando el algoritmo de **selección**, implementa una función que ordene una lista de purezas de los lotes **de mayor a menor**.

---

### Ejercicio 7: Manejo de Archivos  
**Tema:** Registro de distribución  
Escribe un programa que lea un archivo de texto con los registros de distribución. Cada línea del archivo tendrá el siguiente formato:  

```
loteX,cantidad_vendida
```

*Ejemplo de contenido del archivo:*  
```
lote1,100
lote2,200
lote1,150
```

La función debe procesar el archivo y calcular el total de producto vendido por cada lote. La función tendrá la siguiente firma:

```python
def procesar_distribucion(archivo):
    # archivo: nombre o ruta del archivo de texto
    pass
```

---

### Ejercicio 8: Búsqueda Binaria  
**Tema:** Búsqueda de un lote por pureza  
Dada una lista **ordenada** de purezas (de menor a mayor) y un valor de pureza buscado, implementa la búsqueda binaria para determinar si existe un lote con esa pureza.

---

### Ejercicio 9: Teoría – Complejidad Computacional  
**Tema:** Análisis de algoritmos en la operación  
Responde lo siguiente:

1. Describe detalladamente cómo funciona el algoritmo de selección para ordenar elementos y cuál es su complejidad temporal en el peor caso.
2. Compara el algoritmo de selección con el de **QuickSort**, indicando las principales ventajas de este último en términos de eficiencia.  
3. Considerando el entorno de producción de un laboratorio clandestino, discute brevemente qué aspectos de la eficiencia de un algoritmo podrían influir en la toma de decisiones operativas.

---

### Ejercicio 10: Opinión y Análisis  
**Tema:** Organización de la red de distribución  
En el universo de *Breaking Bad*, la organización y el flujo de información son vitales para el éxito y la seguridad de las operaciones. Desde tu perspectiva, **¿cómo se podrían aplicar los conceptos de estructuras de datos (por ejemplo, pilas, colas, listas enlazadas) para mejorar la eficiencia y la seguridad en la organización de una red de distribución tan compleja y clandestina?**  
Justifica tu respuesta utilizando ejemplos y analogías tanto del mundo real como del universo de *Breaking Bad*.

---

**Instrucciones Finales:**  
- Revisa cuidadosamente cada ejercicio antes de entregar tu examen.  
- Asegúrate de que tus respuestas sean claras, concisas y estén bien fundamentadas.  
- ¡Buena suerte!

---
“I am the one who knocks!”
(¡Recuerda que, en el laboratorio de la vida, tú eres el que toma las decisiones!)
