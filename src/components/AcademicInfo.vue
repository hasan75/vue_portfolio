<template>
    <div class="container pb-4">
        <h1 class="eduText">Education</h1>
        <div class="row">
            <div class="col-12 col-md-6 education-img text-center d-none d-md-block">
                <img src="../assets/eduOrange.0793a40d.svg" class="img-fluid" alt="">

            </div>
            <div class="col-12 col-md-6">
                <div class="row">
                    <div class="col-12">
                        <div class="div eduDetails d-flex align-items-center justify-content-start">
                            <div class="eduIconContainer">
                                <img src="../assets/eduImgWhite.433f9250.svg" alt="">
                            </div>
                            <div  class="ms-3">
                                <h6 class="eduDate">April 2018 - June 2022</h6>
                                <h4 class="eduTopic">B.Sc. in Computer Science and Engineering</h4>
                                <h5 class="eduInstitute">International University of Business Agriculture and Technology</h5>
                            </div>
                        </div>
                    </div>
                    <div class="col-12">
                        <div class="div eduDetails d-flex align-items-center justify-content-start">
                            <div class="eduIconContainer">
                                <img src="../assets/eduImgWhite.433f9250.svg" alt="">
                            </div>
                            <div class="ms-3">
                                <h6 class="eduDate">2014 - 2016</h6>
                                <h4 class="eduTopic">Higher Secondary Certificate</h4>
                                <h5 class="eduInstitute">Abdul Kadir Mollah City College</h5>
                            </div>
                        </div>
                    </div>
                    <div class="col-12">
                        <div class="div eduDetails d-flex align-items-center justify-content-start">
                            <div class="eduIconContainer">
                                <img src="../assets/eduImgWhite.433f9250.svg" alt="">
                            </div>
                            <div  class="ms-3">
                                <h6 class="eduDate">2005-2014</h6>
                                <h4 class="eduTopic">Secondary School Certificate(SSC)</h4>
                                <h5 class="eduInstitute">Janata Adarsha Bidyapith</h5>
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
        
    }
</script>

<style scoped>
.eduText{
    color: rgb(245, 101, 57);
    font-weight: 700;
    font-size: 2.7rem;
    /* font-family: 'Satisfy', cursive; */
    /* font-family: 'Dancing Script', cursive; */
    font-family: 'Permanent Marker', cursive; 
    margin: 40px 0px 30px 0px;
}
.education-img > img {
    width: 350px;
    margin-top: 10px;
}
.eduDetails{
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
.eduIconContainer{
    border-radius: 50%;
    width: 55px;
    height: 55px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
    background-color: rgb(245, 101, 57);

}
.eduIconContainer > img{
    width: 40px;
}
.eduDate{
color: rgb(245, 101, 57);
}
.eduTopic{
color: rgb(234, 234, 234);
}
.eduInstitute{
color: rgba(234, 234, 234, 0.8);
}

@media only screen and (max-width: 600px){
    .eduText{
    text-align: center;
    }
}
</style>