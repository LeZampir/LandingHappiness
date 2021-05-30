<template>
    <main>
        <div class="footcont">
            <div id="socials">
                <p>Our products</p>
                <a href="">Sensus</a>
                <a href="">Sono</a>
                <a href="">Barba Italiana</a>
            </div>
            <div id="contact">
                <p>Contact Us</p>
                <a href="">Mobile</a>
                <a href="">Mail</a>
                <a href="">Business</a>
            </div>
            <div id="helpsect">
                <p>FAQ Section</p>
                <a href="">About us</a>
                <a href="">What is our goal</a>
                <a href="">The Team</a>
            </div>
        </div>
    </main>
</template>

<script>
    export default {
        name: 'Footer'
    }
</script>

<style>
.footcont{
    color: white;
    margin-top: 5px;
    display: flex;
    justify-content: space-around;
    text-align: center;
}

a{
    margin: 20px;
    display: flex;
    justify-content: center;
}



p{
    font-size: 25px;
}
</style>