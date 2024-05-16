<template>
    <div class="main-container">
      <div class="project-card" v-for="(item, index) in projectData.ProjectsArray" v-bind:key="index">
        <h2>{{ item.Title }}</h2>
        <img :src="getImageUrl(item.Image)" alt="">
        <p>{{ item.About }}</p>
      </div>
    </div>
  </template>
  
  <script>
  import jsonData from "../../projects.json";
  
  export default {
    data() {
      return {
        projectData: jsonData
      };
    },
    methods: {
      getImageUrl(image) {
        return require(`../assets/${image}`);
      }
    }
  };
  </script>
  
  <style scoped>
  .main-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
  }
  
  .project-card {
    margin: 10px;
    padding: 10px;
    flex-basis: 40%;
    background-color: white;
    border-radius: 25px;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
  }
  
  .project-card img {
    height: 20rem;
    border-radius: 50%;
  }
  </style>
  