<template>
    <section class="informations">
        <div class="img">
            <img src="../assets/pexels-soumil-kumar-735911.jpg" alt="">
        </div>

        <div class="beneficios">
            <p class="beneficios--p">{{ general }}</p>

        </div>
    </section>
</template>

<style>
.informations{
    width: 45%;
    margin: auto;
}
.img{
    width: 100%;
    margin: 2% auto;
}
.img img{
    width: 90%;
    margin: auto;
    border-radius: 10px;
    box-shadow: 0 0 20px rgb(44, 175, 83);

}
.beneficios{
    padding: 10px;
}
</style>


<script>
export default {
    props: {
        general: {
            type: String,
            required: true
        }

    }
}
</script>