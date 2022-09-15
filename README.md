Para crear una aplicación de AR hemos de seguir los mismos pasos para exportar una apk que seguimos en la aplicación de Android.

Para incluir la funcionalidad AR debemos añadir desde el Package Manager la herramienta XR Plugin Management

Ahora seguiremos estos pasos:
- Añadiremos un GameObject vacío para añadirle el componente ARSession
- Añadiremos un XR Origin
- Como hijo del XR Origin añadiremos un objeto vacío (nuestro offset) y dentro de este nuestra Main Camera (si no existía, la crearemos)
- Al XR Origin, le colocaremos los valores de offset y cámara
- Crearemos un default plane
- Crearemos un ARCursor
- Colocaremos el objeto a mostrar como parámetro del AR Cursor