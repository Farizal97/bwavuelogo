<template>
<div class="logos-wrapper">
    <h2 class="title-header">Find Best Logo</h2>
    <div class="items-logos">
       <img class="logo" alt="Starbucks logo" src="../assets/starbucks-logo.png">
    </div>
    <div class="items-logos">
       <img class="logo" alt="Starbucks logo" src="../assets/google.png">
    </div>
    <div class="items-logos">
       <img class="logo" alt="Starbucks logo" src="../assets/b-logo.png">
    </div>
    <div class="items-logos">
       <img class="logo" alt="Starbucks logo" src="../assets/starbucks-logo.png">
    </div>
     <div class="items-logos">
       <img class="logo" alt="Starbucks logo" src="../assets/b-logo.png">
    </div>
    <div class="items-logos">
       <img class="logo" alt="Starbucks logo" src="../assets/google.png">
    </div>
    <div class="items-logos">
       <img class="logo" alt="Starbucks logo" src="../assets/starbucks-logo.png">
    </div>
</div>
</template>

<script>
export default {
    name: 'Logos'
}
</script>



<style scoped>
.title-header {
    margin-bottom: 80px;
    text-align: left;
}
.logos-wrapper {
    width: 62%;
    overflow: hidden;
    margin: auto;
}

.items-logos {
    float: left;
    margin-right: 70px;
    margin-bottom: 70px;
    width: 150px;
    height: 150px;
}


.items-logos .logo {
    width: 150px;
    height: 150px;
}

</style>