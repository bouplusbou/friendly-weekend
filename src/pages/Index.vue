<template>
  <div class="bg-blue-100">
    <h1 class="text-center">Friendly Weekend</h1>
    <section class="p-16">
      <div class="text-center w-2/4 m-auto">
        <p>Si vous lisez ce message, c’est qu’on vous aime très fort, vous êtes comme notre famille.</p>
        <p>Nous nous sommes rendus compte que nous ne prenions pas assez le temps de partager des moments ensemble. Pourtant, ils sont si précieux à nos yeux.</p>
        <p>Alors pourquoi attenderions-nous l’occasion d’un mariage pour rassembler les gens qu’on aime ?</p>
        <p>Puisqu’il faut une bonne raison, nos 2 ans de PACS feront l’affaire !</p>
        <p>Venez prendre une bouffée d’amitié, le temps d’un week-end avec nous.</p>
      </div>
    </section>
    <section class="bg-white p-16 text-center">
<h2 class="text-center font-title">Le lieu</h2>
<p>A 1 heure de Bordeaux, et 5 heures de Paris en train se cache un vrai paradis. 
Nous avons hâte de vous y accueillir !</p>
<p>Quelques  photos prisent durant nos derniers séjours. </p>
    <div class="gallery">
      <img src="../assets/image2.jpg" 
      class="tile" id="image2" />
      <img src="../assets/image3.jpg" class="tile" id="image3" />
      <img src="../assets/image4.jpg" class="tile" id="image4" />
      <img src="../assets/image5.jpg" class="tile" id="image5" />
      <img src="../assets/image6.jpg" class="tile" id="image6" />
      <img src="../assets/image7.jpg" class="tile" id="image7" />
    </div>
    </section>
    <section class="p-16 text-center">
  <h2>Activités</h2>
  <p>Plage</p>
  <p>Piscine</p>
  <p>Olympiades</p>
  <p>Aperos</p>
  <p>Bouee tractee</p>
  <p>Jeux de societe</p>
  <p>Surf</p>
  <p>Yoga</p>
  <p>Tennis</p>
  <p>Balade a velo</p>
  <p>Ping-Pong</p>

    </section>
  <section class="p-16 text-center">
    <h2>Quand</h2>
    
    <p>Week-end prolongé de l’Ascension, 
du jeudi 21 au dimanche 24 mai 2020.</p>
<p>Ajouter à mon calendrier</p>
  </section>
  <section class="bg-yellow-400 p-16 text-center">
    <h2>Next steps</h2>
    <p>Il ne vous reste plus qu’à nous confirmer votre venue, si possible avant le 15 décembre 2019.</p>
    <p>Pour les plus hésitants, dites-vous que c’est tout comme un mariage, vous ne voudriez pas rater ça ! </p>
  </section>
  </div>

</template>

<script>
export default {};
</script>

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr);



  
  grid-template-rows: 300px 300px 300px;
  grid-gap: 5px;
}
.tile {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
#image2 {
  grid-column-start: 1;
  grid-column-end: 3;
}
</style>