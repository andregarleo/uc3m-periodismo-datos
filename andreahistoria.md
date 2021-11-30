## Mi historia de periodismo de datos 

### Visualización población canaria por edad (2019)


La base de datos utilizada para la creación del proyecto fue **Población por sexo, islas y edad (grupos quinquenales)**, cuya fuente es el **INE** (*Instituto Nacional de Estadística*).

En él, se condensaban los datos relativos a esos aspectos, con **todas las islas españolas**, división por sexos y edad. Sin embargo, para realizar la infografía solo se tuvieron en cuenta los datos referidos a las **Islas Canarias**, ignorando la variante del sexo y utilizando únicamente el total de población por cada rango de edad.

Una vez escogida la **base de datos** y descargada del INE en **formato CSV** se procedió al vertido de los mismo en **Open Refine**. Allí, mediante un proceso de limpieza, se descartaron los datos que eran innecesarios para realizar nuestra visualización. Se utilizaron, para ello, herramientas como el **filtro de texto** o, a un nivel más general, la **eliminación de columnas y celdas** que no eran necesarias para completar el proceso. 

Una vez terminada esta fase se procedió a la creación de la visualización en **DataWrapper**, momento en el que se arreglaron algunos aspectos. Una vez se hubo comprobado que los datos eran correctos, se avanzó hasta el apartado de *“Visualize”*, momento en el que se escoge el formato y demás aspectos de nuestro proyecto. 

Tras probar diferentes formatos, se optó por el de **barras**, debido a la idoneidad con la que presenta los datos escogidos, pues se ven, de manera sencilla y esquemática las cifras aportadas. Tras añadir el **título** y una breve **descripción**, se procedió a la elección del **color**, en este caso de un tono salmón, cuyo código en la aplicación es: “#ff8658”.

Finalmente, después de haber dado por terminado el proceso de producción, se llevó a cabo su **publicación**, dando como resultado final la visualización presentada. 

Por último, con el fin de publicar la inografía en **Github**, se accedió desde la **terminal** a este repositorio, realizando en **nano** el presente texto y añadiendo la visualización.
                   
 ![ZNSXs-poblaci-n-de-canarias-por-edad](https://user-images.githubusercontent.com/90326392/143773639-1a32e9e0-6219-4194-a8d8-7f82b76b9e56.png)
