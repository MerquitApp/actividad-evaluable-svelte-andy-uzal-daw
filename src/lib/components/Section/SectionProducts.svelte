<script>
    import CardProduct from "../Card/CardProduct.svelte";
    import nikeImagenUno from '../../../assets/nike_imagen_uno.png';
    import nikeImagenDos from '../../../assets/nike_imagen_dos.png';
    import nikeImagenTres from '../../../assets/nike_imagen_tres.png';
</script>

<section class="w-full justify-center flex gap-10 p-4">
    <CardProduct 
    tituloProducto="Nike Air Force 1 LV8"
    precioProducto="120"
    urlProducto={nikeImagenUno}
    />
    <CardProduct 
    tituloProducto="Nike Air Force 1"
    precioProducto="100"
    urlProducto={nikeImagenDos}
    />
    <CardProduct 
    tituloProducto="Nike Next Nature"
    precioProducto="70"
    urlProducto={nikeImagenTres}
    />
</section>