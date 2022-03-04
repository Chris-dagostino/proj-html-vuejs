<template>
    <!--services-->
    <section class="services" >
        <div class="my_container" >
            <div class="flex column" >
                <div class=" txt_center" >
                    <span class="green" >ROAD TRANSPORT</span>
                    <h3 class="white padg" >Main<span class="bg_txt " > Services</span></h3>
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
                        <i class="fa-solid fa-truck-ramp-box green"></i>
                        <h3>Technology</h3>
                        <p> 
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            Possimus, expedita vel itaque, voluptas quam provident,
                        </p>
                    </div>
                    <div class="card card_centr white" >
                        <i class="fa-solid fa-truck-ramp-box green"></i>
                        <h3>Technology</h3>
                        <p> 
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            Possimus, expedita vel itaque, voluptas quam provident,
                        </p>
                    </div>
                    <div class="card white" >
                        <i class="fa-solid fa-truck-ramp-box green"></i>
                        <h3>Technology</h3>
                        <p> 
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            Possimus, expedita vel itaque, voluptas quam provident,
                        </p>
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
            
            i{
                width: 10px;
                height: 10px;
                background-color: #52bbbb;
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