<template>
    <!--services-->
    <section class="services bg_black" >
        <div class="cont" >
            <div class="flex column" >
                <span class="green" >ROAD TRANSPORT</span>
                <h3 class="white title padg " >Main <span class="title-diff " > Services</span></h3>
                <div class="left flex aligne_it white" >
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                        Odit aut odio quo dolore earum officiis similique tempora 
                        asperiores iure vel, recusandae corporis sunt harum. 
                        Voluptatibus explicabo adipisci consectetur debitis asperiores!
                    </p>
                    <div class="right item_btn" >
                        <a class="btn white transparent" href="#">READ MORE</a>
                    </div>
                </div>

                <!--card-->
                <div class="flex" >
                    <div class="card white" >
                        <i class="fa-solid fa-truck-ramp-box green"></i>
                        <h3>Technology</h3>
                        <p> 
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            Possimus, expedita vel itaque, voluptas quam provident,
                        </p>
                    </div>
                    <div class="card card_centr white" >
                        <i class="fa-solid fa-temperature-low green"></i>
                        <h3>Reefer Cargo</h3>
                        <p> 
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                            Possimus, expedita vel itaque, voluptas quam provident,
                        </p>
                    </div>
                    <div class="card white" >
                        <i class="fa-solid fa-boxes-stacked green"></i>
                        <h3>Dry Cargo</h3>
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
    name:'MyServices',

}
</script>

<style scoped lang="scss">

    //services
    .services {
        .left {
            width: 70%;
        }
        .right {
            width: 30%;
        }

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