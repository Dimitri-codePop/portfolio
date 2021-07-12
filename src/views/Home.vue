<template>
  <div class="home">
    <h1 class="title"> Welcome</h1>
    <div class="animation">DM</div>
  </div>
</template>

<style scoped>

.title{
  font-size: 3rem;
  color: #265d77;
  margin-top: 2rem;
  text-align: center;
}

.animation{
  	background: transparent;
  	position: absolute;
  	top:35%;
  	left:40%;
	border-radius: 50%;
	height: 400px;
	width: 400px; 
	transform: scale(1);
	font-size: 150px;
	display: flex;
  	justify-content: center;
	align-items: center;
    animation: pulse-black 3s infinite;
} 

@keyframes pulse-black {
	0% {
		transform: scale(0.95);
		border: 8px solid #e9e8e7;
	}
	
	70% {
		transform: scale(1.05);
		border: 2px solid #F9E4E3;

	}
	
	100% {
		transform: scale(0.95);
		border: 1px solid #837b6f;
	}
}

</style>

