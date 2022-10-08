<template>
  <div>
   <Navbar />
    <!---article-->
    <main class="content margin-auto">
        <article class="artical">
            <section class="text-center title">
                <h1>Abilities</h1>
            </section>
             
            <section class="row-50 bg-white left">
                <table class="table-cute">
                    <tr>
                        <td>HTML</td>
                        <!--Emoji Windows: WIN+. or WIN+; | MAC: ^+Command+space-->
                        <td>🌱🌱</td>
                    </tr>
                    <tr>
                        <td>Canva</td>
                        <td>🌱🌱🌱🌱</td>
                    </tr>
                    <tr>
                        <td>English Communication</td>
                        <td>🌱🌱🌱🌱</td>
                    </tr>      
                    <tr>
                        <td>Photography</td>
                        <td>🌱🌱🌱</td>
                    </tr>    
                </table> 
            </section>
            <section class="row-50 bg-red left">
                <table class="table-cute">
                    <tr>
                        <td>Drawing</td>
                        <td>🌱🌱🌱</td>
                    </tr>
                    <tr>
                        <td>Singing</td>
                        <td>🌱🌱🌱</td>
                    </tr>
                    <tr>
                        <td>IMovie</td>
                        <td>🌱🌱🌱</td>
                    </tr>      
                    <tr>
                        <td>Computer Graphics</td>
                        <td>🌱🌱🌱</td>
                    </tr>    
                </table>
            </section>
        </article>
    </main>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
    components: { Navbar },

}
</script>

<style>

</style>