# REGLAS DE NEGOCIO
* Un usuario puede ser Admin o Cliente.
* De la cancha me interesa saber el ID autoincremental, un numero que represente la ubicación en el lugar (cancha 1, cancha 2...) nombre y el tipo de turno (En punto o Y media).
* Una cancha esta compuesta de solo una clase de tipo. El mismo me indica el piso, si es techada y un nombre. Me interesa conocer el ID autoincremental. Tambien esta compuesta de una sola clase de tamaño que indique ancho, largo ,capacidad por equipo y es identificado por el id.
* Se puede registrar canchas sin su tipo ni tamaño.
* A la empresa no le interesa llevar un historial de cambio de tipos o tamaños de una misma cancha.
* Los Turnos ya estan cargados y me interesa su ID y hora de inicio y fin. Los turnos de id 1 a 5 representan turnos "en punto" y los de 6 a 10 "y media".
* La reserva depende del turno. Me interesa saber su id, estado de pago y fecha. Un mismo turno puede tener muchas reservas a lo largo del tiempo.
* Una cancha puede tener ninguna o muchas reservas, pero una reserva pertenece a una única cancha.
* Si se elimina una cancha con reservas asignadas, se eliminaran también las mismas.
