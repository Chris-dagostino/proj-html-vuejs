<template>
    <footer>
        <!--footer up-->
        <div class="bg_black footer_up" >
            <div class="cont" >
                <div class="flex space_btw" >
                    <div class="col flex column white space_btw" >
                        <h4> <span class="logo bg_green green" >N E X</span> G E N</h4>
                        <p>
                            A Functional HTML template
                            for Corporate & Business.
                        </p>
                        <a  class="item" href="#"><i class="fa-solid fa-phone white"></i> +1(305)12345678</a>
                        <a  class="item" href="#"><i class="fa-solid fa-envelope white"></i> hello@example.com</a>
                        <a  class="item" href="#"><i class="fa-solid fa-location-dot white"></i> Main Avenue,987</a>
                        <div>
                            <a class="btn white transparent" href="#">GET IN TOUCH</a>
                        </div>
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
                        <h4>Transport</h4>
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
                        <h4>Support</h4>
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
            <div class="my_container flex space_btw" >
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

    .col{
        width: 20%;
    }
    a , p{
        color: rgb(134, 134, 134);
        text-decoration: none;
    }
    a:hover
    {
        color: white;
    }
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
                
            }
        }
    }


</style>