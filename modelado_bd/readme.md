# Modelado Lógico de Base de Datos – API REST Tienda Virtual

Este directorio contiene los artefactos relacionados con el diseño lógico de la base de datos utilizada en el desarrollo de una API REST para la Tienda Virtual de renta y venta de videos por streamer. 
La base de datos está diseñada para ejecutarse en **Microsoft SQL Server 2022**.

## Estructura del directorio

- diagrama-logico.png: Imagen del diagrama de modelado lógico que representa las entidades, atributos y relaciones.
- diccionario-de-datos.xlsx: Documento que describe cada tabla, campo, tipo de dato, restricciones y relaciones.
- script-creacion-bd.sql: Script SQL para crear la base de datos y sus objetos (tablas, claves primarias/foráneas, índices, etc.) en SQL Server 2022.

## Propósito

Este modelo lógico sirve como base estructural para el backend de la aplicación, facilitando:

- La comprensión del diseño de datos por parte del equipo de desarrollo.
- La generación de modelos ORM en Django
- La validación de integridad referencial y normalización de datos.

## Requisitos

- **Motor de base de datos**: Microsoft SQL Server 2022
- **Herramientas recomendadas**:
  - SQL Server Management Studio (SSMS)
  - Visual Studio Code o PyCharm para codificación
  - Diagramador como dbdiagram.io, Draw.io o ERD Plus, o ER-Studio (versión nativa del archivo)

## Uso

1. Abrir el archivo "bd_rentapelicula.sql" en SSMS.
2. Ejecutar el script para crear la base de datos y sus objetos.
3. Consultar el diagrama lógico y el diccionario de datos para entender la estructura.
4. Integrar con el backend de la API utilizando Django ORM y el conector adecuado para SQL Server.

## Notas

- El modelo está normalizado hasta la tercera forma normal (3FN).
- Las convenciones de nombres siguen el estándar snake_case.
- Las claves primarias están definidas explícitamente en cada tabla.
- Las relaciones están documentadas en el diagrama como en el diccionario.

## 📄 Licencia

Este proyecto se distribuye bajo la licencia Apache Common 2.0. Consulta el archivo "LICENSE" para más detalles.

---



