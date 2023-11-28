[[Diseño 2D]] 

**1. ¿Qué relación hay entre el tamaño en píxeles de una imagen y su tamaño de impresión?**
	Se relacionan mediante la fórmula:
		$$
	Resolución (ppp)= \frac {nºpixeles}{tamaño. Píxeles }
	$$

*Es la relacion entre las digitales y las físicas*

**2. ¿Cuál sería el tamaño de imagen más adecuado para una impresión de 3x4 pulgadas en una impresora de 150 ppp?** 
*1 pulgada = 2,54cm*
	La resolución de la imagen sería 450x600 píxeles. 
	$$
	nºpixeles.horizontales = AnchoImpresion * Resolucion(ppp) 
	$$
	$$
	nºpixeles.altura = AltoImpresion * Resolucion(ppp)
	$$


**3. ¿Cuántos bits por canal tienen las imágenes HDR? ¿Qué ventajas presentan frente a una imagen de 8 bits por canal?** 
	Tienen 32 bits por cada canal. En pocas palabras, representan, de forma más fiel, escenas realistas que realzan la luz directa del sol o incluso la luz tenue de las estrellas. 
   
**4. En un formato JPG, ¿cómo varían la calidad de la imagen y el tamaño del archivo al modificar el ratio de comprensión?** 
	Descarta datos de forma selectiva, haciendo lo que se conoce como “comprimir con pérdida”.
	*A mayor ratio se disminuye la calidad y el tamaño del archivo.* 
   
**5. ¿Qué características tiene el formato TIFF?** 
	Es un formato de archivo sin compresión (también admite con/sin pérdida), pensado para guardar imágenes que requieran de toda la calidad posible. 
   
**6. ¿Qué se utiliza más en la web TIFF o PNG?** 
	Se utiliza más el PNG debido a que permite comprimir sin pérdidas pero con un tamaño de archivo muy reducido. 
   
**7. ¿Cuánto espacio en disco necesitaríamos para almacenar una imagen de 1024x768 píxeles en formato RGB sin compresión?**
	Usando la fórmula 
	$$
		Tamaño = \frac{1024 * 768 * 24}{8}
	$$
	Podemos calcular que serían:
	$$
	Tamaño = 2.359.296 bytes  => 2,36mb
	$$
   