<script>
    import Button from "../Buttons/Button.svelte";
    import InputText from "../Inputs/InputText.svelte";
</script>

<header class="flex justify-between items-center text-center p-4">
    <h1 class="font-bold text-4xl">
        MercApp
    </h1>
    
    <InputText />
    
    <div class="flex gap-8">
        <Button textoBoton="Sign In" />
        <Button textoBoton="Register" />
    </div>
</header>


<style>
</style>