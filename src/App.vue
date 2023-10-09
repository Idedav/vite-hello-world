<script>
    import Header from './components/Header.vue'
    import Footer from './components/Footer.vue'
    export default {
        name: 'App',
        components: {
            Header,
            Footer
        },
        data(){
            return{
                title: 'Main'
            }
        }
    }
</script>

<template>
    <Header/>
  <h1>{{ title }}</h1>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis suscipit ea soluta autem minima voluptatibus assumenda ipsa nam incidunt optio nemo tempore non modi veritatis temporibus, libero harum, esse velit dicta ut? Amet consequuntur fugit placeat recusandae consectetur delectus harum maiores ea odio cupiditate, iusto sunt repudiandae temporibus eum itaque numquam. Consequatur nam consectetur obcaecati. Neque soluta doloremque repellat, cupiditate deleniti aliquam eos laboriosam nemo delectus, pariatur laudantium nesciunt obcaecati ipsum atque possimus officia dolorum, aliquid consectetur ipsa maxime non reiciendis. Totam enim corrupti praesentium ex, architecto eius nihil quae ad nesciunt inventore voluptatibus laudantium est! Sit expedita fugiat vero veritatis? Obcaecati atque nisi dignissimos doloribus rem pariatur repudiandae harum impedit incidunt, dolor, ducimus quaerat veniam! Ad consectetur labore quas voluptates? Aliquam nulla voluptas excepturi tempora voluptatum expedita eaque nostrum in hic! Eligendi modi corporis omnis dolores eveniet, iure fugiat, magnam illum perspiciatis iste debitis explicabo sint atque repudiandae nostrum, dicta ab hic itaque minima unde? Magnam exercitationem modi, officiis alias dicta odit tempore nam, accusamus ducimus dolorem quas obcaecati a perferendis dolores ea explicabo aspernatur ullam! Id odio distinctio eum, quae expedita quia sapiente nemo atque eligendi illum numquam illo similique cupiditate sunt rerum ex, quaerat excepturi rem delectus.</p>
    <Footer/>
</template>


<style scoped>
    h1{
        background-color: yellow;
    }
</style>