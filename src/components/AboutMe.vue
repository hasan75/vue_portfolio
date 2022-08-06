<template>
 <div class="container">
        <div class="about" id="about">
            <div class="line-styling">
                <div class="style-circle" style="background-color: rgb(245, 101, 57);"></div>
                <div class="style-circle" style="background-color: rgb(245, 101, 57);"></div>
                <div class="style-line" style="background-color: rgb(245, 101, 57);"></div>
            </div>
            <div class="aboutMe">
                <div class="row g-2">
                    <div class="col-12 col-md-6 order order-2 order-md-1">
                        <h1 class="AboutTextOne">Who I am</h1>
                        <p>
                            Hello, It's Hasan Ahmed. I'm a competitive programmer and web developer based in Bangladesh.
                            <br>
                            I have been working with modern web developments materials and technologies like JS, HTML5, CSS3, Bootstrap V5, Tailwind, Material Ui, React, etc. As I have been practicing object-oriented programming, I love to write JS codes. Right now I'm also trying a hand at machine learning and AI. I love to learn and explore new arenas. Besides all of this, I always love to explore the countryside.
                        </p>

                    </div>
                    <div class="col-12 col-md-6 about-img text-center order order-1 order-md-2">
                        <img src="../assets/orangeTheme-girl.af6ec93a.svg" class="img-fluid aboutImg" alt="">
                    </div>
                </div>

            </div>
        </div>
 </div>

</template>

<script>
    export default {
        name:'AboutMe',

    }
</script>

<style scoped>
.about {
    /* min-height: 100vh; */
   
}
.aboutMe{
    top: 8rem;
}

.about .line-styling {
    margin: 30px 10px;
    height: 50px;
    width: 95%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.about .line-styling .style-circle {
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background-color: rgb(245, 101, 57);
}

.about .line-styling .style-line {
    width: 95%;
    height: 5px;
    border-radius: 10px;
}
.AboutTextOne{
    color: rgb(245, 101, 57);
    font-weight: 700;
    font-size: 2.7rem;
    /* font-family: 'Satisfy', cursive; */
    /* font-family: 'Dancing Script', cursive; */
    font-family: 'Permanent Marker', cursive; 
    margin-bottom: 1rem;
     padding: 30px 0px;
}
p{
    font-size: 1.4rem;
    color: #A8C2C2;
}

.about-img > img {
    width: 250px;
    margin-top: 20px;
}


@media screen and (max-width: 992px){
    .about .line-styling {
    top: 20px;
}
}

@media screen and (max-width: 800px){
.about .line-styling .style-circle {
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background-color: rgb(245, 101, 57);
}
}

@media screen and (max-width: 600px){

    .about .line-styling .style-circle {
    width: 5px;
    height: 5px;
    border-radius: 50%;
}
    .about .line-styling .style-line {
    width: 93%;
    height: 3px;
    border-radius: 10px;
}
.AboutTextOne{
    text-align: center;
    margin-top: 1rem;
}
.about-img > img {
    width: 250px;
    margin-top: 1px;
}

}
</style>