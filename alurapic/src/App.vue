<template>
  <div>
    <h1>{{titulo}}</h1>
    <ul>
      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo"> 
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return{
      titulo: 'Alurapic _',
      fotos: [
        { 
          url: 'https://abrilsuperinteressante.files.wordpress.com/2018/05/filhotes-de-cachorro-alcanc3a7am-o-c3a1pice-de-fofura-com-8-semanas1.png',
          titulo: 'cachorro'
        },
        { 
          url: 'https://abrilsuperinteressante.files.wordpress.com/2018/05/filhotes-de-cachorro-alcanc3a7am-o-c3a1pice-de-fofura-com-8-semanas1.png',
          titulo: 'cachorrão'
        }
      ]
    }
  }
}
</script>

<style>
</style>
