# Dashboard de Gestión de Licitaciones

## Descripción
Aplicación web interna desarrollada con **FastAPI y React** para centralizar la gestión de licitaciones de la empresa. Permite crear, modificar y consultar licitaciones, visualizar fechas clave en un calendario, recibir alertas automáticas de plazos próximos y gestionar accesos mediante roles de usuario. La base de datos está centralizada para uso multiusuario.

## Tecnologías utilizadas
- Backend: FastAPI  
- Frontend: React  
- Base de datos: SQLite centralizada  
- Control de accesos: Gestión de roles de usuario  

## Capturas de pantalla

### Inicio de sesión
![IniciarSesión](images/ini.png)  
Panel principal para iniciar sesión con cuenta de usuario.

### Vista general del dashboard
![Dashboard](images/dashboard.png)  
Panel principal con lista de licitaciones, principales datos y estado. Además incluye diferentes filtros para poder listar.

### Vista expandida de licitación
![VistaExpandida](images/expand.png)  
Vista expandida de una licitación donde se pueden observar todos los datos de la misma. Además permite cumplimentar todos los datos de las ofertas (Informe resumen, Costes y Detalle costes Indirectos) y posteriormente exportarlo en una plantilla propia de la empresa en Excel.

### Calendario de licitaciones
![Calendario](images/calendario.png)  
Visualización de todas las licitaciones con fechas clave y alertas automáticas.

## Beneficios
- Mejora la organización y seguimiento de licitaciones  
- Elimina procesos manuales basados en Excel  
- Notificaciones automáticas de plazos  
- Control multiusuario con roles de acceso  

