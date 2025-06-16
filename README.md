# Examen_IntroduccionAbackend

1ERA FORMA DE NORMALIZACION:
la tabla ua se cuenta normalizada en la 1era forma, la tabla presenta valores atomicos, organizados, sin redundancias y con el mismo tipo de dato.

2DA FORMA DE NORMALIZACION:
libros (ISBN,titulo,autor,fecha_publicacion,editorial,ategoria,precio,stock ) 
cliente (id_cliente,correo_cliente,telefono_cliente)
pedido(ISBN, id_cliente , metodo_pago , monto)

3ERA FORMA DE NORMALIZACION:
PROPUESTA FINAL.
En esta forma se eliminaron dependencias transitivas generando una llave principal ISBN.
Y QUEDARIA DE LA SIGUIENTE FORMA.

libros (ISBN|titulo|autor|fecha_publicacion|editorial|categoria|precio|stock ) 
cliente (id_cliente|correo_cliente|telefono_cliente )
pedido(ISBN| id_cliente | metodo_pago |monto )
