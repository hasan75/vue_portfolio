<template>
    <div class="container pb-4" id="projects">
        <h1 class="ProjectHeader">Projects</h1>
        <div class="row row-cols-1 row-cols-sm-1 row-cols-md-3 g-3 text-dark fw-bold">
            <div v-for="project in projects" :key="project.name" class="col">
                <div class="card h-100">
                    <img :src="project.picture" class="card-img-top" alt="project">
                    <div class="card-body">
                        <h5 class="card-title">{{project.name}}</h5>
                        <p class="card-text">{{project.details}}</p>
                    </div>
                    <div class="card-footer">
                        <div class="buttonContainer d-flex justify-content-between">
                            <a :href="project.liveLink" target="_blank" rel="noreferrer">
                                <button class="custom-button">Live Site</button>
                            </a>
                            <a :href="project.github">
                                  <button class="custom-button">Github Link</button>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        name:"MyProjects",
        data(){
            return{
                projects: [
                    {
                        name:'Pran RFL',
                        liveLink:'https://pran-rfl-react.web.app/',
                        github:'https://github.com/hasan75/pran-rfl-website-client',
                        details:
                            'An e-commerce website where user can login,register and surfe the products. User can book,buy product, give reviews. Admin can manage products,reviews,orders'
                        ,
                        picture:'https://i.ibb.co/JFHvzsy/pranrfl1.png',
                        picture2:'https://i.ibb.co/Xjyz0cs/Pran-RFL-Group-4.png',
                        picture3:'https://i.ibb.co/nQStGZC/Pran-RFL-Group-2.png',
                        technologies:[
                            'React Js','MongoDB','FireBase','Express JS', 'Bootstrap', 'Module CSS',
                            'Css', 'JavaScript','React Router'
                        ]
                    },
                    {
                        name:'Tourism Hit The Trail',
                        liveLink:'https://tourism-htt.web.app/',
                        github:'https://github.com/hasan75/tourism_htt_client',
                        details:
                            'An Travel website where user can login,register and surfe the packages. User can book,buy packages, give reviews. Admin can manage packages,reviews,orders'
                        ,
                        picture:'https://i.ibb.co/8DChnmq/hit-The-Trail.png',
                        picture2:'https://i.ibb.co/Xjyz0cs/Pran-RFL-Group-4.png',
                        picture3:'https://i.ibb.co/nQStGZC/Pran-RFL-Group-2.png',
                        technologies:[
                            'React Js','MongoDB','FireBase','Express JS', 'Bootstrap', 'Module CSS',
                            'Css', 'JavaScript','React Router'
                        ]
                    },
                    {
                        name:'Shafa Care Plus',
                        liveLink:'https://shafa-care-plus-firebase.web.app/',
                        github:'https://github.com/hasan75/shafa-care-plus-healthcare-web',
                        details:
                            'An health carew website where user can login,register and surfe the health packages. User can book,buy packages, give reviews. Admin can manage packages,reviews,orders'
                        ,
                        picture:'https://i.ibb.co/JFHvzsy/pranrfl1.png',
                        picture2:'https://i.ibb.co/Xjyz0cs/Pran-RFL-Group-4.png',
                        picture3:'https://i.ibb.co/nQStGZC/Pran-RFL-Group-2.png',
                        technologies:[
                            'React Js','MongoDB','FireBase','Express JS', 'Bootstrap', 'Module CSS',
                            'Css', 'JavaScript','React Router'
                        ]
                    },
                    {
                        name:'KajKam Initiative Website',
                        liveLink:'https://kajkaminitiative.com/',
                        github:'https://github.com/hasan75',
                        details:
                            'Official static website for KajKam Initiative'
                        ,
                        picture:'https://i.ibb.co/ryf1m2T/kajkam1.png',
                        picture2:'https://i.ibb.co/Xjyz0cs/Pran-RFL-Group-4.png',
                        picture3:'https://i.ibb.co/nQStGZC/Pran-RFL-Group-2.png',
                        technologies:[
                            'React Js','MongoDB','FireBase','Express JS', 'Bootstrap', 'Module CSS',
                            'Css', 'JavaScript','React Router'
                        ]
                    },
                    {
                        name:'Honda CBR',
                        liveLink:'https://hasan75portfolio.netlify.app/projects/honda-cbr-hasan.netlify.app/',
                        github:'https://github.com/hasan75/honda_cbr_bootstrap_website',
                        details:
                            'An static website to practive responsiveness'
                        ,
                        picture:'https://i.postimg.cc/CLJ5z0rn/Honda-Web-1.png',
                        picture2:'https://i.ibb.co/Xjyz0cs/Pran-RFL-Group-4.png',
                        picture3:'https://i.ibb.co/nQStGZC/Pran-RFL-Group-2.png',
                        technologies:[
                            'HTML','Css', 'JavaScript','Bootstrap'
                        ]
                    },
                    {
                        name:'Hit The Trail',
                        liveLink:'https://hit-the-trail-react.web.app/',
                        github:'https://github.com/hasan75/hit-the-trail-website-client',
                        details:
                            'An e-commerce website where user can login,register and surfe the products. User can book,buy product, give reviews. Admin can manage products,reviews,orders'
                        ,
                        picture:'https://i.postimg.cc/j25HJ2XC/Hit-The-Trail.png',
                        picture2:'https://i.ibb.co/Xjyz0cs/Pran-RFL-Group-4.png',
                        picture3:'https://i.ibb.co/nQStGZC/Pran-RFL-Group-2.png',
                        technologies:[
                            'React Js','MongoDB','FireBase','Express JS', 'Bootstrap', 'Module CSS',
                            'Css', 'JavaScript','React Router'
                        ]
                    }
                ]
            }
        }
    }
</script>

<style scoped>
    .ProjectHeader{
    color: rgb(245, 101, 57);
    font-weight: 700;
    font-size: 2.7rem;
    /* font-family: 'Satisfy', cursive; */
    /* font-family: 'Dancing Script', cursive; */
    font-family: 'Permanent Marker', cursive; 
    margin: 30px 0px 20px 0px;
     padding: 30px 0px;
    }
        .custom-button{
        border: 2px solid #ff774d31;
        color: white;
        border-radius: 20px;
        margin: 0px 10px;
        padding: 5px 20px !important;
        background-color: black;
    }
    .custom-button:hover{
        border: 2px solid #FF764D;
        color: white;
        border-radius: 20px;
        margin: 0px 10px;
        padding: 5px 20px !important;
        background-color: #FF764D;
    }
</style>