# PreEntrega2_Paniati
Proyecto Coder JavaScript - Kuki's Hostel.

El codigo JS esta vinculado en la pagina reservas.html
Son 3 archivos JS.
1) Objetos del tipo HABITACION con todas las habiataciones del hostel y sus atributos. Por el momento al momento de ingresar la cantidad de huespedes, filtra las habiataciones
cuya capacidad es mayor o igual a la cantidad de huespedes. (NO divide en distintas habitaciones en esta entrega).
2) Objetos del tipo SERVICIOS con todos los servicios ofrecidos por el hostel para contratar. Solo se puede contratar 1 vez cada uno.
3) Codigo JS con la logica del simulador.

Para reservar, desde el index.html se debe presionar el boton "Ver cuartos y servicios" el cual lleva a la seccion acomodacao.html. Es esta seccion se pueden ver los cuarots con sus
caracteristicas. Desde ahi presionar el boton "Simular una reserva" el cual nos lleva a la seccion reservas.html que contiene el codigo JS.

Cuando simulamos, nos pedira el nombre, cantidad de huespedes, cantidad de dias de hospedaje. En base a eso filtra las habitaciones del array de habitaciones mostrando solo las
que puedan albergar la cantidad de huspedes ingresados o mas. Luego nos pedira q seleccionemos los servicios adicionales a contratar. Cada servicio seleccionado
se carga en el carrito de servicios.

Por Console, se pueden ver los dos carritos (HABITACIONES y SERVICIOS) y que se les va agregando. (Recuerda que en esta version solo se puede seleccionar una habitacion).
Luego el codigo recorre los carritos para calcular el costo total de hospedaje y servicios para emitirlos por alert al final del proceso.
