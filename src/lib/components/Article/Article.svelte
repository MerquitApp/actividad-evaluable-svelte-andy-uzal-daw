<script>
    let { tituloArticle, subTituloArticle } = $props()    
</script>

<article class="w-full p-4 flex flex-col justify-start gap-1">
    <h3 class="font-bold text-xl">
        {tituloArticle}
    </h3>
    <h2 class="font-normal text-s text-gray-400">
        {subTituloArticle}
    </h2>
</article>
