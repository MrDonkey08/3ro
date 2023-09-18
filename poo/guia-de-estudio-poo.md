|# Guía de Estudio POO C++

## Glosario

- **POO:** _Modelo de programación_ que utiliza _objetos_, _ligados mediante **mensajes**_, para la solución de problemas.
- **Clase:** Generalización de un tipo específico de objetos.
	- **Clases abstractas base:** Aquellas **clases bases** de las que _nunca se tendrá intención de crear objetos a partir de ella_. Solo sirve para englobar a sus subclases.
- **Objeto:** Conjunto de _atributos_ y _métodos_ que definen a la entidad o cosa. Un _**objeto** se deriva de una **clase**_.
- **Miembros de la clase o datos miembro de la clase:**
	- **Atributo:** Propiedades de un objeto. Por lo general, los atributos se establecen como privados.
	- **Método:** Ácción o función de un objeto.
		- **Métodos de acceso:** Métodos que permiten acceder a los _miembros privados_.
		- **Sobrecarga de métodos:** La sobrecarga de métodos es una característica que _permite a una **clase** tener **múltiples funciones** con el mismo nombre, pero con **diferentes parámetros**_. Los métodos sobrecargados _se diferencian por el tipo y/o **cantidad de sus parámetros**_.
- **Mensaje:** Nombre del método (llamada).
- **Interfaz:** _Métodos_ que pueden acceder a los _atributos del objeto_.
	- **Interfaz pública:** miembros públicos de la clase; privada y protegida
- **Encapsulamiento:** Existen dos _tipos de encapsulamiento_: 
	- **Private:** Se ocultan los _atributos_ o _métodos_ de un _objeto_ para que solo puedan ser manejados por los _**metodos** de la **misma clase**_.
	- **Protected:** Lo mismo que private con la diferencia de que tiene _comportamiento public_ para los _**métodos** de **subclases_**.
- **Constructor:** Método creado para _inicializar las variables al crear el objeto_. "Llamado, automáticamente siempre que se crea una objeto de esa clase". Tiene el mismo nombre de la clase. No hay que utilizar "void".
	- **Constructor explicito:** Aquel que _solo_ se puede utilizar para _construir un objeto de la clase correspondiente de **manera explícita**_, es decir, no se puede utilizar de manera implícita para convertir un objeto de una clase en otra.
	- **Constructor por omisión:** Aquel que _no tiene **argumentos**_. Establece a los atributos del objeto los valores establecidos en la clase o, sino están inicializados, valores por defecto como 0, "", null, etc.
	- **Constructor copia:** Cuando en el _**parámetro del constructor** se le pone como **parámetro** un **objeto**_ (declarado previamente) de la _misma clase_.
	- **Sobrecarga de constructores:** Cuando hay _más de un **constructor** en una **clase**_. Para crear más _constuctores_, solo es necesario que todos los _constructores_ tengan diferente _cantidad de **parámetros**_.
- **Argumentos por omisión:** Los argumentos son posicionales; si un argumento se omite al llamar un método o función, entonces se remplazará por su valor por defecto.

- **Herencia:** capacidad de una clase de _**heredar** características de una o más **clases base**_.
- **Polimorfismo:** Cualidad que tienen los _**objetos** de responder de diferente manera a un **mensaje**_.

---

- **Apuntador:** _Variable_ que guarda una _dirección de memoria de otra **variable**_
	- **Declaración:** tipo var2* = &var1; donde var1 y var2 son del _mismo tipo de valor_, var2 es la _variable apuntador_ y var1 es la variable al que se le extrae la _dirección de memoria_

---

- **Operador de resolución ámbito (::):** para acceder a elementos globales o de clases desde cualquier lugar del programa.
	- También se utiliza para _acceder a **miembros** de una **clase**_; _sintaxis_: nombre_clase::nombre_miembro
 
- **Operador Ternario (?):**  condición ? expresión_si_verdadero : expresión_si_falso
- **Operador de dirección (&):** &
- **Operador de desreferencia (\*):** se utiliza para acceder al _valor almacenado_ en una _dirección de memoria_ que está siendo apuntada por un _puntero_.

---

- **Acceso por referencia:** variable (Tipo apuntador)\-\>
- **Acceso por valor:** variable.

---
- **Orden en que se ejecutan los _constructores_ en una _relación jerarquica_:** Desde arriba hacia abajo, es decir, parte de la clase base, baja de clase en clase hasta llegar a la clase derivada.
- **Orden en que se ejecutan los _destructores_ en una _relación jerarquica_:** Desde abajo hacia arriba, es decir, parte de la clase derivada, y sube de clase en clase hasta llegar a la clase base.

---
"#ifndef" y "#define" para la creación de un _mecanismo de inclusión de **archivos de encabezado**_ de manera segura y _evitar la inclusión múltiple de los mismos en un **programa**_.

```cpp 

//Archivo.h

#ifndef ARCHIVO_H // Forma alternativa #if !defined (_ARCHIVO_H_)
#define ARCHIVO_H // Forma alternativa #define _ARCHIVO_H_

// cuerpo de la clase

#endif            // Forma alternativa #endif

```

---

- Aquellos _**métodos** que no modifican la estructura interna de un objeto_, se les puede establecer como **const**
-  **Notación de camello:** nombreDeLaVariable
- **Campo:** cadena de carácteres


<!--# Notas random

- **Parámetros por Referencia**
- **DOO:** Diseño Orientado a Objetos

# Temario

- POO
	- Pensar en objetos.
- Diseño de una clase de Objetos

- Diagramas de objeto
- Diagramas de clase

- Especificación de requerimientos
- ATM

- Clases abstractas y funciones virtuales puras

# Tareas extra

pp. 52 - 56 Deitel (ATM)

pp. 246 - panchito

pp. 109 panchito
pp. 109 (111) - python

pp. 567 - Fig 12.22, 12.23, 12.24, 12.25, 12.26

pp. 342, 379 (Declaraciones e inicialización de variables apuntadores



## Dudas

	setprecision
	fixed
-->