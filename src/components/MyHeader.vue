<template>
    <header>
        <div class="my_container flex space_btw" >
            <div class="left" >
                <div class="item" >
                    Open Hours Mon-Sat-9:00-18:00
                </div>
            </div>
            <div class="right flex space_btw" >
                <a  class="item" href="#">+1(305)12345678</a>
                <a  class="item" href="#">hello@example.com</a>
                
                <div class="item" >
                    icons
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
            width: 30%;
        }
        .item {
            padding: 15px 0px;
            color: #bcbdbd;
            text-decoration: none
        };
    };

</style>