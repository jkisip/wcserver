<template>
<div>
    <header class="py-5 bg-image-full" style="background-image: url('https://i.pinimg.com/originals/e5/e3/1b/e5e31bec5a92d24929ae5298e582e82a.jpg');">
    <p class="title">WORLD NEWS</p>
    <br>
  </header>

  <!-- Content section -->
  <section class="py-5">
    <div class="container">
      <h1>DAILY NEWS</h1>
      <p class="lead">On March 19, 2020</p>
      <p class="abc">Nunc euismod ante lectus, in commodo augue molestie eu. Quisque ut elit sed odio viverra blandit ut a erat. Curabitur tempus pharetra feugiat. Nam eu molestie lectus. Etiam ligula ex, elementum eu mollis nec, semper sed tortor. In sodales id purus ac tempus. Sed sed felis urna. Praesent vestibulum mi ut bibendum tincidunt. Ut at laoreet velit. Pellentesque quis vehicula risus. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Phasellus in arcu et dolor auctor interdum. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
      <p class="abc">Nam volutpat molestie eros a sollicitudin. Donec eu nisl posuere, auctor quam eu, consectetur ligula. Vivamus aliquet justo tortor, eu commodo tellus tristique vel. Donec tincidunt finibus orci, eget mattis nulla aliquam non. Etiam sollicitudin elit quam, ac suscipit leo congue fermentum. Fusce et nulla bibendum, varius nunc ac, semper lacus. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nullam auctor metus at libero mollis interdum. Cras mattis semper facilisis. Pellentesque bibendum dapibus leo, non aliquet diam lacinia a.</p>
      <button class="continue">Continue Reading >></button>
    </div>
  </section>

  <!-- Image Section - set the background image for the header in the line below
  <section class="py-5 bg-image-full" style="background-image: url('https://unsplash.it/1900/1080?image=1081');">
  Put anything you want here! There is just a spacer below for demo purposes!
    <div style="height: 200px;"></div> 
  </section>-->

  <!-- Content section
  <section class="py-5">
    <div class="container">
      <h1>Section Heading</h1>
      <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid, suscipit, rerum quos facilis repellat architecto commodi officia atque nemo facere eum non illo voluptatem quae delectus odit vel itaque amet.</p>
    </div>
  </section> -->
</div>

</template>

<script>
export default {
  name: 'home',
}
</script>
<style>
section{
  background-color: #8A8A8A ;
}
.abc{
  text-indent: 10%;
  text-align: justify;
}
.continue{
  background-color:lightgray;
  margin-left: 83%;
}
.title{
  font-size: 120px;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  margin-left: 31%;
  color:#A8D6FF ;
}
</style>
