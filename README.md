# Prueba Práctica Avanzada - Oracle SQL

**Institución:** Universidad Técnica de Ambato  
**Facultad:** Ingeniería en Sistemas  
**Asignatura:** Bases de Datos  
**Estudiante:** Barragán García Fernando Danilo  
**Nivel:** 4to Software  

---

## Escenario Asignado

**Tema:** Aeropuerto Internacional  
**Integridad:** CASCADE  

Según la distribución de escenarios de la prueba, al estudiante **Barragán García Fernando Danilo** le corresponde el escenario **Aeropuerto Internacional** con integridad **CASCADE**. :contentReference[oaicite:0]{index=0}

---

## Tablas utilizadas

El escenario se desarrolló con las siguientes tablas:

- AEROLINEA
- PASAJERO
- VUELO
- BOLETO
- EQUIPAJE

---

## Desarrollo del Examen

Este repositorio contiene la resolución completa de la prueba práctica de Oracle SQL, cumpliendo con los puntos solicitados.

### DDL — Modelado y creación de tablas

Se realizó el modelado lógico del escenario **Aeropuerto Internacional** y se crearon las tablas correspondientes mediante sentencias `CREATE TABLE`.

En esta parte se aplicaron restricciones como:

- `PRIMARY KEY`
- `FOREIGN KEY`
- `UNIQUE`
- `NOT NULL`
- `CHECK`
- `ON DELETE CASCADE`

La regla `ON DELETE CASCADE` se aplicó para mantener la integridad referencial entre las tablas relacionadas.

---

### DML e Integridad

Se insertaron registros válidos en las tablas:

- AEROLINEA
- PASAJERO
- VUELO
- BOLETO
- EQUIPAJE

También se provocó el error `ORA-02291`, insertando un registro con una clave foránea inexistente. Esto permitió demostrar el funcionamiento de la integridad referencial en Oracle SQL.

Además, se realizó un `UPDATE` seguro utilizando la condición `WHERE` para evitar modificar todos los registros de una tabla.

---

### Consultas SQL

Se desarrollaron consultas SQL utilizando los operadores y funciones solicitadas:

- `IN`
- `LIKE`
- `BETWEEN`
- `MAX`
- `JOIN`

Estas consultas permiten filtrar, relacionar y analizar la información registrada en la base de datos del aeropuerto.

---

### Análisis Profesional

Se incluyó una explicación breve sobre temas importantes de bases de datos:

- Atomicidad
- Riesgo de usar `DELETE` sin `WHERE`
- Funcionamiento de `ON DELETE CASCADE`

Estos puntos permiten comprender la importancia de proteger la información y mantener la coherencia de la base de datos.

---

## Contenido del Repositorio

```text
/scripts
Archivos .sql con el código de creación de tablas, inserciones, actualizaciones, eliminaciones y consultas.

/evidencias_manuales
Fotografías del desarrollo realizado a mano durante la clase.

/capturas_oracle
Capturas de pantalla de la ejecución de los comandos SQL y los resultados obtenidos en Oracle.
