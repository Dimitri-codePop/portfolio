<template>
  <div class="about">
  <h1 class="titlename">Mes Compétences</h1>
    <section class="personnal">
      <h2 class="title">Front :</h2>
      <ul class="personnals">
        <li class="list">Html</li>
        <li class="list">CSS</li>
        <li class="list">Javascript</li>
        <li class="list">VueJs</li>
      </ul>
    </section>
    <section class="personnal">
      <h2 class="title">Back :</h2>
      <ul class="personnals">
        <li class="list">NodeJs</li>
        <li class="list">Express</li>
        <li class="list">Graphql</li>
        <li class="list">Redis</li>
        <li class="list">Sequelize</li>
        <li class="list">Sqitch</li>
        <li class="list">PostgresQL</li>
        <li class="list">Mongodb</li>
        <li class="list">Mocha</li>
        <li class="list">Chai</li>
      </ul>
    </section>
    <section class="personnal">
      <h2 class="title"> Autre :</h2>
      <ul class="personnals">
        <li class="list">Github</li>
        <li class="list">Git</li>
        <li class="list">Docker</li>
        <li class="list">Linux</li>
        <li class="list">Heroku</li>
        <li class="list">AWS: RDS/EC2</li>
      </ul>
    </section>
  </div>
</template>

<style scoped>

.about{
  top: 200px;
  display: flex;
  flex-direction: column;
  align-content: center;
}

.titlename{
  margin-bottom: 2rem;
  font-size: 2rem;
  color: #265d77 ;
  text-align: center;
}

.title{
  font-size: 1.5rem;
  color: #265d77;
}

.personnals{
  display: flex;
} 

.personnal {
  margin: 1rem;
  border: 2px solid #265d77;
  padding: 1rem;
}

.list{
  top: 0.5rem;
  margin: 0.6rem;
}

</style>