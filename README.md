Cumplimiento de las 3FN:
Primera forma normal (1FN): Todos los atributos de las tablas contienen valores “atómicos” y no hay grupos repetitivos, asegurando que cada columna contiene un solo valor por fila.
                            Por ejemplo, en la entidad Persona, atributos como nombre, apellidoP, email contienen valores únicos y no hay grupos repetitivos como listas o múltiples valores en una sola celda.
Segunda forma normal (2FN): No hay dependencia parcial en ninguna tabla, es decir, todos los atributos no clave dependen completamente de la clave primaria, eliminando redundancias dentro de tablas que tienen claves compuestas.
                            Por ejemplo, en DetalleReserva, atributos como fechaUso, horaInicio, y precio dependen totalmente de la clave compuesta codDetalleReserva, asegurando que no haya redundancias relacionadas con dependencias parciales.
Tercera forma normal (3FN): Todos los atributos no clave son dependientes únicamente de la clave primaria y no de otros atributos no clave, eliminando dependencias transitivas y asegurando un diseño óptimo.
                            Por ejemplo, en Persona, atributos como telefono y direccion dependen directamente de la clave primaria idPersona y no de otros atributos como dni o sexo, lo que garantiza que no existan dependencias indirectas entre atributos no clave.
