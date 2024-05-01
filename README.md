# Proyecto CoderHouse
Comisión: 54135
Alumno: Cristian M. CARRIÓ

## Descripción del Proyecto
	"La web se centra en la venta de suministros de pintura. Ofrecemos un sistema completo para gestionar clientes, artículos y pedidos, facilitando una experiencia de compra eficiente y sin complicaciones."
 
## Tecnologías utilizadas
    asgiref 3.8.1    Django 5.0.4    sqlparse 0.5.0    tzdata 2024.1
    
## Apps   
    -Core: Pantalla principal  
    -Cliente: Muestra los clientes registrados y permite el ingreso de nuevos clientes.
    -Artículo: Muestra los artículos disponibles y permite la carga de nuevos artículos.
    -Pedido: Muestra los pedidos registrados y permite la creación de nuevos pedidos.
    
### Models
Las aplicaciones anteriores utilizan el contenido de los siguientes modelos:
    -Cliente: Almacena todos los datos correspondientes de cada cliente: nombre, apellido, DNI, dirección y ciudad.
    -Artículo: Almacena todos los datos correspondientes a cada artículo: nombre, descripción y precio.
   	-Pedido: Almacena todos los datos correspondientes a cada pedido: cliente, artículo y cantidad.
