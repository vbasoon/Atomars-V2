<template>
<div class="wrapper">
  <Header/>
    <Nuxt />
  <Footer/>
</div>
  
</template>

<style lang="scss">

$bgColor: #f5f5f7;
$paddingMain: 20px;
$marginMain: 20px;

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "IBM Plex Sans", sans-serif;
  letter-spacing: -0.005em;
}

.wrapper {
  max-width: 480px;
  height: auto;
  margin: 0 auto;
  background: #f5f5f7;
  outline: 1px solid black;
}

h3 {
  font-size: 18px;
  font-weight: 400;
}

h4 {
  font-size: 16px;
  font-weight: 400;
  margin-bottom: 15px;
}
</style>
