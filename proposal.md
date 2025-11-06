# Propuesta TP DSW

## Grupo
### Integrantes
* 51236 - JUAN BENNAZAR, León
* 51729 - MORETTI, Lucca

### Repositorios
* [frontend app](https://github.com/leonbennazar/tp-dsw-frontend)
* [backend app](https://github.com/leonbennazar/tp-dsw-backend)

## Tema Mi Turno FC
### Descripción

Mi Turno FC es un sistema para gestionar reservas de canchas de fútbol. Solamente tenés que registrar un usuario con tu mail para empezar a reservar. Elegís la fecha, la hora y la cancha que más te guste [y pagar la seña para confirmar la reserva]. Nosotros te recordamos cuando te toca jugar!

### Modelo
[imagen del modelo](https://drive.google.com/file/d/1kphVH6JrEQCR6wbfDhli8j-YjjmINlYh/view?usp=drivesdk)
## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tamaño Cancha<br>2. CRUD Material Cancha|
|CRUD dependiente|1. CRUD Cancha {depende de} CRUD Tamaño Cancha y Material Cancha|
|Listado<br>+<br>detalle| 1. Listado de Turnos libres para una Cancha filtrado por fecha => detalle Crud Reserva|
|CUU/Epic|1. Reservar una cancha.|

Adicionales para Aprobación Directa:
|Req|Detalle|
|:-|:-|
|CRUD |1. <br>2. <br>3. <br>4. <br>5.Pago con MP <br>6.<br>7. |
|CUU/Epic|1. <br>2. <br>3. |

### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.
