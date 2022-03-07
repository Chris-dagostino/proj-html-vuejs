<template>
    <!--numbers-->
    <section class="numbers txt_center cont white" >
        <div>
            <span class="dark_green" >HOW IT WORKS IN PRATICS</span>
            <h3 class="title padg" ><span class=" title-diff " >Results</span> in Numbers</h3>
        </div>
        <div class="cont card flex space_ard txt_center dark_green padg" >
            <div>
                <h3>128</h3>
                <span class="white" >Certifications</span>
            </div>
            <div>
                <h3>230</h3>
                <span class="white" >Employees</span>
            </div>
            <div>
                <h3>517</h3>
                <span class="white" >Customers</span>
            </div>
            <div>
                <h3>94</h3>
                <span class="white" >Countries Served</span>
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
        width: 100%;
        height: 500px;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        h3{
            font-size: 40px;
            
        }
    }
    
    //numbers
    
</style>