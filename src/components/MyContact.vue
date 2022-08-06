<template>
    <div class="container">
        <div class="contacts" id="contacts">
            <h1 class="contactHeader">Contacts</h1>
            <div class="row row-cols-1 row-cols-md-2">
                <div class="col mb-3 d-flex align-items-center justify-content-center">
                    <div class="contactContainer">
                        <div class="d-flex justify-content-start align-items-center mb-3">
                    
                            <div class="iconContain">
                                <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><circle cx="12" cy="12" r="4"></circle><path d="M16 8v5a3 3 0 0 0 6 0v-1a10 10 0 1 0-3.92 7.94"></path></svg>
                            </div>
                            <p class="mt-3 ms-2">hasanjab14@gmail.com</p>
                        </div>
                        <div class="d-flex justify-content-start align-items-center mb-3">
                            <div class="iconContain">
                                <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path></svg>
                            </div>
                            <p class="mt-3 ms-2">+8801761395574</p>
                        </div>
                        <div class="d-flex justify-content-start align-items-center mb-3">
                            <div class="iconContain">
                                <svg stroke="currentColor" fill="none" stroke-width="0" viewBox="0 0 24 24" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                            </div>
                            <p class="mt-3 ms-2">Uttara, Dhaka, bangladesh</p>
                        </div>
                    </div>
                </div>
                <div class="col d-none d-md-block">
                    <img src="../assets/contactsOrange.46b295a2.svg" class="img-fluid contactImg" alt="">
                </div>
            
            </div>
            <h4 class="contactFooter">
                <span>Ⓒ</span> <span>All Right and Reserved by Hasan Ahmed</span>
            </h4>
        </div>

    </div>
</template>

<script>
    export default {
        name:'MyContact'
    }
</script>

<style scoped>
    .iconContain{
        height: 50px;
        width: 50px;
           display: flex;
    font-size: 23px;
    transition: 250ms ease-in-out;
    align-items: center;
    flex-shrink: 0;
    border-radius: 50%;
    justify-content: center;
    background-color: #f56539;
    }

        .contactHeader{
    color: rgb(245, 101, 57);
    font-weight: 700;
    font-size: 2.7rem;
    /* font-family: 'Satisfy', cursive; */
    /* font-family: 'Dancing Script', cursive; */
    font-family: 'Permanent Marker', cursive; 
    margin: 30px 0px 20px 0px;
     padding: 30px 0px;
    }
    .contactImg{
        width: 250px;
    }
    .contactFooter{
        text-align: center;
        font-size: 1.4rem;
        padding: 20px 0px;
        color: #f56539;
    }

    @media screen and (max-width: 600px){

    }
</style>