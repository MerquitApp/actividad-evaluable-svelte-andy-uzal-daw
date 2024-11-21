<script>
    import Article from "../lib/components/Article/Article.svelte";
    import Footer from "../lib/components/Footer/Footer.svelte";
    import Header from "../lib/components/Header/Header.svelte";   
    import Main from "../lib/components/Main/Main.svelte";
    import SectionProducts from "../lib/components/Section/SectionProducts.svelte";
</script>

<div>
    <Header />
    <Main />
    <Article 
    tituloArticle="Zapatillas de deporte" 
    subTituloArticle="¡Al mejor precio!"
    /> 
    <SectionProducts />
    <Footer />
</div>