<template>
        <nav class="navbar navbar-expand-lg navbar-light bg-light" style="background-color: rgba(106, 130, 155, 0.5) !important">
      <a class="navbar-brand"><b>Сервис для управления сведениями о клиентах и их заказами</b></a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">      
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="/#/client">Клиенты</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="/#/app">Товары</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="/#/service">Услуги</a>
          </li>
        </ul>
      </div>
    </nav>
</template>

<script>
  import axios from 'axios'
    export default {
        data() 
        {
          return {

          }
        },       
        mounted() {         
        },
        methods:{
 
        }
    }
</script>