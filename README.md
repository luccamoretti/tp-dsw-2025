# REGLAS DE NEGOCIO
* Un usuario puede ser Admin o Cliente
* De la cancha me interesa saber el ID autoincremental, un numero que represente la ubicación en el lugar (cancha 1, cancha 2...) nombre y el tipo de turno (En punto o Y media)
* Una cancha esta compuesta de solo una clase de material. El mismo me indica el piso, si es techada y un nombre. Me interesa conocer el ID autoincremental. Tambien esta compuesta de una sola clase de tamaño que indique ancho, largo, una y es identificado por el tamaño del equipo recomendado (f5, f6, f7...)
* A la empresa no le interesa llevar un historial de cambio de material o tamaño de una misma cancha
* Los Turnos ya estan cargados y me interesa su ID y hora de inicio y fin
* La reserva depende del turno. Me interesa saber su id, estado y fecha. Un mismo turno puede tener muchas reservas a lo largo del tiempo.
*Una cancha puede tener ninguna o muchas reservas, pero una reserva pertenece a una única cancha
