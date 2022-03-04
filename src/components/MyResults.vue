<template>
    <!--numbers-->
    <section class="numbers txt_center cont white" >
        <div>
            <span class="dark_green" >HOW IT WORKS IN PRATICS</span>
            <h3 class="padg" ><span class="bg_txt " >Results</span>in Numbers</h3>
        </div>

        <div class="card flex txt_center padg" >
            <div>
                <h4>128</h4>
            </div>
            <div>
                <h4>230</h4>
            </div>
            <div>
                <h4>517</h4>
            </div>
            <div>
                <h4>94</h4>
            </div>
        </div>
    </section>
    <!--numbers-->
</template>

<script>
export default {
    name:'MyResults',

}
</script>

<style scoped lang="scss">

    //numbers
    .numbers{
        background-image: url('../assets/img/bg-10.jpg');
        height: 600px;
        width: 100%;
        object-fit: cover;
        h4{
            width: 50%;
            margin: auto;
            padding: 10px 0px;
        }
    }
    
    //numbers
    
</style>