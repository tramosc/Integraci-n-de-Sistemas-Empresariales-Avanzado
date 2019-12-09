Laboratorio 05
Desarrollo del laboratorio:
2. Creación de Cotización a cliente
2.1. Entramos al menú Cotización y empezamos la creación de una nueva cotización. Podemos apreciar que están los productos creados en el laboratorio anterior.

![Lab_05_1](./Capturas/2_1_3.JPG)

2.2. Seleccionemos manzanas verdes e intentemos vender 100 unidades. En caso no tengamos stock suficiente, el sistema nos dará una alerta al respecto. Esto es muy útil para la persona que realiza la cotización.

![Lab_05_2](./Capturas/2_2_3.JPG)

2.3. A pesar de la falta de stock, crearemos la Cotización con al menos dos productos.

![Lab_05_3](./Capturas/2_3_3.JPG)

2.6. Demos click en Guardar y luego en Validar. Al validar la cotización, aparecerán nuevas opciones, como Enviar por Email, Imprimir o incluso, Confirmar Venta (recordar que esta es solamente una cotización para un cliente interesado en comprar)

![Lab_05_4](./Capturas/2_6_4.JPG)

2.8. Ahora que hemos ingresado un correo válido para el cliente (para las pruebas, ingrese un correo personal, usaremos el correo de TECSUP más adelante), nos aparecerá un asistente de redacción del correo. Cada vez que intentamos enviar un correo de cierto documento, Odoo precarga una plantilla con texto por defecto, además de adjuntar el documento en formato PDF. Esto permite flexibilidad en el tipo de correo a enviar según el cliente deseado, e inclusive, añadir más adjuntos, digamos, un contrato o una foto del producto.

![Lab_05_5](./Capturas/2_8_5.JPG)

La cotización pasa ahora a ser un Presupuesto o Pedido de Venta. 

![Lab_05_6](./Capturas/2_8_1-5.JPG)


Podemos ver así mismo, las nuevas opciones, como Entrega y Crear Factura

![Lab_05_7](./Capturas/2_8_2-5.JPG)


3. Entrega de productos de una Cotización
Capturas

![Lab_05_8](./Capturas/3_1_6.JPG)
![Lab_05_9](./Capturas/3_1_2_6.JPG)
![Lab_05_9_1](./Capturas/3_1_3_6.JPG)
![Lab_05_9_2](./Capturas/3_2_6.JPG)
![Lab_05_9_3](./Capturas/3_3_7.JPG)
![Lab_05_9_4](./Capturas/3_3_2_7.JPG)
![Lab_05_9_5](./Capturas/3_4_7.JPG)

4. Facturación y registro de pago de una Cotización
4.4. Demos click en Validar. Al igual que con otros documentos, aparecerán nuevas opciones en esta factura. Podremos incluso crear un correo con el adjunto de la factura generada para pagar.

![Lab_05_10](./Capturas/4_4.JPG)


4.5. Al haber validado esta factura, se afectará al estado del cliente. Si buscamos en el menú Clientes, veremos que nuestro contacto ahora tiene un indicador de cuantas ventas tiene.

![Lab_05_11](./Capturas/4_5_10.JPG)


 Al entrar al contacto, vemos el total facturado hasta el momento a dicho cliente. 

![Lab_05_12](./Capturas/4_5_2_10.JPG)


E incluso, al hacer click en Imprimir, tendremos un reporte llamado Pagos pendientes, que muestra todo el detalle de deuda del cliente.
4.6. Volvamos a la factura. Ahora demos click en Registrar Pago. Por defecto, se completa el monto para toda la factura y darla por cancelada.

![Lab_05_13](./Capturas/4_6_10.JPG)


En caso, nos vayan a hacer un pago parcial, ingresamos la cantidad abonada. El sistema se dará cuenta de esto y nos preguntará si debe mantener aún abierta la factura o pagarla totalmente. La dejaremos abierta y validaremos el pago.
Si vemos el detalle de la factura, en la parte de los totales veremos registrado el pago y el saldo pendiente de pago. 
Esto también podremos observarlo en el módulo de Facturación, al ver el comprobante en estado abierto y cuál es el saldo pendiente.


![Lab_05_14](./Capturas/4_6_2_11.JPG)

5. Configuración de envío de Correos
5.2. De click en Editar para modificar el servidor de correo. Ingresaremos la siguiente data. Reemplace el correo por el suyo propio de Tecsup y coloque la contraseña que utiliza para iniciar sesión.

![Lab_05_15](./Capturas/5_2_12.JPG)

5.3. Vamos a la URL https://myaccount.google.com/security y deslicemos la pantalla hasta la opción de Acceso de aplicaciones poco seguras. Demos click en Activar acceso.
Ahora, solamente debemos permitir el acceso a estas aplicaciones

![Lab_05_16](./Capturas/5_3_12.JPG)

Una vez hecho esto, volvamos a Odoo y probemos la conexión. En caso de ser exitoso, demos click en Guardar.

![Lab_05_17](./Capturas/5_3_2_12.JPG)


6. Cambio de secuencia.
6.4. Guarde los cambios de la secuencia y cree otra Cotización. Verá el cambio rápidamente reflejado. Así podemos modificar todas las secuencias del sistema, no solamente las de ventas.

![Lab_05_18](./Capturas/6_4_14.JPG)
![Lab_05_18_2](./Capturas/6_4_2_14.JPG)

7. Listas de precios
7.3. Proceda a crear otra cotización y juegue con el cambio de Lista de Precio (este campo no estaba activado antes)


![Lab_05_19](./Capturas/7_3_pag15.PNG)


8. Portal del cliente
8.3. Le diremos al sistema que este cliente tiene acceso. De click en el check al costado del correo electrónico para poder marcarlo y activarlo.

![Lab_05_20](./Capturas/8_3_pag17.PNG)


