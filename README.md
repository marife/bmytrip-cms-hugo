# Carpeta data
- Contiene dos carpetas para cada lenguaje, con los datos que serán llamados desde el shortcode en el content.

# Carpeta content
- Contiene dos carpetas para cada lenguaje.
- Para llamar al shortcode de español por ejemplo: {{< data  "spanish/archivo" >}} y para inglés {{< data  "english/archivo" >}}

`Hugo server --renderToDisk`
Para crear carpeta public crea dos carpetas EN y ES, donde esta el contenido respectivo a cada lenguaje.