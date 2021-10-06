<template>
  
    <div class="container-show">

        <div class="container--img--desc">

            <img src="../assets/house.jpg" alt="">

            <div class="descrizioni">
                
                <h2>Titolo casa</h2>
                
                <span>Recensioni</span>

            </div>

        </div>
       
        <div class="banner-servizi">

            <h2>Servizi</h2>

            <ul class="el-servizi">
                <li><i class="fas fa-bed"></i> Letti: codice</li>
                <li><i class="fas fa-house-user"></i> Stanze: codice</li>
                <li><i class="fas fa-restroom"></i> Bagni: codice</li>
                <li><i class="fas fa-align-justify"></i> ecc: codice</li>
            </ul>

        </div>
       


    </div>

</template>


<script>

    export default {

    }

</script>


<style lang="scss" scoped>

    .container-show {
        border-radius: 20px;
        width: 100%;
        height: 500px;
        margin-top: 100px;

        .container--img--desc {
            height: 500px;
            border-radius: 20px;
            display: flex;
            width: 90%;
            background-color: rgba(128, 128, 128, 0.13);
            margin: 0 auto;
            animation: animate 2s;

            img {
                width: 50%;
                height: 500px;
                border-radius: 20px;
                position: absolute;
            }

            .descrizioni {
                width: 50%;
                margin-left: 70%;
            }

        }

        .banner-servizi {
            background-color: rgba(128, 128, 128, 0.13);
            width: 90%;
            margin: 0 auto;
            border-radius: 20px;
            padding: 30px;
            margin-top: 30px;

            .el-servizi {
                display: flex;
                margin: 20px;
                list-style: none;

                li {
                    margin: 0px 20px;
                }

            }

        }
        
    }
    

    @keyframes animate {

        from {
            width: 50%;
        }

        to {
            width: 90%;
        }

    }

     // PARTE RESPONSIVE
    @media (max-width: 968px) {

        .container {

            margin-top: 150px;

            .container--img--desc {

                display: block;
                animation: none;
                width: 90%;

                img { 
                    width: 90%;
                    height: 300px;
                }

                .descrizioni {
                    width: 50%;
                    margin-left: 0;
                    padding: 350px 0px 0px 30px;

                }

            }

        }

    }

</style>