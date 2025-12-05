# Casos de prueba RJN PIDAWE

## Registro de usuario
- Registro correcto con email válido y contraseña segura.
- Registro con email duplicado → muestra error.
- Registro sin contraseña → bloquea envío.
- Registro con formato de email inválido → alerta de validación.

---

## Inicio de sesión
- Login correcto con credenciales válidas.
- Login con contraseña incorrecta → mensaje de error.
- Login con usuario inexistente → alerta.
- Logout → cierra sesión y redirige a pantalla de inicio.

---

## Agenda
- Crear clase con fecha y hora → se guarda correctamente.
- Editar clase → se actualiza en la base de datos.
- Eliminar clase sin confirmación → error de validación.
- Ver listado de clases → muestra todas las clases del usuario.

---

## Chat
- Enviar mensaje → aparece en tiempo real.
- Mensaje vacío → muestra alerta.
- Recepción de mensaje → se muestra en la conversación.
- Intento de enviar mensaje sin conexión → alerta de red.

---

## Reputación
- Calificar profesor → se guarda en perfil.
- Calificación sin comentario → bloquea envío.
- Promedio de calificaciones → se actualiza correctamente.
- Intento de calificar dos veces al mismo profesor → error.

---

## Perfil de usuario
- Editar datos personales → se guardan correctamente.
- Subir imagen de perfil con formato inválido → error.
- Cambiar contraseña → requiere validación de contraseña actual.
- Intento de guardar perfil sin campos obligatorios → alerta.

---

## Seguridad
- Acceso a rutas protegidas solo con sesión iniciada.
- Intento de acceso sin login → redirección a pantalla de inicio.
- Tokens de sesión expiran correctamente.
- Intento de modificar datos sin permisos → error 403.

---

## Rendimiento
- Carga de página principal < 2 segundos en escritorio.
- Carga de chat < 1 segundo en red estable.
- Simulación de carga con 100 usuarios → verificar escalabilidad.
