<template>
    <!--services-->
    <section class="services" >
        <div class="cont" >
            <div class="flex column" >
                <div class=" txt_center" >
                    <span class="green" >ROAD TRANSPORT</span>
                    <h3 class="title white padg" >Trusted <span class="title-diff " > Feedback</span></h3>
                    <div class="flex aligne_it white " >
                        <p>
                            Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                            Odit aut odio quo dolore earum officiis similique tempora 
                            asperiores iure vel, recusandae corporis sunt harum. 
                            Voluptatibus explicabo adipisci consectetur debitis asperiores!
                        </p>
                    </div>
                </div>

                <!--card-->
                <div class="flex " >
                    <div class="card white" >
                        <img src="../assets/img/logo-1.png" alt="">
                        <p> 
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            Possimus, expedita vel itaque, voluptas quam provident,
                        </p>
                        <i class="fa-solid fa-quote-right"></i>
                    </div>
                    <div class="card card_centr white" >
                        <img src="../assets/img/logo-2.png" alt="">
                        <p> 
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            Possimus, expedita vel itaque, voluptas quam provident,
                        </p>
                        <i class="fa-solid fa-quote-right"></i>
                    </div>
                    <div class="card white" >
                        <img src="../assets/img/logo-3.png" alt="">
                        <p> 
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            Possimus, expedita vel itaque, voluptas quam provident,
                        </p>
                        <i class="fa-solid fa-quote-right"></i>
                    </div>
                </div>
                

            </div>
        </div> 
    </section>
    
    <!--services-->
</template>

<script>
export default {
    name:'MyFeedback',

}
</script>

<style scoped lang="scss">

    //services
    .services {
        background-color: #000;

        .card{
            width: 30%;
            background-color: #19191f;
            border-radius: 5px;
            padding: 40px;
            margin: 30px 0px;
            position: relative;
            
            img{
                filter: invert(1);
                padding: 10px 0px;
                width: 120px;
            }
            
            h3{
                padding: 20px 0px;
            }
        }
        .card_centr{
            margin: 30px 5%;
        }
    }
    //services
    
</style>