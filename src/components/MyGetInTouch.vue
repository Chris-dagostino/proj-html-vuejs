<template>
    <!--get_in_touch-->
    <section class="get_in_touch" >
        <div class="cont flex space_btw" >
            <div class="left" >
                <span class="dark_green" >SEND MESSAGE</span>
                <h3 class="title padg" >Get in <span class="title-diff dark_green" >Touch</span></h3>
                <p>
                    We will to your message as soon as possible
                </p>
                <div class="padg" >
                    <div>
                        <input type="text" placeholder="Name" >
                        <input type="text" placeholder="Email" >
                    </div>
                    <div>
                        <input type="text" placeholder="Phone" >
                        <input type="text" placeholder="More info" >
                    </div>
                    <div>
                        <input type="text" placeholder="Message" >
                    </div>
                </div>
                <a class="btn white bg_dark-green" href="#">SEND</a>
            </div>

            <div class="right flex column " >
                <h3>Exemple Inc.</h3>
                <p class="padg grey" >Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                <p class="padg grey" >Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                <a  class="flex dark_green aligne_it" href="#"><i class="icon fa-solid fa-phone"></i> +1(305)12345678</a>
                <a  class="flex dark_green aligne_it" href="#"><i class="icon fa-solid fa-envelope"></i> hello@example.com</a>
                <div class="" >
                    <a  class="flex dark_green aligne_it" href="#"><i class="icon fa-solid fa-location-dot"></i> Main Avenue,987</a>
                </div>
                <div class="padg">
                    <a class="btn transparent dark_green" href="#">VIEW MAP</a>
                </div>
            </div>

        </div>
        
    </section>
    <!--get_in_touch-->
</template>

<script>
export default {
    name:'MyGetInTouch',

}
</script>

<style scoped lang="scss">

    //get_in_touch
    .left{
        width: 60%;
        input{
            width: 45%;
            height: 30px;
            background-color: #e6ece8;
            border: none;
            border-radius: 5px;
            padding: 10px;
            margin: 5px  ;
        }
        .mex{
            width: 100%;
        }
    }
    .right{
        width: 35%;
        a{
            padding: 10px 0px;
            text-decoration: none;
            .icon{
                width: 15px;
                height: 15px;
                background-color: rgb(82, 187, 187,0.3);
                border-radius: 50%;
                padding: 10px;
                margin-right: 10px;
            }
        }
    }
    
    
    //get_in_touch
    
</style>