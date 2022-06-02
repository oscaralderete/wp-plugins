# WordPress + WooCommerce Plugins

Un set de plugins que desarrollé y luego refactoricé especialmente para usuarios del Perú.

---

## 1. Markers On OpenstreetMap

Este es un plugin que desarollé hace unos años y que es una variación del realizado para Google Maps. Originalmente, la URL de la API de Google Maps se invocaba sin más desde un tag _script_ hasta que decidieron que tendría que funcionar obligatoriamente con un _KEY_ de usuario. Debido a que algunos usuarios de mapas no contaban con una cuenta de Google o el proceso de generar tal _KEY_ se les hacía algo complicado alguien me pidió una solución alternativa y así es como se originó este plugin.

Esta versión está refactorizada y sigue las recomendaciones de buenas prácticas de WP. Su página en el _admin zone_ usa Vue y Ajax para funcionar sin necesidad de recargar la página a cada interacción con el servidor. Un _live demo_ se encuentra en el siguiente link (buscarlo en el footer del website):

-   <a href="http://demo.oscaralderete.com/tienda1/" target="_blank">http://demo.oscaralderete.com/tienda1/</a>

PS: Hay montones de plugins de este tipo así que para diferenciarla un poco decidí darle un toque especial, hice que los colores del _marker_ puedan ser fácilmente personalizables.

---

## 2. Multiple Markers on Google Maps

Uno de los primeros plugins que escribí, inicialmente usaba un archivo XML para almacenar la data. Cuando Google Maps comenzó a requerir el _KEY_ de developer lo dejé olvidado y no fue hasta el año pasado (2021) que lo refactoricé en onda con mi anterior plugin.

Necesita el _KEY_ de usuario de Google Maps que se registra en su página en el _admin zone_. También tiene el personalizador de colores del plugin anterior. Su _live demo_ se está en el siguiente link (buscarlo en el footer del website):

-   <a href="http://demo.oscaralderete.com/tienda2/" target="_blank">http://demo.oscaralderete.com/tienda2/</a>

---

## 3. WooCommerce: Inputs para Boleta Factura

Este plugin agrega los inputs Boleta/Factura y DNI/RUC para su registro en una instalación de WooCommerce. Información que se ve en la pantalla, el _admin zone_ correspondiente y también en el _email_ del usuario.

Revisa su _live demo_ en este link (para simplificarte el _review_ hay un botón que al clicarlo elige un producto al azar y te envía al _checkout_, cool):

-   <a href="http://demo.oscaralderete.com/tienda1/" target="_blank">http://demo.oscaralderete.com/tienda1/</a>

---

## 4. WooCommerce: Autocompletador de Departamento, Provincia y Distrito

También otro plugin desarrollado hace varios años, la versión original usaba Ajax para obtener la provincia y el distrito con cada interacción, ¿pero para qué sobrecargar al servidor con minucias? Un tiempo después lo modifiqué para que use un JSON como origen de datos, lo cuál lo ha hecho extremadamente eficiente.

Encuentra su _live demo_ en este link (para simplificarte el _review_ hay un botón que al clicarlo elige un producto al azar y te envía al _checkout_, cool):

-   <a href="http://demo.oscaralderete.com/tienda2/" target="_blank">http://demo.oscaralderete.com/tienda2/</a>

---

## IMPORTANTE:

Todos estos plugins son de libre descarga, instalación y uso. Los refactoricé hace unos pocos meses a todos, si buscan entre mis otros repositorios seguramente encontrarán algunas versiones anteriores de alguno de ellos, al menos las de los mapas. Todos usan la denominación: **_WPE (Web-apps Para Emprendedores)_** que es una sub-marca que creé para brindar servicios como consultor IT y desarrollo de plugins a medidad para diferentes plataformas, pero que por razones de tiempo hasta ahora no he podido consolidar.

Si son programadores y se dan el trabajo de comparar los códigos, encontrarán cuán 'limpias' son estas nuevas versiones. Y si son emprendedores y buscan descargarse unos plugins útiles para su emprendimiento, seguramente encontrarán que les son de utilidad en su _WordPress/WooCommerce_.


Oscar Alderete
