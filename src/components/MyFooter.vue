<template>
    <footer>
        <!--footer up-->
        <div class="bg_black footer_up" >
            <div class="cont" >
                <div class="flex space_btw" >
                    <div class="col flex column white" >
                        <h4> <span class="logo bg_green dark_green " >N E X</span> G E N</h4>
                        <p>
                            A Functional HTML template
                            for Corporate & Business.
                        </p>
                        <a  class="item dark_green" href="#"><i class="fa-solid fa-phone"></i> +1(305)12345678</a>
                        <a  class="item dark_green" href="#"><i class="fa-solid fa-envelope"></i> hello@example.com</a>
                        <a  class="item dark_green" href="#"><i class="fa-solid fa-location-dot"></i> Main Avenue,987</a>
                        <a class="btn white transparent" href="#">READ MORE</a>
                    </div>
                    <div class="col card flex column white" >
                        <h4>About</h4>
                        <ul>
                            <li>
                                <a href="#">the company</a>
                            </li>
                            <li>
                                <a href="#">the company</a>
                            </li>
                            <li>
                                <a href="#">the company</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col card flex column white" >
                        <h4>About</h4>
                        <ul>
                            <li>
                                <a href="#">the company</a>
                            </li>
                            <li>
                                <a href="#">the company</a>
                            </li>
                            <li>
                                <a href="#">the company</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col card flex column white" >
                        <h4>About</h4>
                        <ul>
                            <li>
                                <a href="#">the company</a>
                            </li>
                            <li>
                                <a href="#">the company</a>
                            </li>
                            <li>
                                <a href="#">the company</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <!--footer up-->

        <!--footer Down-->
        <div class="footer_down bg_light_black white" >
            <div class="cont flex space_btw" >
                <p class="" >
                    Enjoy the low price. We are tracking any intention of price.
                </p>
                <p class="flex aligne_it" >
                    <i class="fa-regular fa-copyright"></i>
                    2020 NEXGEN is powered by 
                    <span class="dark_green" >Coding</span>.
                </p>
            </div>
        </div>
        <!--footer Down-->
    </footer>
</template>

<script>
export default {
    name:'MyFooter',

}
</script>

<style scoped lang="scss">

    
    .card{
        background-color: #19191f;
        padding: 30px;
        border-radius: 5px;
        ul{
            margin-top: 5px;
            li{
                list-style-type: none;
                padding: 5px 0px;
                &::before{
                    content: '>';
                    color: rgb(134, 134, 134);
                    margin-right: 5px;
                }
                a{
                    color: rgb(134, 134, 134);
                    text-decoration: none;
                }
            }
        }
    }


</style>