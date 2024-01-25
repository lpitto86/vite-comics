<script>
export default {
    name: "AppJumbotron",
}
</script>

<template>
    <div class="container-fluid bg-image">
    </div>
        <div class="container">
            <div class="row d-flex text-center align-items-center">

            </div>
        </div>
</template>

<style scoped>
    .bg-image {
        background-image: url(../assets/img/jumbotron.jpg);
        background-size: cover;
        height: 20rem;
        object-position: 50% 50%;
    }

    button {
        background-color: #0282F9;
        color: white;
        border: none;
        padding: 1rem;
    }

    span {
        font-size: 1.5rem;
        font-weight: bold;
    }
</style>