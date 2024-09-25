# **Solución Trabajo ETL**

## **Integrantes**
- Juan Felipe Muñoz Cuartas (El falso)
- Dennis Patrick Juilland Prada (El psicópata)
- Simón Londoño Londoño (El desempleado)

---

## **1. Tipo de Fuentes de Datos**
- Base de datos: `Northwind.sql`

---

## **2. Mecanismos de Transformación**
Se aplican procesos de limpieza y transformación de datos con el objetivo de construir tablas dimensionales y una tabla de hechos que alimenten una base de datos OLAP.

---

## **3. Objetivo de Llegada de los Datos**
El objetivo final de los datos es un esquema OLAP (Online Analytical Processing) para optimizar consultas y análisis.

---

## **4. Esquema Visual del Diseño de la ETL**

![image](https://github.com/user-attachments/assets/c21221d1-a75d-44f2-a50e-1f5a7a4bbc8a)

---

## **5. Modelo Relacional Obtenido**

![image](https://github.com/user-attachments/assets/6d9aedc3-60cd-4176-93da-cad3f70b3d01)


---

## **6. Código**

### **6.1 Librerías Utilizadas**
Para ejecutar este código, se requiere instalar las siguientes librerías:
```bash
%pip install sqlalchemy
%pip install psycopg2
