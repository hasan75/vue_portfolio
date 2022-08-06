<template>
    <div class="container">
        <h1 class="skillHeader">Skills</h1>
        <div class="row">
            <div v-for="(skill, index) in skills" :key="index" class="col-4 col-sm-4 col-lg-2">
                <div class="skillSet text-center">
                    <img src={{skill.link}} alt="">
                    <span class="d-block fw-bold skillText">
                        {{skill.name}}
                    </span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name:'MySkills',
        data(){
            return{
                skills: [
                    { link: 'https://hasan75portfolio.netlify.app/static/media/html.75bdf0b0.svg', name:'HTML5'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/css.afb434f6.svg', name:'CSS3'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/javascript.f84ec710.svg', name:'JavaScript'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/nodejs.3dc364b8.svg', name:'NodeJS'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/react.c3a0b34a.svg', name:'Rect JS'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/mongoDB.4428e2ce.svg', name:'Mongo DB'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/nodejs.3dc364b8.svg', name:'Express JS'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/c.e580cb17.svg', name:'C'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/cplusplus.3b0d7340.svg', name:'C++'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/bootstrap.3b3ab2cf.svg', name:'Bootstrap'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/tailwind.01daca9b.svg', name:'Tailwind'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/materialui.d7f5c38f.svg', name:'Material UI'  },
                    { icon: 'https://hasan75portfolio.netlify.app/static/media/typescript.f66836b8.svg', name:'Typescript' },
                    ]
            }
        }
    }
</script>

<style scoped>
.skillHeader{
    color: rgb(245, 101, 57);
    font-weight: 700;
    font-size: 2.7rem;
    /* font-family: 'Satisfy', cursive; */
    /* font-family: 'Dancing Script', cursive; */
    font-family: 'Permanent Marker', cursive; 
    margin: 30px 0px 20px 0px;
}
.skillSet {
    min-height: 6rem;
    margin: 10px 5px;
    padding: 10px 20px;
    border-radius: 10px;
    border: 1 px solid #FF764D;
    box-shadow: 3px 3px 2px #FF764D;
    box-shadow: #FF764D 0px 2px 5px -1px, #FF764D 0px 1px 3px -1px;
}
.skillText{
    font-size: 1.2rem;
}
</style>