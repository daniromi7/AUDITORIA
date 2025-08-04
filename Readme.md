# Mini-Reporte
### Vulnerabilidad
#### 1.INJECTION SQL
#### 2.Descripcion
Esta vulnerabilidad permite a un atacante ejecutar código malicioso en una base de datos a través de entradas de usuario no validadas en una aplicación web, potencialmente robando o modificando datos sensibles

#### 3.Table / csv
| Vulnerabilidad | Severidad | CVSS | Impacto |
| -------------- | --------- | ---- | ------ |
| Inyeccion SQL | Crítica | 9.8 | Alto |
| XSS Reflejado | Alta | 7.5 | Medio  |
#### 4.Bloque poc
SQL
Select * from user where id =`1`or ´1´=1.

#### 5.Enlace
**Evidencia** :
![xss Pc](https://www.concienciaeco.com/wp-content/uploads/2015/04/4236243003_7382465301_b.jpg)gti 