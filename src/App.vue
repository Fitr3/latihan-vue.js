<script setup>
import { ref } from 'vue'

const msg = "Hello World"
const rawHtml = "<li>Daftar 1</li>"
const link = "https://www.youtube.com/"

let a= 10
let b= 5
let c = a+b

</script>

<template>
  <div id="app">
    <span>{{ msg }}</span><br>
    <span v-html="rawHtml"></span><br>
    <button :disabled="isButtonDisabled">Button</button><br>
    <span style="color:brown;">warna coklat</span><br>
    <a v-bind:href="link"> youtube </a>

    bil 1 = {{ a }}<br>
    bil 2 = {{ b }}<br>
    hasil bil 1 + bil 2 = {{ c }}
  </div>
</template>
