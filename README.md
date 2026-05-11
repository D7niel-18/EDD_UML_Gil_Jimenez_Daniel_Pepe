# Diagrama de Actividad UML 2.5 – Confirmación de Pedido
- Profesor: Willman Acosta
- Actividad: Actividad Práctica – *AEE Modelado de Comportamiento en Sistemas de E-commerce*


## Descripción del proceso modelado

Este diagrama representa el flujo de negocio que se activa cuando un usuario pulsa "Finalizar compra" en una tienda online. El modelado sigue la especificación formal UML 2.5 del Object Management Group (OMG) y hace uso explícito de nodos de bifurcación (Fork) y sincronización (Join) para representar la concurrencia real del sistema.

## Herramientas utilizadas  
- Visual Studio Code  
- DRAW.IO

## Fases realizadas
### Fase 1: Investigación Técnica
Una especificación que define un lenguaje gráfico para visualizar, 
especificar, construir y documentar los artefactos de los sistemas de objetos distribuidos.
Fue definida en 2017. 

Entrando más en detalle, la definimos como una representacion gráfica de un bajo diseño post implementado o ya existente. Contiene elementos gráficos, nodos UML
conectados (llamados flujos), que representan elementos en el modelo de uml del sistema diseñado. 

El tipo de diagrama esta definido por simbolos graficos primarios que se muestran en el diagrama, un ejemplo claro podria ser un diagrama que muestra los casos de uso y los actores es el diagrama de casos de uso.

La clasificación de los diagramas se dividen principalmente en estructurales (estáticos) 
y de comportamiento (dinámicos):

**Diagramas Estructurales** (Estructura Estática)
**Diagrama de Clases:** El más utilizado. Muestra clases, atributos, métodos y sus relaciones.
**Diagrama de Componentes:** Muestra la organización y dependencias entre módulos de software.
**Diagrama de Despliegue:** Muestra la arquitectura física del sistema (hardware y software).
**Diagrama de Objetos:** Vista de instancias específicas de clases en un momento dado.
**Diagrama de Paquetes:** Organiza los elementos del modelo en grupos.
**Diagrama de Estructura Compuesta**: Muestra la estructura interna de una clase.
**Diagramas de Comportamiento** (Comportamiento Dinámico)
**Diagrama de Casos de Uso:** Captura los requisitos funcionales y la interacción con los actores.
**Diagrama de Secuencia**: Muestra la interacción entre objetos a lo largo del tiempo, enfatizando el orden.
**Diagrama de Actividades:** Modela el flujo de trabajo o procesos de negocio (diagrama de flujo).
**Diagrama de Máquina de Estados:** Muestra los estados por los que pasa un objeto durante su vida.
**Diagrama de Comunicación:** Se enfoca en las relaciones entre los objetos.

IBM Engineering Systems Design Rhapsody es un entorno colaborativo de diseño y desarrollo para ingenieros de sistemas
y desarrolladores de software que permite crear, probar y documentar sistemas y software en tiempo real.

Esto les permite colaborar para analizar requisitos, optimizar decisiones de diseño y validar la funcionalidad en las primeras etapas del ciclo de desarrollo. Esta línea de productos se integra con el ciclo de vida completo del desarrollo de productos, desde la especificación y el desarrollo hasta las pruebas y la entrega.

Dentro de los principales aspectos se destacan:

Compatibilidad con todas las ediciones para el modelado con UML, SysML, AUTOSAR, MARTE, DDS, MODAF*, UPDM*, multicore, MISRA-C, MISRA-C++.

Perfiles, configuraciones, estereotipos, etiquetas y API con las que puede ampliar y configurar el producto.

Un conjunto de herramientas de ingeniería de sistemas para automatizar funciones comunes de ingeniería de sistemas, incluyendo Rational Harmony para ingenieros de sistemas.

**Hay distintas versiones de Rhapsody:**

Para ingeniería de software, puede usar las ediciones Rhapsody Developer y Rhapsody Architect para software.

También tienen funciones de accesibilidad ayudando a los usuarios con discapacidad, movilidad reducida o visión limitada

El diseño UML en Rhapsody permite diseñar modelos con UML.

### Fase 2: Modelado del Proceso de Compra
<img width="835" height="1079" alt="UML_Gil_Jimenez_Daniel_Pepe (1)" src="https://github.com/user-attachments/assets/85d723c2-833b-4cf4-8c43-76979c586fda" />


### FUENTES DE CONSULTA
https://www.ibm.com/docs/en/rhapsody/9.0.1?topic=diagrams-uml-activity --> IBM Documentation: "UML activity diagrams", 2021
https://www.omg.org/spec/UML/ --> OMG (Object Management Group)
