<template>

    <div class="title">
        <h1 class="title--information"> {{ nameCompany }} </h1>
    </div>

</template>

<style>
.title{
    width: 90%;
    margin:12% auto;
    border-radius: 3px;
    box-shadow: 0 0 15px  rgb(105, 160, 112);
    text-align: center;
}
</style>


<script>
export default {
    props: {
        nameCompany: {
            type: String,
            required: true
        }

    }
}
</script>