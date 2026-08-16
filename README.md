# DMBI-TAREA1
# Proyecto OLTP con Northwind
Módulo: MIAV1E605 - Base de Datos  
Tarea: 1.2 Diseño e Implemento un modelo de base de datos  
Fecha: Agosto 2026

## Descripción del Proyecto
Este repositorio contiene la implementación de la base de datos Northwind como proyecto OLTP (Online Transaction Processing).  
El objetivo es mostrar un modelo entidad-relación normalizado que soporte transacciones rápidas y consistentes.

## Contenido del Proyecto
- Scripts SQL generados a partir de la base de datos Northwind.
- Archivos de solución de Visual Studio (SQL Server Database Project).
- Diagrama entidad-relación con las principales tablas y relaciones.

## Tablas principales
- Customers: información de clientes.
- Orders: órdenes de compra realizadas.
- OrderDetails: detalle de cada orden.
- Products: catálogo de productos.
- Suppliers: proveedores asociados.
- Employees: empleados relacionados con las órdenes.

## Instrucciones de Ejecución
1. Abrir SQL Server Management Studio (SSMS).
2. Restaurar la base de datos Northwind desde el archivo `Northwind.bak`.
3. Abrir Visual Studio Community.
4. Importar la base de datos Northwind en un nuevo proyecto SQL Server Database Project.
5. Ejecutar los scripts para verificar la creación de tablas y relaciones.
