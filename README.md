# Caso: VENTAS

Le contratan para hacer una base de datos que permita apoyar la gestión de un
Sistema de ventas. La empresa necesita llevar un control de sus proveedores,
empleados, clientes, productos y sus ventas. Un proveedor tiene un RUC, Razón social,
dirección, teléfono y pagina web. Un cliente está clasificado en: cliente naturales y
jurídicas. Ambos casos comparten atributos como código, dirección y correo. Un
empleado tiene su código, nombres, fecha de contratación y además un empleado
puede cumplir el rol de supervisor de otros empleados. Un producto tiene un código
único, descripción, precio actual, stock. Además, se organizan en categorías y cada
producto va solo en una categoría. Una categoría tiene código, nombre. Un proveedor
puede abastecer varios productos a la tienda y un producto puede ser abastecido por
muchos proveedores. Por razones de contabilidad, se debe registrar la información de
cada venta con un número, fecha, datos del cliente, datos del empleado. Además, se
debe guardar el precio al momento de la venta la cantidad vendida.