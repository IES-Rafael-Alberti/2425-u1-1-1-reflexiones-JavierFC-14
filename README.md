[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Z6NE2ogx)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16652556&assignment_repo_type=AssignmentRepo)
# Práctica 1: Introducción al desarrollo. Reflexiones.

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica010/)


---

# Título de la Actividad

## Identificación de la Actividad
- **ID de la Actividad:** P1.1 reflexiones
- **Módulo:** EDES
- **Unidad de Trabajo:** Introducción al desarrollo de software
- **Fecha de Creación:** 7/10/2024
- **Fecha de Entrega:** 20/10/2024
- **Alumno(s):** 
  - **Nombre y Apellidos:** Javier Fernández Castro
  - **Correo electrónico:** jfercas614@g.educaand.es
  - **Iniciales del Alumno/Grupo:** JFC

## Descripción de la Actividad
[Descripción detallada de la actividad, objetivos, y contexto necesario para comprenderla. Explicar en qué consiste la actividad y qué se espera que el alumno desarrolle o implemente.]

## Instrucciones de Compilación y Ejecución
1. **Requisitos Previos:**
   - [Lenguaje de programación y versión]
   - [Entorno de desarrollo o dependencias necesarias]

2. **Pasos para Compilar el Código:**
   ```bash
   [Comando para compilar el código]
   ```

3. **Pasos para Ejecutar el Código:**
   ```bash
   [Comando para ejecutar la aplicación]
   ```

4. **Ejecución de Pruebas:**
   ```bash
   [Comandos para ejecutar pruebas, si las hubiera]
   ```

## Desarrollo de la Actividad
### Descripción del Desarrollo
[Explicación de cómo se ha abordado el desarrollo de la actividad, incluyendo las decisiones de diseño, estructura del código y enfoque de resolución de problemas. Se recomienda adjuntar diagramas o capturas de pantalla si es necesario.]

### Código Fuente
[Aquí se incluirá un enlace directo a los archivos de código fuente en el repositorio, por ejemplo, si se está usando GitHub: `src/main.java` o algún enlace directo.]

### Ejemplos de Ejecución
- **Entrada 1:** Descripción de la entrada y valor de prueba.
- **Salida Esperada 1:** Explicación de la salida esperada y el resultado de la prueba.

### Resultados de Pruebas
[Aquí se detallará cómo se ha verificado la funcionalidad del código, incluyendo resultados de pruebas automatizadas o manuales, en caso de que las haya.]

## Documentación Adicional
- **Manual de Usuario:** [Enlace a la documentación del usuario, si existe]
- **Autorización de Permisos:** Verificar que el profesor tenga permisos de lectura en el repositorio para revisar el código.

## Conclusiones
[Resumen de las conclusiones alcanzadas al desarrollar la actividad, las lecciones aprendidas, y posibles mejoras que se puedan implementar en futuras entregas.]

## Referencias y Fuentes
[Aquí se listarán las fuentes consultadas para el desarrollo de la actividad, tales como documentación oficial, artículos, o cualquier recurso externo relevante.]

### Notas Adicionales:
1. **Nombres de Archivos y Repositorios:**
   - Asegúrate de que el nombre del archivo o repositorio siga la estructura definida: `XXX-idActividad-Iniciales`.
2. **Permisos:**
   - Verifica que el profesor tenga los permisos necesarios para acceder al repositorio o documento.
3. **Formato:**
   - Si se entrega en formato PDF o Google Docs, asegúrate de cumplir con el mínimo y máximo de folios establecidos.
4. **Compilación y Ejecución:**
   - Detalla claramente cómo compilar y ejecutar el código, incluyendo las instrucciones en el archivo `README.md`.


1. Relación software y hardware
1.1. Primera parte
1.1.1. Primero han de ejecutarse las 3 primeras fases: fuente, objeto y ejecutable
1.1.2. El botón envía información a nuestra memoria RAM la cual se almacena y es ejecutada por la CPU
1.1.3.Mediante diversos conectores como son el SATA, PCIe , USB...
1.2. Segunda parte
1.2.1. Los perifericos mandan información a la memoria la cual almacena esa información y el procesador se encarga de ejecutarla en forma de procesos
1.2.2. Esa información es liberada para que la memoria pueda procesar otras funciones.
1.2.3. Inicialización,ejecución y gestión de memoria
1.2.4.No se como responder esta pregunta, no entiendo.
2. Del código fuente al ejecutable
2.1. Basicamente el código fuente es el conjunto de instrucciones escritas por un programador en un lenguaje de programación, el código objeto es el resultado de compilar el código fuente y el código ejecutable es la versión final del programa, listo para funcionar.
2.2. El programa necesita ser compilado, además necesita ciertos enlaces adicionales a bibliotecas o ciertos módulos.
2.3. El paso de enlazado seguramente será el más importante de todo el proceso, puesto que reúne todas las piezas del programa en un único ejecutable.
2.4. El programa no funcionará, si falta el código objeto no podrás enlazar el programa y por tanto no podrás obtener el ejecutable, y si falta el código ejecutable no podrás ejecutar el programa debido a que faltarán ciertas instrucciones
3. Generación de código intermedio
3.1. Son códigos los cuales pueden ser ejecutados por diferentes maquinas virtuales mientras que el ejecutable es un código hecho para una plataforma específica
3.2. Son muy útiles por que permiten hacer de mediador entre un código intermedio y el hardware
3.3. Por su portabilidad, seguridad y por su optimización de tiempo de ejecución
3.4. c++