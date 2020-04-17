<template>
  <div id="app">
    <hr>
    <h2>Atom</h2>
    <hr>
    <div class="komponen">
        <text-h1 class="komponen-atom"></text-h1>
        <text-h3 class="komponen-atom"></text-h3>
        <text-biasa class="komponen-atom"></text-biasa>
        <button-kuning class="komponen-atom"></button-kuning>
        <button-merah class="komponen-atom"></button-merah>
        <button-hijau class="komponen-atom"></button-hijau>
        <inputan class="komponen-atom"></inputan>
        <url class="komponen-atom"></url>
    </div>
    <hr>
    <h2>Molekul</h2>
    <hr>
    <div class="komponen">
        <dropdown class="komponen-atom"></dropdown>
        <inputan-grup class="komponen-atom"></inputan-grup>
        <button-grup class="komponen-atom"></button-grup>
    </div>
    <hr>
    <h2>Organism</h2>
    <hr>
    <div class="komponen">
        <form-input class="komponen-atom"></form-input>
        <card class="komponen-atom"></card>
        <jumbotron class="komponen-atom"></jumbotron>
    </div>
  </div>
</template>

<script>
import ButtonKuning from './components/ButtonKuning.vue'
import ButtonHijau from './components/ButtonHijau.vue'
import ButtonMerah from './components/ButtonMerah.vue'
import TextH1 from './components/TextH1.vue'
import TextH3 from './components/TextH3.vue'
import TextBiasa from './components/TextBiasa.vue'
import Url from './components/Url.vue'
import Inputan from './components/Inputan.vue'
import Dropdown from './components/Dropdown.vue'
import InputanGrup from './components/InputanGrup.vue'
import ButtonGrup from './components/ButtonGrup.vue'
import FormInput from './components/FormInput.vue'
import Card from './components/Card.vue'
import Jumbotron from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    ButtonKuning,
    ButtonMerah,
    ButtonHijau,
    TextH1,
    TextH3,
    TextBiasa,
    Url,
    Dropdown,
    Inputan,
    InputanGrup,
    ButtonGrup,
    FormInput,
    Card,
    Jumbotron
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
  margin-top: 60px;
}

.komponen{
  width: 100%;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.komponen .komponen-atom{
  margin: 10px;
}
</style>
