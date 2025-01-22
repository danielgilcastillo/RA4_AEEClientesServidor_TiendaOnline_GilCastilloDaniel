Abrir apache con xamp, y acceder a la pagina del login.
El cliente HTML almacenará la información de la tienda en el localStorage después de la autenticación, evitando consultas constantes al servidor. La autenticación se realizará a
través de un sistema de login que verificará las credenciales de usuario y, una vez validado, enviará la información de la tienda para ser almacenada localmente. A partir de ahí, el
cliente gestionará las páginas (productos, categorías, carrito de compras) utilizando solo los datos almacenados en el navegador, mientras que el servidor se encargará de la validación
de los precios del carrito y la seguridad con tokens.

