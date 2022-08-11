<template>
    <nav class="navbar">
        <div class="container">
            <a href="/" class="navbar-brand">
                <img src="../assets/logo-black.svg" id="navbar-logo">
            </a>
            <a href="/app" class="navbar-toggler">
                <button class="button">
                    <i class="icon-fire"></i>
                    Escritório virtual
                </button>
            </a>
        </div>
    </nav>
</template>

<script lang="ts">
    export default {
        name: "NavBar"
    }
</script>

<style lang="css" scoped>
    /* Navbar*/

.navbar {
    background: #fff;
    height: 70px;
    box-shadow: 0 1px 15px rgb(0 0 0 / 4%), 0 1px 6px rgb(0 0 0 / 4%);
    position: fixed;
    top: 0;
    right: 0;
    left: 0;
    display: block;
    box-sizing: border-box;

    padding: 0.25rem 0.75rem;
    font-size: 1.25rem;
    line-height: 1;
    background-color: transparent;
    border: 1px solid transparent;
    border-radius: 0.25rem;
}

@media (max-width: 767px) {
    .navbar {
        height: 70px;
        padding: 10px 0;
    }
}

@media (max-width: 1199px) {
    .navbar {
        height: 80px;
        padding: 1rem 0 1rem 0;
    }
}

@media (max-width: 1439px) {
    .navbar {
        height: 90px;
    }
}

.navbar .container {
    position: relative;
    margin: 0 auto;
    padding-right: 15px;
    padding-left: 15px;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
}

.navbar-brand {
    float: left;
    height: 50px;
    padding: 15px 15px;
}

.navbar-brand>img {
    display: block;
    height: 2.75rem;
}

/* Navbar Button*/

.button {
    padding: 0.5rem 1rem;
    font-size: .76rem;
    line-height: 1.5;
    cursor: pointer;
    display: inline-block;
    font-weight: 400;
    text-align: center;
    vertical-align: middle;
    color: #fff;
    background-color: #1c8968;
    border-color: #1c8968;
    border: 1px solid transparent;
    border-radius: 50px;
    outline: initial !important;
    box-shadow: none !important;
    -webkit-appearance: button;
}
</style>