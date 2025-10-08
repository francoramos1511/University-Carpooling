# Requerimientos Funcionales

| Funcionalidad | Interesado | Descripcion |
| - | - | - |
| **Registro de usuario** | Estudiantes | Permitir el registro mediante correo electrónico, nombre de usuario y contraseña. El usuario podrá elegir su perfil (conductor, pasajero o ambos). No se podrá modificar el email una vez registrado. |
| **Login de usuario** | Todos los usuarios | Permitir iniciar sesión con nombre de usuario y contraseña o con una cuenta de Google. Debe incluir la opción de recuperación de contraseña. |
| **Logout de usuario** | Todos los usuarios | Permitir cerrar sesión actual. |
| **Editar usuario** | Todos los usuarios | Permitir modificar los datos registrados, excepto el correo electrónico. |
| **Gestión de perfiles de usuario** | Todos los usuarios | Permitir seleccionar el perfil con el que se va a interactuar con el sistema (conductor, pasajero, administrador). Los administradores solo pueden ser dados de alta por otro administrador. |
| **Publicar viaje** | Conductor | Permitir publicar un viaje indicando origen, destino, ruta principal, día, horario, costo compartido sugerido y cantidad de lugares disponibles. |
| **Editar o cancelar viaje** | Conductor | Permitir la modificación o cancelación de viajes previamente publicados. Si el viaje es cancelado, deben notificarse los pasajeros con reserva. |
| **Evaluar pasajeros** | Conductor | Permitir al conductor evaluar a los pasajeros del viaje. |
| **Buscar viajes** | Pasajero | Permitir la búsqueda de viajes según zona, día y hora. Debe mostrar resultados relevantes con la información del conductor y los lugares disponibles. |
| **Reservar lugar en un viaje** | Pasajero | Permitir al pasajero reservar un lugar en un viaje publicado. El sistema debe validar la disponibilidad de lugares y confirmar la reserva. |
| **Evaluar conductor** | Pasajero | Permitir que el pasajero evalúe al conductor después de completar un viaje. |
| **Gestión de usuarios** | Administrador | Permitir al administrador dar de baja usuarios con mala reputación o incumplimientos, así como crear nuevos administradores. |
| **Gestión de evaluaciones** | Administrador | Permitir revisar y arbitrar discrepancias o conflictos en las evaluaciones entre pasajeros y conductores. |
| **Gestión de reportes** | Administrador | Permitir la administración de reportes realizados por los usuarios sobre comportamientos inapropiados o problemas detectados. |
| **Notificaciones por cancelación** | Pasajero / Conductor | Notificar a los pasajeros cuando un conductor cancele un viaje en el que tenían una reserva. |
| **Notificaciones por demora** | Pasajero / Conductor | Notificar a los pasajeros si el conductor está atrasado o demorado. |
| **Recordatorio de viaje próximo** | Pasajero / Conductor | Enviar una notificación a los usuarios 15 minutos antes del inicio del viaje programado. |

# Requerimientos no funcionales

| Requerimiento | Interesado |  Detalle |
| - | - | - |
| **Usabilidad** | Todos los usuarios | La aplicación debe ser fácil de usar para jóvenes entre 18 y 30 años, con una interfaz móvil intuitiva que siga las guías de diseño de iOS y Android. |
| **Rendimiento** | Todos los usuarios | La applicacion debe ser capaz de responder en no mas de 2 segundos. |
| **Seguridad** | Todos los usuarios | La aplicacion debe mantener datos sensibles cifrados. |
| **Fiabilidad** | Todos los usuarios | La aplicación debe ser capaz de funcionar normalemte en epocas de examenes o parciales donde la demanda puede aumentar. |
| **Disponibilidad** | Todos los usuarios | Disponibilidad continua con mantenimiento planificado fuera de horario pico. |
