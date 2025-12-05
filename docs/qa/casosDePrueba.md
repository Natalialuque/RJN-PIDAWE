# Casos de prueba RJN PIDAWE

## Registro de usuario
- Registro correcto con email válido.
- Registro con email duplicado → muestra error.
- Registro sin contraseña → bloquea envío.

## Agenda
- Crear clase con fecha y hora → se guarda correctamente.
- Editar clase → se actualiza en la base de datos.
- Eliminar clase sin confirmación → error de validación.

## Chat
- Enviar mensaje → aparece en tiempo real.
- Mensaje vacío → muestra alerta.

## Reputación
- Calificar profesor → se guarda en perfil.
- Calificación sin comentario → bloquea envío.
