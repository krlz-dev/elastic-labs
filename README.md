# elastic-labs
Tomando un curso de Platzi, aprendo de elastic search

- PUT localhost:9200/usuarios/_doc/rick // puede ademas actualizar, pero por version
- POST localhost:9200/usuarios/_doc/rick
- GET localhost:9200/usuarios/_search
- GET localhost:9200/usuarios/_search
- GET localhost:9200/usuarios/_doc/rick // por doc
- GET localhost:9200/usuarios/_source/rick //POR FUENTE
- GET localhost:9200/usuarios/_mapping // un mapeo de los datos requiere mas explicacion

- POST localhost:9200/usuarios/_update/rick // actualiza, se debe poner la actualizacion dentro de {"doc":{....}}
- DELETE localhost:9200/usuarios_otro // delete sirve para borrar indices o documentos
