<template>
    <!--numbers-->
    <section class="numbers txt_center cont white" >
        <div>
            <span class="dark_green" >HOW IT WORKS IN PRATICS</span>
            <h3 class="padg" ><span class="bg_txt " >Results</span>in Numbers</h3>
        </div>
        <div class="cont card flex space_ard txt_center dark_green padg" >
            <div>
                <h4>128</h4>
                <span class="white" >Certifications</span>
            </div>
            <div>
                <h4>230</h4>
                <span class="white" >Employees</span>
            </div>
            <div>
                <h4>517</h4>
                <span class="white" >Customers</span>
            </div>
            <div>
                <h4>94</h4>
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
        height: 600px;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        h4{
            width: 50%;
            margin: auto;
            padding: 10px 0px;
        }
    }
    
    //numbers
    
</style>