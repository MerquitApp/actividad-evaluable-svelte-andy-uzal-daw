<script>
    let { tituloProducto, precioProducto, urlProducto } = $props();
</script>

<div class="p-4 rounded-lg border-2 border-slate-300">
   <div>
        <img 
        src={urlProducto}
        alt={`imagen-${urlProducto}`}>
   </div>
   <div>
     <h4 class="text-xl">
        {tituloProducto}
     </h4>
     <p class="font-bold text-l">
        {`€${precioProducto}`}
     </p>
   </div> 
</div>