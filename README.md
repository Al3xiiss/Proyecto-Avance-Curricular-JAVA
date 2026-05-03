# Sistema Académico de Avance Curricular

Proyecto desarrollado para el curso de **Programación Avanzada**. Consiste en un sistema de gestión académica robusto que permite administrar alumnos, docentes y sus respectivas cargas académicas, cumpliendo con estándares de arquitectura orientada a objetos en Java.

##  Instalación y Ejecución

### 1. Requisitos Previos
Para ejecutar este sistema, asegúrese de tener instalado:
* **Java JDK:** Versión 17 o superior.
* **IDE Recomendado:** NetBeans (facilita la gestión de proyectos Ant y la generación de Javadoc).
* **Sistema Operativo:** Windows, macOS o Linux.

### 2. Estructura de Datos
El proyecto utiliza persistencia en modo **batch** (carga al inicio y guardado al cierre). Requiere que los siguientes archivos `.txt` estén en la raíz del proyecto para funcionar correctamente:
* `alumnos.txt`: Registro base de estudiantes.
* `profesores.txt`: Registro base de docentes.
* `asignaturas_alumnos.txt`: Relación de materias y estados académicos.
* `asignaturas_profesores.txt`: Relación de materias dictadas por docentes.

---

## Documentación Técnica (Javadoc)
Este proyecto cumple con el requerimiento **SIA-O3**, contando con documentación técnica detallada de cada clase y método. 

Para visualizarla:
1. Vaya a la carpeta `dist/javadoc/`.
2. Abra el archivo **`index.html`** en su navegador favorito.

---

## Instrucciones de Uso

Al iniciar, el sistema permite elegir entre dos interfaces de usuario:
1. **Modo Consola:** Interfaz de texto optimizada para visualización rápida de datos.
2. **Modo Ventana:** Interfaz gráfica basada en `JOptionPane` para una gestión intuitiva (SIA-12).

### Funcionalidades destacadas:
* **Gestión de Alumnos:** Inserción, edición, eliminación y búsqueda avanzada.
* **Análisis de Rendimiento (KPI):** Cálculo de progreso curricular y rendimiento promedio por carrera (SIA-9).
* **Gestión de Profesores:** Asignación de carga académica y filtros por especialidad.
* **Manejo de Errores:** Implementación de excepciones personalizadas (`AtributoInvalidoException` y `EntidadNoEncontradaException`) para asegurar la integridad de los datos.

---

## Enlaces y Repositorio
* **GitHub:** [https://github.com/Al3xiiss/Proyecto-Avance-Curricular-JAVA](https://github.com/Al3xiiss/Proyecto-Avance-Curricular-JAVA)

---
*Nota: Se recomienda cerrar la aplicación utilizando la opción "Salir" del menú para asegurar que los datos en memoria se persistan correctamente en los archivos de texto (SIA-11).*
