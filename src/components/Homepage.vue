<template>
        <!-- Front cover  -->
    <main>
        <div class="fc">
            <div id="ftt">
                WELCOME TO
            </div>
            <div id="ftm">
                NEW HAPPINESS
            </div>
            <div id="ftb">
                THE HOME FOR YOUR HAIR
            </div>
        </div>
    
    <!-- Shop Description -->
        <div class="desccont">
            <div id="desctext">
                In this universe you will find the finest from the New Happiness line of hair products
                <br>Here is what we can offer you
            </div>
        </div>
    </main>
</template>

<script>
    export default {
  name: 'Homepage',
}
</script>

<style>
/* Front Cover and Text */

.fc {
    width: auto;
    height: 300px;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-direction: column;
}

#ftt,#ftb {
    font-size: 30px;
}

#ftm {
    font-size: 80px;
}

/* Front cover DESCRIPTION*/

.desccont{
    margin-top: 7px;
    height: auto;
    color: white;
    display: flex;
    justify-content: center;
}

#desctext{
    text-align: center;
    font-size: 25px;
    width: 100%;
    margin-top: 5px;
}
</style>