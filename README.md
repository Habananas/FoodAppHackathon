# FoodAppHackathon


Para la DB:
la categoria "padre" es el usuario, cada uno tiene un ID único y también una variable true/false  por si es proveedor o no.
luego, por los usuarios que son proveedores, creamos una colección de productos . 
Los productos contienen:
- nombre
- coordenadas de producción
- ecologico/convencional
- tipo de producto (carne, verdura etc)
- cantidad de producción (kg/year)
-agua usada (l/year)
-ha usados (ha)
-electricidad usada (kwh/year)
-fertilizadores (si/no)
- ... (desarrollamos luego)

a partir de esto hacemos una suma ponderada (cuales factores nos parecen más importantes y cuales menos) y lo visualizamos en la app (podríamos pensar en crear un motor que nos desarrolla un SCORE (tipo de 0-10 de sostenabilidad), see FoodE app: https://foode.eu
