# TP1

Diseño del Formulario:
El formulario tiene un diseño simple y fácil de usar. Usamos colores claros, bordes redondeados y un diseño centrado. Al hacer clic en los campos, se resaltan con un borde de color.

Validaciones y Funcionamiento:
Se hicieron validaciones con JavaScript para asegurar que los datos sean correctos:

Nombre: Mínimo 3 caracteres.

Email: Debe tener un formato válido.

Contraseña: Mínimo 8 caracteres, con al menos un número y una letra.

Confirmar contraseña: Debe coincidir con la contraseña ingresada.

Si hay errores, se muestra un mensaje rojo. Si todo está bien, aparece un mensaje verde confirmando el envío.

Dificultades y Soluciones:
Un problema fue que el formulario se enviaba aunque hubiera errores. Lo solucionamos usando event.preventDefault(). Tambien se nos complicó en un momento cuando queriamos mandar el mensaje final, ya que al llenar de manera correcta el formulario no enviaba el mensaje que se habia mandado correctamente, lo solucionamos poniendo haciendo return true o false en las funciones de validacion.

Mejoras posibles:
Si hubiera más tiempo, se podría agregar:

Animaciones para los mensajes.

Iconos para indicar si un dato es correcto o incorrecto.

Validaciones extra, como caracteres especiales en la contraseña.

Mas campos a llenar para registrarse
