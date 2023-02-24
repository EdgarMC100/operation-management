![Mind Logo](https://uploads-ssl.webflow.com/5e94eacec7d8c21e2cbbe093/616f539cc4710faaaab29c20_mind-home_Logo-06.svg)

# Mind Team Challenge

## Intrucciones
  - [ ] Contruir un Docker con las herramientas y configuraciones requeridas para montar un sitio web. (Dejar implementacion al final)
  - [ ] Configurar una base de datos (SQL, MySql, Mongo)
  - [ ] Contruir un Web API RestFul (Net Core, Node, PHP)
    * Implementar documentacion (Swagger/OpenAPI)
    * Implementar versionado del API
    * Implementar seguridad JWT
    * Implementar un Log de errores
    
  - [ ] Construir Unit Test
    * Integrar herramienta de code coverage para el avance
  - [ ] Implementar ORM si el modelo de Base de datos lo permite
  - [ ] Contruir un FrontEnd con una de las siguientes opciones (React, Angular, Vue, React Native, Android, IOS)
    * Integrar validaciones en los campos (Campos vacios o nulos)
    *Integrar notificaciones de confirmacion (Alertas al guardar, eliminar)
  - [ ] Se requiere entregar en un repositiorio git el resultado de la implementacion
  - [ ] Evitar manejo de variables fijas en el código(Configurarlas en algun archivo general y documentadas)
  
  ## **Historias (Funcionalidad)**
  
  - [ ] Inicio de sesión
  - [ ] Cerrar sesión
  - [ ] Manejo de roles
    - Super user(Se crea directo en la base de datos)
      - Este usuario puede dar de alta admins o usuarios normales
    - Admin
    - Usuario normal
    
  ## **Role Admin y superAdmin** puede hacer la siguientes tareas
  - [ ] Crud de usuarios
    - Nombre
    - Correo
    - Contraseña encriptada
  - [ ] Crud de cuentas
    - Nombre de la cuenta
    - Nombre del cliente
    - Nombre del responsable de operación
    - Consulta de equipo
  - [ ] Movimiento de personas de los equipos
    - Debe poder agregar usuarios registrados
      * Fecha de inicio
      * Fecha de fin
      * El sistema debe mantener un log de movimientos de las personas
  - [ ] Consuta log de movimientos de personas entre equipos
    - Filtro
      - Por equipo
      - Por nombre
      - Por fecha de inicio y fecha de fin
  - [ ] Consultar información detalle de los usuarios
  
  ## **Role Usuario normal**
  - [ ] Solo puede consultar su perfil
    - Nombre
    - Correo (No editable)
    - Nivel de inglés
    - Conocimientos técnicos (Campo de texto)
    - Link de CV(Google Doc) para manejar formato de arkus
    
  ## **Proceso de seguimiento**
  - [ ] Se tiene un sprint de 1 semana para realizar esta actividad
    1. Preparar código en repositorio
    2. Preparar demo de la implementación
