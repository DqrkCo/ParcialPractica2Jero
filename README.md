# Parcial2_PracticaJero
Gestión de tarjetas (JavaFX + MySQL)

Autor: [tu nombre] - Curso: [materia y grupo]

Es una app de escritorio hecha en Java con JavaFX y MySQL para crear y consultar tarjetas de débito y crédito de un titular.

HISTORIA DE USUARIO (HU-01)

Como analista de crédito, quiero asignar un estado a una tarjeta para controlar si puede ser utilizada.

Criterios de aceptación:

La tarjeta puede estar Activa, Bloqueada o Cancelada.
El estado se guarda en la base de datos.
El estado se ve en el formulario principal.
El estado es obligatorio al crear una tarjeta.
No se puede guardar una tarjeta sin un estado válido.

ESTIMACIÓN

5 puntos de historia, más o menos 10 horas de trabajo.

TAREAS TÉCNICAS

Crear el enum EstadoTarjeta (0,5 h)
Cambiar el estado de Tarjeta, Debito y Credito para que use el enum y no acepte nulos (1 h)
Poner la columna estado como ENUM NOT NULL y hacer el script de migración (1 h)
Guardar y leer el estado en DAOTarjeta (1,5 h)
Agregar el combo de estado en Crear y mostrar el estado en Consultar (2 h)
Hacer las pruebas unitarias y de integración (2 h)
Hacer los diagramas UML en StarUML (1 h)
Escribir este README (0,5 h)
