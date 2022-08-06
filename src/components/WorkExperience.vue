<template>
    <div class="container pb-4">
        <h1 class="experienceText">Experience</h1>
        <div class="row">
            <div class="col-12 col-md-6 experience-img text-center d-none d-md-block">
                <img src="../assets/expOrange.c3e97320.svg" class="img-fluid" alt="">

            </div>
            <div class="col-12 col-md-6">
                <div class="row">
                    <div v-for="(exp,index) in experiences" :key="index" class="col-12">
                        <div class="div experienceDetails d-flex align-items-center justify-content-start">
                            <div class="experienceIconContainer">
                                <img src="../assets/expImgWhite.b9923db4.svg" alt="">
                            </div>
                            <div  class="ms-3">
                                <h6 class="exDate">{{exp.startDate}} - {{exp.endDate}}</h6>
                                <h4 class="exTopic">{{exp.name}}</h4>
                                <h5 class="exCompany">{{exp.company}}</h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
    </div>
</template>

<script>
    export default {
        name:'WorkExperience',
        data(){
            return{
                experiences: [
            {
                startDate: 'December, 2021',
                endDate: 'Present',
                name:'FrontEnd Software Engineer',
                company:'Kajkam Initiative',

            },
            {
                startDate: ' August, 2021',
                endDate: 'October, 2022',
                name:'Software Engineer (Intern)',
                company:'Pioneer Alpha',

            },
            {
                startDate: '2020',
                endDate: '2021',
                name:'WordPress Developer',
                company:'EkhoneShop',

            },
        ]
            }
        }
    }
</script>

<style scoped>
.experienceText{
    color: rgb(245, 101, 57);
    font-weight: 700;
    font-size: 2.7rem;
    /* font-family: 'Satisfy', cursive; */
    /* font-family: 'Dancing Script', cursive; */
    font-family: 'Permanent Marker', cursive; 
    margin: 40px 0px 30px 0px;
}
.experience-img > img {
    width: 350px;
    margin-top: 10px;
}
.experienceDetails{
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    background-color: #f565394d;
    width: 98%;
    padding: 1.5rem;
    border-radius: 20px;
    margin-bottom: 1.5rem;
}
.experienceIconContainer{
    border-radius: 50%;
    width: 55px;
    height: 55px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
    background-color: rgb(245, 101, 57);

}
.experienceIconContainer > img{
    width: 40px;
}
.exDate{
color: rgb(245, 101, 57);
}
.exTopic{
color: rgb(234, 234, 234);
}
.exCompany{
color: rgba(234, 234, 234, 0.8);
}

@media only screen and (max-width: 600px){
    .experienceText{
    text-align: center;
    }
}
</style>