<template>
    <!--certification-->
    <section class="certification cont flex" >
        <div class="flex space_btw" >
            <div class="left flex column" >
                <span class="dark_green" >WHO WE ARE</span>
                <h2 class="title" >
                    <span class="title-diff dark_green" >
                        <i class="fa-solid fa-gem"></i> Excellence</span> in Transport
                </h2>
                
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Iure sint magnam, mollitia molestiae beatae adipisci sapiente expedita dolore facere ad vel veritatis at, porro nulla unde rem, vitae aliquam? Eos.</p>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Debitis deleniti eligendi in labore eaque nisi deserunt quidem error perspiciatis, voluptatibus minima esse molestiae laborum consequuntur at nesciunt? Accusamus, quas reprehenderit?</p>
                <p class="border" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit voluptate dolores fugit quibusdam blanditiis, non quo possimus fugiat laborum eveniet eius iste, at quae libero reiciendis ex sunt quas quisquam.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi eos, nisi doloribus magnam maiores sequm</p>
                <ul>
                    <li>
                        lorem ipsum dolor sit amet
                    </li>
                    <li>
                        lorem ipsum dolor sit amet
                    </li>
                    <li>
                        lorem ipsum dolor sit amet
                    </li>
                    <li>
                        lorem ipsum dolor sit amet
                    </li>
                    <li>
                        lorem ipsum dolor sit amet
                    </li>
                </ul>
            </div>
            <div class="right flex column" >
                <h3>Vehicles Types</h3>
                <div class="flex" >
                    <img class="vehicle bg_green " src="../assets/img/truck-1.png" width="100" alt="truck">
                    <div class="flex column" >
                        <h3>Light</h3>
                        <p class="grey" >Max weight 1200 kg</p>
                    </div>
                </div>
                <hr>
                <div class="flex" >
                    <img class="vehicle bg_green"  src="../assets/img/truck-1.png" width="100" alt="truck">
                    <div class="flex column" >
                        <h3>Light</h3>
                        <p class="grey" >Max weight 1200 kg</p>
                    </div>
                </div>
                <hr>
                <div class="flex" >
                    <img class="vehicle bg_green"  src="../assets/img/truck-1.png" width="100" alt="truck">
                    <div class="flex column" >
                        <h3>Light</h3>
                        <p class="grey" >Max weight 1200 kg</p>
                    </div>
                </div>
                <h3>Certification</h3>
                <div class="flex space_ard" >
                    <div class="box" >
                        <img src="../assets/img/certificate.png" width="100" alt="certificate">
                    </div>
                    <div class="box" >
                        <img src="../assets/img/certificate.png" width="100" alt="certificate">
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!--certification-->
</template>

<script>
export default {
    name:'MyCertification',

}
</script>

<style scoped lang="scss">

    //certification
    .left{
        width: 75%;
        margin-right: 30px;
        p{
            padding: 20px 0px;
            color: grey;
            width: 90%;
        }
        .border{
            border-left: 5px solid rgb(82, 187, 187,0.3) ;
            padding-left: 20px;
        }
        ul{
            margin-left: 20px;
            li{
                padding: 5px;
                color: grey;
            }
        }
    }
    .right {
        width: 25%;
        h3{
            padding: 20px 0px;
        }
        .vehicle{
            padding: 5px;
            border-radius: 5px;
            margin: 10px 10px 10px 0px;
        }
        .box{
            box-shadow: 5px 2px 8px #888888;
            img{
                width: 130px;
                height: 120px;
            }
        }
    }


    //certification
    
</style>