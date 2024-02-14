---
marp: true
theme: default
paginate: true
---

<style>
section::after {
  content: attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total);
}
</style>

# Introducción a la computación - Temas básicos

Realizado por: Sergio Augusto Gélvez Cortés
MMXXIV

---

# ¿Qué es la informática?

Aclaración: Informática es básicamente los mismo que Ciencia de Computadores.

## ¿Ingeniería de Sistemas?

La ingeniería de sistemas es un enfoque transdisciplinar que permite la construcción, desarrollo, creación, uso y, disposición final de sistemas complejos de ingeniería, basándose en conceptos científicos, tecnológicos y de administración.

Fuente: [INCOSE - https://www.incose.org/](https://www.incose.org/)

---

# Ingeniería de Sistemas

<style>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
</style>


![w:640 center Aplicaciones de la ingeniería de sistemas width:400px height:400px](SE_APPS.jpg "Aplicaciones de la ingeniería de sistemas") 
Aplicaciones de la ingeniería de sistemas[^1] 



[^1]: http://commons.wikimedia.org/wiki/Image:Jsc2006e43519.jpg

---

# Informática o ciencias de la computación

Lo primero entonces es definir que es la computación.

Es algo diverso, que se explica mejor explicando las partes.

Intuitivamente, disciplina(s) que trata con el diseño, uso y aprovechamiento de los computadores.

---

![center Disciplinas de la comutación](CD.png)

---

# ¿Qué es un sistema?

Un conjunto de elementos, cuyas partes están relacionadas entre si.  Puede ser material o conceptual.  Se espera que aparezcan comportamientos emergentes.

La confusión del proviene del término "Sistemas de computo", muy probablemente.

---

# Ejemplos de sistemas

![width:400 center Sistema digestivo.](./dig_System.svg)

---

![width:800 Tokyo Metro center](./tokyoMetro.png)

---

### Sistema de escritura

![center width:900 Sistemas de escritura en el mundo](./writingSystems.png)

---

# ¿Qué es un computador?

Es una máquina para hacer operaciones de propósito general consideradas intelectuales. 

---

# Programas y algoritmos

### Programas

Son conjuntos de instrucciones que se entregan al computador para que realice una tarea.

### Algoritmos
 Es una descripción de un conjunto de instrucciones que se realizan para resolver un problema.

*Un programa es un concretización de un algoritmo, teniendo en cuenta un lenguaje objetivo* 

---

# Conceptualización de un computador

[Máquina de Von Neumann.](https://en.wikipedia.org/wiki/Von_Neumann_architecture)

![w:640 center Arquitectura de Von Neumman width:600 height:50%](./vonNeumann.png)

---

# Hardware y software

* Hardware: infraestructura física, en tiempos actuales, los dispositivos electrónicos en los que se realizan las operaciones. (relacionado con 'sustrato)
* Software: los programas, el conjunto de programas, rutinas, etc, que permiten que el computador haga las tareas.
> Coloquialmente - Hardware es lo que se golpea, Software es lo que se maldice, cuando algo sale mal.

---

# Clasificación del Software

* Software de sistema -> Sistema operativo y adyacentes.
* Software de aplicación.
    * Software de construcción de programas.

---

# Sistemas operativos y otro software del sistema

Son los programas necesarios para el computador funcione correctamente.  Si toda la funcionalidad básica del computador viniera en el hardware los costos de diseño y construcción (además de otros factores) los harían inviables. Un sistema operativo seguramente tendrá:

* Un nucleo donde se definen los accesos a los recursos, así como donde se alojan los controladores de los dispositivos hardware del sistema.
* Subsistemas de entrada / salida de datos
* Un mecanismo para dar instrucciones al sistema.

---

# Software para construir software

Lenguajes de programación y sus compiladores.  Estas dos herramientas en conjunto (además de otras accesorias) permiten construir todo tipo de programas.

Los hay de muchos tipos, para diversos propósitos y se pueden clasificar de varias maneras.

---

# Actividad

Realizar una revisión basándose en las siguientes preguntas:

* ¿Cómo se pueden clasificar los sistemas operativos?
* ¿Cuáles son los principales sistemas operativos que existen en la actualidad?
* Aparte de los más populares, ¿existen otros sistemas operativos actuales o históricos con notoreidad?
* ¿Qué diferencia hay entre un lenguaje de programación, el lenguaje, el idioma, el sistema de escritura? De ejemplos de cada uno, cuando corresponda.

---

* ¿Cuáles son los lenguajes de programación más populares en la actualidad? Además, nombre otros (al menos 15).  De entre estos, ¿cuáles se pueden considerar emergentes o nuevos?
* ¿Cómo se pueden clasificar los lenguajes de programación?

---

# Historia de los computadores

Hay varias formas de dividir la historia de los computadores.  Una es por los componentes hardware utilizados:

| Generación          | Período       | Componente      |
| ---                 | ---           | ---             |
| Primera generación  | 1940s - 1950s | Tubos de vacío  |
| Segunda generación  | 1950s - 1960s | Transistores    |
| Tercera generación  | 1960s - 1970s | Circuitos integrados  |
| Cuarta generación   | 1970s - Presente | Microprocesador |
| Quinta generación   | Ahora y el futuro | Varias tendencias |

---

# Tubos de vacío

Se utilizaban para realizar funciones de interrupción. (La electrónica digital se basa en la interrupción condicional de la corriente)

![Tubos de vacío w:800 center](./valvulas.jpeg)

<span style="font-size:10px">By Stefan Riepl (Quark48) - Self-photographed, CC BY-SA 2.0 de, https://commons.wikimedia.org/w/index.php?curid=14682022</span>

---

![Eniac w:700 center](./ENIAC_Penn2.jpeg)

<span style="font-size:10px">https://commons.wikimedia.org/wiki/File:ENIAC_Penn2.jpg</span>

---

# Transistores

Cumplen una función similar a los tubos de vacío, pero basándose en propiedades de los semiconductores.  Mucho menos frágiles.

![Transistores w:550 center](./Transistorer.jpg)

<span style="font-size:10px">https://commons.wikimedia.org/wiki/File:Transistorer_(cropped).jpg</spam>

---

# Circuitos Integrados

Un circuito en el que todos o varios de sus elementos están asociados e interconectados de manera indivisible. No solo transistores, sino otros elementos.  Funcionalmente independientes.

![Integrados w:500 center](./ChipAtoD.jpeg)

<span style="font-size:10px">http://www.jedec.org/standards-documents/dictionary/terms/integrated-circuit-ic<br>https://upload.wikimedia.org/wikipedia/commons/4/4f/AD570JD.jpg</span>

___

# En construcción...

---

# Software de aplicación

Permite resolver problemas o prestar servicios específicos.

Ejemplos: Office, Photoshop, Navegadores

---






