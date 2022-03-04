<template>
    
    <!--jumbotron-->
    <section class="jumbo" >
        <div class="my_container" >
            
            <nav class="flex space_btw aligne_it" >
                <div class="left" >
                    <div class="logo flex" >
                        <div class="Bg_green item" >N E X</div>
                        <div class="item" >G E N</div>
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
                    <a class="btn bg_green" href="#">GET IN TOUCH</a>
                </div>
            </nav>

            <div class="cont_tex_1 flex column space_btw" >
                <div class="item green" >LOGISTICS SERVICES</div>
                <h1 class="item" >CARGO TRANSPORT</h1>
                <p class="item" >Fractional or exclusive road cargo transportation to all 
                    regions, whit small, medium and large vehicles.
                </p>
                <div class="item_btn" >
                    <a class="btn bg_green" href="#">GET IN TOUCH</a>
                    <a class="btn transparent" href="#">READ MORE</a>
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
    
                .Bg_green{
                    background-color: rgb(82, 187, 187, 0.3);
                    border-top-left-radius: 20px ;
                    border-bottom-left-radius: 20px ;
                    color: #52bbbb;
                    padding-left: 20px;
                    padding-right: 5px;
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