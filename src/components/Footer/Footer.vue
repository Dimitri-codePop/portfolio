<template>
     <footer class="footer">
      <img src="./copyright.png" alt="copyright logo" class="copyright" />
      <div class="footer-desc">
        Copyright all rights reserved
      </div>
    </footer>
</template>


<script>

export default {
  name: 'Footer'
}

</script>


<style scoped>
 .footer {
  position: fixed;
  bottom: 20px;
  display: flex;
  align-items: center ;
}

.copyright {
  margin-right: 1.5rem;
  width: 20px;
  height: 20px;
}
</style>