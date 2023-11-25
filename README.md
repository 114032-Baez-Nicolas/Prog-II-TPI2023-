# Prog-II-TPI2023-
Automotor Prestige (TPI)

En caso de un error en el alta de una factura, ir a la base de datos y en el apartado de inserts modificar lo siguiente:

insert into FACTURAS(fecha,id_forma_pago,id_vendedor,id_cliente,total) values('12/01/2023',1,18,2,27000.75)

insert into DETALLES_FACTURAS(id_detalle,cantidad,id_factura,id_producto) values(25,1,4,3) --fijarse en nro de facutura (id_factura) de la tabla facturas y modificar el detalle con dicho numero en el campo id_factura 
