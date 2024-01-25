<script>
export default {
    name: "AppHeader",
}
</script>

<template>
    <div class="container mt-4 mb-4">
        <div class="row">        
            <div class="col-4">
                <img src="../assets/img/dc-logo.png" alt="logo">
            </div>
            <div class="col-8 d-flex justify-content-end">
                <nav class="d-flex align-items-center justify-content-center">
                    <ul class="list-unstyled d-flex gap-4">
                        <li><a href="#">CHARACTERS</a></li>
                        <li><a href="#">COMICS</a></li>
                        <li><a href="#">MOVIES</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">GAMES</a></li>
                        <li><a href="#">COLLECTIBLES</a></li>
                        <li><a href="#">VIDEOS</a></li>
                        <li><a href="#">FANS</a></li>
                        <li><a href="#">NEWS</a></li>
                        <li><a href="#">SHOP</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </div>
</template>

<style scoped>
    a {
    text-decoration: none;
    color: black;
    }
</style>