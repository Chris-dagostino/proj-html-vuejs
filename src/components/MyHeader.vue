<template>
    <header>
        <div class="my_container flex space_btw" >
            <div class="left" >
                <div class="item" >
                    <i class="fa-solid fa-clock"></i> Open Hours Mon-Sat-9:00-18:00
                </div>
            </div>
            <div class="right flex space_btw" >
                
                <a  class="item" href="#"><i class="fa-solid fa-phone"></i> +1(305)12345678</a>
                <a  class="item" href="#"><i class="fa-solid fa-envelope"></i> hello@example.com</a>
                
                <div class="icons item flex" >
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-linkedin-in"></i>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name:'MyHeader',

}
</script>

<style scoped lang="scss">

    header{
        background-color: #21333e;
        .right{
            width: 45%;
        }
        .item {
            color: #bcbdbd;
            text-decoration: none
        };
        .icons{
            width: 15%;
            justify-content: space-between;
        }
    };

</style>