# Sistema de Control de Parqueo Privado - Proyecto Final

# Descripción del Proyecto
Este software de escritorio, desarrollado en C#, tiene como objetivo principal gestionar el control y cobro de un parqueo privado. El sistema aplica conceptos avanzados de Programación Orientada a Objetos (POO), diseño de bases de datos normalizadas y una arquitectura de software N-capas

# Funcionalidades Principales:

* Generación de Tickets: Creación de tickets con códigos únicos, registrando placa, fecha y hora de entrada.
* Gestión de Cobros: Cálculo automático del monto a pagar según el tiempo de estadía y tasas configurables en la base de datos.
* Módulo de Seguridad: Control de acceso mediante login con contraseñas encriptadas y gestión de usuarios (CRUD).
* Reportes: Generación de informes de tickets cobrados filtrados por rangos de fecha.

# Arquitectura y Tecnologías

El proyecto se fundamenta en una Arquitectura N-Capas para garantizar la independencia y segmentación de roles:

* WinUI (Capa de Presentación): Interfaz gráfica desarrollada en Visual Studio, enfocada en ser atractiva e intuitiva.
* BLL (Capa de Lógica de Negocio): Procesa la lógica de cálculo de cobros y validaciones de datos
* DAL (Capa de Acceso a Datos): Gestiona la persistencia de información en la base de datos.

* Stack de tecnologías : C#, MySQL

# Metodología de Desarrollo

* Sprint 1: Base de Datos y Configuración Inicial de Arquitectura.
* Sprint 2: Módulo de Seguridad, Usuarios y Encriptación.
* Sprint 3: Operaciones Core (Generación de Tickets).
* Sprint 4: Módulo de Cobros e Interfaz Principal.
* Sprint 5: Reportes, Validaciones Finales y Documentación.



  



