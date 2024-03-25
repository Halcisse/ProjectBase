<script setup>
  import TheHeader from "@/components/TheHeader.vue"
</script>

<template>

 <TheHeader class="header"/>
 <div class="mainHome">
    <section>
      <div class="titres">
        <h1>Je suis le titre  principal de la page Home</h1>
        <h2>Je suis le titre  secondaire de la page Home</h2>
      </div>
      <div class="articleHome">
          Je suis le texte principale de la page d'accueil

          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ullamcorper placerat finibus. Maecenas volutpat sodales laoreet. Vestibulum quis facilisis purus, eget commodo odio. Aenean ac urna augue. Donec tempus euismod bibendum. Donec sed scelerisque massa. Duis quis lobortis turpis, ut fringilla nisl. Mauris a justo commodo, auctor velit malesuada, molestie leo. Donec tristique at lectus vel placerat.

Phasellus vehicula tempor ligula ut maximus. Sed malesuada, tortor vitae fringilla scelerisque, odio nulla malesuada mi, id egestas leo ipsum at urna. Curabitur sed euismod mi, eu laoreet odio. Aenean in mattis lectus. Donec rhoncus lectus sit amet dolor tristique molestie. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Nunc imperdiet leo non ex mattis ultricies. In hac habitasse platea dictumst. Mauris sit amet auctor elit. Ut imperdiet eros id ullamcorper vestibulum. Morbi quis sapien sit amet libero vulputate mattis at sit amet elit.

Etiam non arcu placerat, blandit leo nec, gravida metus. Nam varius, tortor ac venenatis luctus, neque nibh euismod est, id lobortis elit magna vitae arcu. Nulla sodales a nibh ac dapibus. Maecenas molestie elementum bibendum. Morbi quis odio vulputate, cursus risus eu, faucibus lorem. Maecenas id malesuada orci. Proin interdum turpis non nisl tincidunt pulvinar. Ut vel semper turpis, at aliquam arcu. Sed lacus diam, iaculis non lacinia id, aliquam sit amet est. Vivamus dapibus enim at sapien ullamcorper cursus nec sit amet nisi. Nam eu urna gravida, pellentesque metus quis, auctor mi. Proin at tempus libero, in aliquet risus.

Integer non feugiat sapien. Aenean dapibus magna a tristique aliquam. Curabitur ut diam eget arcu pulvinar dictum ac non augue. Nam auctor, dolor ac consequat venenatis, diam dui aliquam nisi, sed vestibulum est odio ac nisl. Integer accumsan luctus interdum. Donec consectetur mattis nisi, eget efficitur purus. Morbi mi lacus, rhoncus vitae suscipit a, imperdiet ac lacus. Vestibulum mauris sapien, fermentum vel sollicitudin in, vehicula eget nibh. Nulla cursus, erat luctus condimentum tempor, arcu augue faucibus dolor, id imperdiet nulla neque ut arcu. Nulla semper, urna et consectetur tincidunt, risus mauris ultrices dui, vitae scelerisque risus odio in augue. In eget accumsan dui. Curabitur eget augue nisi. Nam ac scelerisque eros. Praesent mattis lobortis elementum.

Praesent quis ligula lacus. Aenean placerat eget ligula ac luctus. Duis scelerisque mi nisi, et consequat turpis lacinia sed. Donec luctus consectetur elit, et vestibulum erat bibendum id. Quisque mollis mollis venenatis. Quisque consequat lacus nibh, id ornare risus suscipit id. Vestibulum fermentum consectetur nunc et bibendum. Curabitur cursus metus at justo posuere gravida. Fusce convallis eros et velit ornare, sit amet volutpat orci tempus. Fusce lorem nisi, aliquet ultrices tellus ac, lobortis mollis eros. Aliquam efficitur dignissim consectetur. Mauris eleifend non lorem quis cursus. Ut at porttitor ante. Pellentesque ac felis sagittis, convallis quam sed, vehicula turpis. Nulla sagittis ante blandit vulputate vulputate. Vivamus ac elit sodales, dignissim massa a, sagittis turpis.
      </div>
    </section>
    <aside>
      <h2>Je suis le titre des actualités</h2>
      <div class="actu">
           Je suis un article en complément de ma page 
      </div>
    </aside>
 </div>    

</template>

<style scoped>

.header{
  background: rgb(158, 158, 244);
  display: flex;
  justify-content: center;
  align-items: center;
  position: fixed;
 width: 100%;


}
.mainHome{
  display: flex;
  flex-direction:row;
}
section{
background-color: orangered;
width: 100%;
min-height: 89vh;
border-right: 1px solid black;

}
.titres{
/* background-color: aquamarine; */
display: flex;
flex-direction: column;
margin-bottom: 24px;
margin-left: 38px;

}
.articleHome{
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
margin: 0 38px;
}
aside{
background-color: rgb(42, 173, 173);
display: flex;
flex-direction: column;
}
</style>