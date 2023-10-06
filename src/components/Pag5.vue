<script setup>

</script>

<template>
  <div class="pag5">
    <div class="container">
        <div class="title-pag5"><h2>3 METABOLIC BOOSTERS</h2></div>
        <div class="container-bar">
            <div class="bar1">
                 <h3>AMINO ACIDS</h3>
                <a href=""><i class="bi bi-plus"></i></a>
            </div>
            <div class="bar2">
                 <h3>ANTIOXIDANTS</h3>
                 <a href=""><i class="bi bi-plus"></i></a>
            </div>
            <div class="bar3">
                 <h3>PROTEIN</h3>
                 <a href=""><i class="bi bi-plus"></i></a>
            </div>
        </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
@use "../assets/styles/general.scss";
.pag5{
    background-color:#1a1a17 ;
    padding-top: 100px;
}
.container{
    padding: 0px 100px;
}
.title-pag5{
    display: flex;
    align-items: center;
    padding-bottom: 100px;
}
.title-pag5 h2{
    font-size: 70px;
    color: #FFFFFF;
}
.bar1, .bar2, .bar3{
    height: 20%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 30px;
    color: #FFFFFF;
    border-top: 1px solid white;
    padding: 20px 0px;
}
.bar1 i, .bar2 i, .bar3 i{
    font-size: 80px;
}
.bar2{
    opacity: .5;
}
.bar3{
    opacity: .3;
    border-bottom: 1px solid white;
    padding-bottom: 100px;
}
@media (max-width: 770px) {
    .container{
        padding: 0px 20px;
    }
    .title-pag5 h2{
        font-size: 50px;
    }
    .bar1 i, .bar2 i, .bar3 i{
    font-size: 60px;
    .bar1 h3, .bar2 h3, .bar3 h3{
        font-size: 30px;
    }
    }
    .bar2{
        flex-wrap: wrap;
    }
    


    
}
    

</style>
