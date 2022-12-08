# SD_Bigtable
Proyecto - Seminario Sistemas Distribuidos 2023-1

Usar Bigtable para un website de e-commerce que busca recomendar productos a los usuarios basándonos en sus búsquedas e historial de compras. 
Para esto se implementarán las siguientes tablas:

UserHistory: Esta tabla guardará información acerca de la sesión de los usuarios, incluyendo que productos vieron, cuales agregaron a su carrito y los que compraron.

UserPersonalization: La tabla almacenará productos recomendados para cada usuario, los cuales serán generados dinámicamente usando ML. De igual forma puede almacenar preferencias declaradas por el usuario desde una lista de deseos o ítems guardados.

ProductRecommendation: Proveerá recomendaciones de productos basándose en un producto original. (Recomendaciones respecto a un ítem ya adquirido).
