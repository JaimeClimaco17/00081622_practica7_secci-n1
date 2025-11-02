# 00081622_practica7_secci-n1

¿Cuál es la diferencia entre autenticación y autorizacion?
Autenticacion: Es el proceso de verificar la identidad del usuario, es decir, comprobar que eres quien dices ser.

Autorizacion: Es el proceso de verificar qué puede hacer un usuario autenticado, o sea, qué permisos tiene.

En resumen:

Autenticación = Quién eres.

Autorización = Qué puedes hacer.

¿Cuál es la función del token JWT en la guía?
El JWT (JSON Web Token) es una credencial digital que se entrega al usuario una vez que se autentica correctamente (por ejemplo, al hacer login). Permitir la autorización automática en peticiones posteriores, sin tener que volver a iniciar sesión.

El JWT demuestra quién eres (autenticación) y permite que el servidor sepa si estás autorizado (autorización) sin pedir tu contraseña en cada petición.