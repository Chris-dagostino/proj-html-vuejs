<template>
  <main>
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
                                <a href="#"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><!--! Font Awesome Pro 6.0.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M224 256c70.7 0 128-57.31 128-128s-57.3-128-128-128C153.3 0 96 57.31 96 128S153.3 256 224 256zM274.7 304H173.3C77.61 304 0 381.6 0 477.3c0 19.14 15.52 34.67 34.66 34.67h378.7C432.5 512 448 496.5 448 477.3C448 381.6 370.4 304 274.7 304z"/></svg></a>
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
                    <div class="item" >
                        <a class="btn bg_green" href="#">GET IN TOUCH</a>
                        <a class="btn transparent" href="#">READ MORE</a>
                    </div>
                </div>

            </div>
        </section>
        <!--fine jumbotron-->
            
  </main>
</template>

<script>
export default {
    name:'MyMain',

}
</script>

<style scoped lang="scss">
    main{
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
            padding: 300px 0px;
            width: 40%; 

            .item {
                margin: 10px 0px;
            }
        }
    }

</style>