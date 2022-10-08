<template>
  <div>
    <Navbar />
    <footer class="content margin-auto">
        <article style="color:aliceblue" class="text-center">
            <section>
                <span>"{{motto2}}"</span>
            </section>
            <section>
                <span>--- {{author}} ---</span>
            </section> 
            <hr>
            <div v-for="e in experiences" :key="e.title">
                <section class="title" >
                <span>{{e.title}}</span>
            </section> 
            
            <article class="skill-menu margin-auto">
                <ul class="ul-navbar">
                    <li class="menu-list">
                        <a href="index.html">{{e.subtitle}}</a>
                    </li>
                    <li class="menu-list">
                        <a href="Experiences.html">{{e.subtitle2}}</a>
                    </li>
                </ul>
            </article>
            </div>
        </article>
    </footer>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
    components: { Navbar },
    data() {
        return {
            motto2 : 'Life Is The Art Of Drawing Without And Eraser',
            author : 'John W Gardner',
            experiences :[{
                title : 'Scholarship',
                subtitle : 'ทุนเพชรในชัยพฤกษ์ 100%',
                subtitle2 : 'ทุนสหกรณ์ ประจำปี2565',
            },{
                title : 'Certificate',
                subtitle : 'BU Creative SandBox X Workpoint 2022',
                subtitle2 : 'การเเข่งขันประกวดร้านค้ากาชาดออนไลน์',
            }

            ]
        }


    }

}
</script>

<style>

</style>