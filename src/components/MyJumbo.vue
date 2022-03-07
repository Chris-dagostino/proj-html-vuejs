<template>
    
    <!--jumbotron-->
    <section class="jumbo" >
        <div class="my_container" >
            
            <nav class="flex space_btw aligne_it" >
                <div class="left" >
                    <div class="flex" >
                        <h4> <span class="logo bg_green green " >N E X</span> G E N</h4>
                    </div>

                </div>
                <div class="right flex" >
                    <ul class="flex aligne_it" >
                        <li v-for="(link, index) in links" :key="index" >
                            <a :href="link.url">{{link.text}}</a>
                        </li>
                        
                        <li>
                            <a href="#"><i class="fa-regular fa-user"></i></a>
                        </li>
                    </ul>
                    <a class="btn white bg_dark-green" href="#">GET IN TOUCH</a>
                </div>
            </nav>

            <div class="cont_tex_1 flex column space_btw" >
                <div class="item green" >LOGISTICS SERVICES</div>
                <h1 class="item" >CARGO TRANSPORT</h1>
                <p class="item" >Fractional or exclusive road cargo transportation to all 
                    regions, whit small, medium and large vehicles.
                </p>
                <div class="item_btn" >
                    <a class="btn white bg_dark-green" href="#">GET IN TOUCH</a>
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
    data() {
    return {
      links: [
          {
              text: "HOME",
              url: "#",
          },
          {
              text: "ABOUT",
              url: "#",
          },
          {
              text: "SERVICES",
              url: "#",
          },
          {
              text: "PROCESS",
              url: "#",
          },
          {
              text: "TESTIMONIALS",
              url: "#",
          },
      ],
    }
  }
}
</script>

<style scoped lang="scss">

    //jumbotron
    .jumbo{
        background: url('../assets/img/bg-9.jpg'), rgb(73, 73, 73);
        background-blend-mode: overlay;
        height: 900px;
        width: 100%;
        object-fit: cover;
        color: #fff;

        nav {

            .right{
                ul{
                    list-style-type: none;
                    padding: 0px 20px;
                    li{
                        &:hover{
                            transform: translateY(-10px);
                            transition: 1s ease;
                        }
                        
                        a{
                            color: #fff;
                            text-decoration: none;
                            padding: 30px;
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