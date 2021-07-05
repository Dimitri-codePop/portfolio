<template>
  <div class="home">
    <h1 class="title"> Welcome</h1>
    <div class="blob">DM</div>
  </div>
</template>

<style scoped>

.title{
  font-size: 3rem;
  color: rgb(80, 43, 71);
}

.blob{
  background: transparent;
  position: absolute;
  top:35%;
  left:40%;
	border-radius: 50%;
	margin: 10px;
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
		transform: scale(0.55);
		box-shadow: 0 0 0 0 rgba(128, 71, 1, 0.7);
		border: 8px solid rgb(230, 126, 0, 0.3);
	}
	
	70% {
		transform: scale(1.25);
		box-shadow: 0 0 0 30px rgba(230, 126, 0, 0);
		border: 2px solid rgb(230, 126, 0, 0);

	}
	
	100% {
		transform: scale(0.55);
		box-shadow: 0 0 0 0 rgb(230, 126, 0, 0);
		border: 1px solid rgb(230, 126, 0, 1);

	}
}

</style>