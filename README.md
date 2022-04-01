# Comando Update Oracle
#### Actualizar registros de una tabla o modificar datos dentro de una tabla;

```sql
select * from articulos;
```
 | CODIGO            | NOMBRE           |  DESCRIPCION   |   PRECIO   |
 | ------------------|:----------------:|---------------:|-----------:|
 | 1            | impresora           |  Epson Stylus C45   |   400.80   |
 | 2            | impresora           |  Epson Stylus C85   |   500   |
 | 3            | monitor           |  Samsung 14   |   800   |
 | 4            | teclado           |  ingles Biswal   |   100   |
 | 8            | Computadora           |  Dell   |   2000   |
 
 > UPDATE
 ```sql
 update articulos set nombre = 'impresora' where codigo = '8';
 ```
 ```sql
select * from articulos;
```
 | CODIGO            | NOMBRE           |  DESCRIPCION   |   PRECIO   |
 | ------------------|:----------------:|---------------:|-----------:|
 | 1            | impresora           |  Epson Stylus C45   |   400.80   |
 | 2            | impresora           |  Epson Stylus C85   |   500   |
 | 3            | monitor           |  Samsung 14   |   800   |
 | 4            | teclado           |  ingles Biswal   |   100   |
 | 8            | impresora           |  Dell   |   2000   |
 
 ___
 
 > UPDATE DOS CAMPOS
  ```sql
 update articulos set nombre = 'impresora', precio = 500 where codigo = '3';
 ```
 ```sql
select * from articulos;
```

 | CODIGO            | NOMBRE           |  DESCRIPCION   |   PRECIO   |
 | ------------------|:----------------:|---------------:|-----------:|
 | 1            | impresora           |  Epson Stylus C45   |   400.80   |
 | 2            | impresora           |  Epson Stylus C85   |   500   |
 | 3            | impresora           |  Samsung 14   |   500   |
 | 4            | teclado           |  ingles Biswal   |   100   |
 | 8            | impresora           |  Dell   |   2000   |
 
 
 
