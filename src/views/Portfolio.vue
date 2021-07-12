<template>
  <div class="portfolio">
      <h1 class="titlename">Portfolio</h1>
    <div class="container">
     <h2 class="title">JS / VueJS</h2>
        <article class="card">
          <div class="content">
            <h2>PlayrFindR</h2>
            <p>Site de mise en relation de particulier à particulier pour un instant BoardGaming</p>
             <iframe src="http://playrfindr.surge.sh/" style="background-color: transparent;" class="iframe_img">
              </iframe>
            <a href="http://playrfindr.surge.sh" class="url_site">
                Voir le site
            </a>
          </div>
        </article>
    </div>
  </div>
</template>


<style scoped>


.portfolio {
  display: flex;
  align-content: center;
  flex-direction: column;
}

.container{
  display: flex;
  flex-direction: column;
}

.title{
  margin-top: 1rem;
  text-align: center;
  font-size: 1.7em;

  font-size: 2rem;

}

.titlename{
  font-size: 1.7em;
  margin-bottom: .2em;
  text-align: center;
  font-size: 3rem;
}

.card {
  border: 1px solid #ffff;
  width: 60%;
  display: flex;
  align-self: center;

  margin-top: 1rem;
}


.content{
  text-align: center;
}

section {
  text-align: left;
}

h2{
  font-size: 2rem;
  padding: 1rem
}

.iframe_img{
  background-image: cover;
  background-position: cover cover;
  overflow: hidden;
  height: 200px;
}

.url_site{
  color: #265d77;
  display: inline-block;
  font-size: 1.2rem;
  width: auto;
  text-align: center;
  border-radius: 5px;
  padding:  0.8rem;
  margin: 1rem;
  border: 1px solid #ffffff;
}

.url_site:hover{
  transition: 0.33s ease-in;
  background-color: #ffffff;
}

p{
  margin: 1rem;
}


</style>