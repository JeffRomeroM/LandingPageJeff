<template>
    <section class="products">
        <h3 class="h3">Productos</h3>
        <div class="products--container">
            <P>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Expedita quis quas </P>
        </div>
        <div class="products--container">
            <P>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Expedita quis quas </P>
        </div>
        <div class="products--container">
            <P>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Expedita quis quas </P>
        </div>
        <div class="products--container">
            <p>Los productos nuevos que llegaron a tienda son las fundas para Xiaomi</p>
            

            <p>{{ products }}</p>
        </div>
    </section>
</template>

<style>
.products{
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    margin-top: 2%;
    margin-bottom: 2%;
}
.h3{
    width: 100%;
    text-align: center;
    margin-bottom: 2%;
}

.products--container{
    border-radius: 10px;
    width: 20%;
    margin: auto;
    padding: 10px;
    box-shadow: 0 0 10px green;
}

</style>

<script>

export default {
    props: {
        product: {
            type: String,
            required: true
        }
    }
}



</script>