[`Introducción a Bases de Datos`](../../Readme.md) > [`Sesión 01`](../Readme.md) > `Reto 03`
	
## Ordenamientos y Límites

### OBJETIVO 

- Escribir consultas que permitan responder a algunas preguntas mediante ordenamientos y límites.

#### REQUISITOS 

1. MySQL Workbench instalado.

#### DESARROLLO

Usando la base de datos `tienda`, escribe una consulta que permita obtener el top 5 de puestos por salarios.

<details><summary>Solución</summary>
<p>

Para contestar a esta pregunta, basta con ordenar las calificaciones del alumno en orden descendente y limitar el número de registros a 5.

   ```sql
   SELECT salario
   FROM tienda
   ORDER BY salario DESC
   LIMIT 5;
   ```
</p>
</details> 
