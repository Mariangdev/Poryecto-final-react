# Proyecto Final Curso React.JS - CoderHouse

Este es mi Proyecto Final para el curso de React JS de CoderHouse. Se trata de una tienda E-commerce de remeras de bandas de rock.

La navegabilidad de este sitio permite entrar a una página principal:



Luego, se podrá acceder a una opción de filtrado de prodcutos por categoría, eligiendo entre Men, Women y un filtro por artista (por ejemplo, si se selecciona la opción "Queen" se mostrarán las remreras de esa banda tanto para hombre como para mujer):


Una vez que accedemos a la vista de detalle, se puede elegir la cantidad por cada prodcuto (cada item tiene su stock individualizado). Ademas de elegir talle y color (esta no es una opción generada en la BBDD, sino que se asigna de manera genérica en el código, a los fines estéticos y funcionales del sitio):

Finalmente, una vez confirmada la compra, se accede a un CheckOut, donde seleccionamos el medio de pago. Además, podremos adicionar el gasto de envío (esto modifica el precio final en tiempo real) y, finalmente, accedemos a un formulario de envío para obtener el código de compra:


La BBDD esta alojada en Firestore. Además, se utilizaron librerías de codigo abierto para el desarrollo de esta aplicación como lo son Bootstrap y MUI Material. También se acude a SweetAlert2 para generar un determinado Alert.

