# ecommerce_page
Simulación de una tienda virtual de muebles

#Especificidad en CSS

¿Qué es mas importante?
En CSS 

nav a {
    Importante (Toma en cuenta los estilos)
}

.clase a{
    Medio importante (Si se tiene una clase y un selector será más importante)
}

#id a{
    Muy importante (Si se tiene un id y u nselector será más importante que todos)
}

#Uso de object-fit

Se define un ancho y un alto y luego el object-fit.

.galeria img {
    width: 40rem;
    height: 30rem;
    object-fit: cover;

    o

    height: 40rem;
    width: 100%;
    object-fit: cover;
}

# Campo datalist

1°parte
< input class="campo__field" list="categorias" name="categorias" placeholder="Tu categoría"

2° parte
< datalist id="categorias">
    < option value="Cocina" >
    < option value="Exterior" >
    < option value="Recamaras" >
    < option value="Oficina" >
    < option value="Televisión">
< /datalist>
