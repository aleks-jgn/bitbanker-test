<template>
  <router-view />
</template>

<script lang="ts">
import HomeView from './components/HomeView.vue'
import PostView from './components/PostView.vue'
export default {
  name: 'App',
  HomeView,
  PostView
};
</script>

<style>
  html, body {
    box-sizing: border-box;
    scroll-behavior: smooth;
  }

  input, textarea {
    box-sizing: border-box;
  }

  h1, h2, p {
    text-transform: capitalize;
  }

 .content {
    width: 100%;
    max-width: 900px;
    margin: 0 auto;
    font-family: "Inter", serif;
    font-size: 15px;
    font-weight: 400;
    line-height: 1;
    text-align: left;
    text-underline-position: from-font;
    text-decoration-skip-ink: none;
  }

  .content h1 {
    font-weight: 600;
    font-size: 32px;
    margin-top: 45px;
  }

  button:disabled{
    background-color: #EEE;
    cursor: not-allowed;
    color: rgba(0, 0, 0, 0.3);
  }

  button{
    padding: 12px 18px;
    outline: none;
    background-color: #EEE;
    border: 2px solid #ccc;
    border-radius: 12px;
    color: #555;
    font-weight: 700;
    font-family: 'Roboto', sans-serif;
    cursor: pointer;
    transition: .2s;
    margin-right: 20px;
  } 

  button:disabled{
    background-color: #EEE;
    cursor: not-allowed;
    color: rgba(0, 0, 0, 0.3);
  }

  button:hover:enabled{
    color: rgba(0, 0, 0, 0.3);
  }
</style>
