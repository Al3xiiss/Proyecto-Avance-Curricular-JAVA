Sistema Académico de Avance Curricular
Curso: Programación Avanzada
Tema: Gestión de mallas curriculares, carga docente y métricas académicas.

Instalación y Ejecución
1. Requisitos Previos
Java JDK: Versión 17 o superior.

IDE: NetBeans (recomendado), IntelliJ IDEA o Eclipse.

Archivos de Datos: El sistema utiliza persistencia en modo batch. Asegúrese de que los archivos .txt (alumnos.txt, profesores.txt, etc.) estén en la raíz del proyecto para que la carga inicial sea exitosa.

2. Ejecución Directa
Si no desea compilar el código manualmente, puede ejecutar el archivo pre-compilado:

Navegue a la carpeta dist/.

Ejecute el archivo Avance_Curricular.jar (requiere Java Runtime instalado).

Documentación Técnica (SIA-O3)
Este proyecto cuenta con documentación técnica completa generada mediante Javadoc. Para revisar la arquitectura de clases, métodos y manejo de excepciones:

Diríjase a la carpeta dist/javadoc/.

Abra el archivo index.html en su navegador web.

Allí podrá navegar por la lógica de negocio de cada componente del sistema.

Funcionalidades Principales
Interfaz Dual: Selección entre modo Consola o Ventanas (GUI) al iniciar.

Gestión Académica: CRUD completo de Alumnos y Profesores.

Métricas (KPI): Análisis de progreso curricular (SIA-9) y rendimiento promedio por carrera.

Robustez: Manejo de excepciones personalizadas (AtributoInvalidoException y EntidadNoEncontradaException) para prevenir errores de datos.

Persistencia: Guardado automático de cambios al cerrar la aplicación (SIA-11).

Enlaces
Repositorio GitHub: https://github.com/Al3xiiss/Proyecto-Avance-Curricular-JAVA
Gestión de Profesores: Permite asignar asignaturas y buscar por especialidad.

Se recomienda salir usando la opción "Salir" del menú.
