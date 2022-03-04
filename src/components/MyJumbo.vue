<template>
    
    <!--jumbotron-->
    <section class="jumbo" >
        <div class="my_container" >
            
            <nav class="flex space_btw aligne_it" >
                <div class="left" >
                    <div class="flex" >
                        <h4> <span class="logo bg_green dark_green " >N E X</span> G E N</h4>
                    </div>

                </div>
                <div class="right flex" >
                    <ul class="flex aligne_it" >
                        <li>
                            <a href="#">HOME</a>
                        </li>
                        <li>
                            <a href="#">ABOUT</a>
                        </li>
                        <li>
                            <a href="#">SERVICE</a>
                        </li>
                        <li>
                            <a href="#">PROCESS</a>
                        </li>
                        <li>
                            <a href="#">TESTIMONIALS</a>
                        </li>
                        <li>
                            <i class="fa-regular fa-user"></i>
                        </li>
                    </ul>
                    <a class="btn white bg_green" href="#">GET IN TOUCH</a>
                </div>
            </nav>

            <div class="cont_tex_1 flex column space_btw" >
                <div class="item green" >LOGISTICS SERVICES</div>
                <h1 class="item" >CARGO TRANSPORT</h1>
                <p class="item" >Fractional or exclusive road cargo transportation to all 
                    regions, whit small, medium and large vehicles.
                </p>
                <div class="item_btn" >
                    <a class="btn white bg_green" href="#">GET IN TOUCH</a>
                    <a class="btn white transparent" href="#">READ MORE</a>
                </div>
            </div>

        </div>
    </section>
    <!--fine jumbotron-->

</template>

<script>
export default {
    name:'MyJumbo',

}
</script>

<style scoped lang="scss">

    //jumbotron
    .jumbo{
        background-image: url('../assets/img/bg-9.jpg');
        height: 900px;
        width: 100%;
        object-fit: cover;
        color: #fff;

        nav {
            padding-top: 15px;
            .left {
                .item {
                    padding: 10px 0px;
                    font-weight: bolder;
                    margin: 1px;
                }
            }

            .right{
                ul{
                    list-style-type: none;
                    li{
                        margin: 0px 20px;
                        a{
                            color: #fff;
                            text-decoration: none;
                        }
                    }
                }
            }
        }

        .cont_tex_1{
            padding: 200px 0px;
            width: 40%; 

            h1{
                font-size: 80px;
            }
            .item_btn{
                margin-top: 30px;

                a{
                    margin-right: 20px;
                }
            }
        }
    }
    //jumbotron
</style>