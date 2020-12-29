<template>
     <div id="tope">
    <!--
      https://getbootstrap.com/docs/4.0/components/navbar/
      https://getbootstrap.com/docs/4.0/getting-started/introduction/
    -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <a class="navbar-brand" href="https://unam.mx" target="_blank"><img src='/logo.png' width="64px;" /></a>

      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#" @click="goHome"><b>¿En qué te ayudo?</b> <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#" @click="goList">Inicio</a>
          </li>

          <li class="nav-item">
           <a class="nav-link" href="#" @click="goList">Preguntas</a>
          </li>
        </ul>

      </div>

    </nav>
  </div>
</template>

<script>
    export default {

    }
</script>

<style>
header {
background-color: darkgrey;
padding: 10 px;
height: 50px;
text-align: center;
color: #ffffff;
}
</style>