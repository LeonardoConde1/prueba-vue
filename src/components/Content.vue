<template>
  <div class="container">
    <div class="content">
      <img class="image" src="../assets/usuario.webp" alt="foto" />
      <div class="text">
        <h1 class="text-name">Eduardo Mexia</h1>
        <div class="icons">
          <svg
            class="star"
            xmlns="http://www.w3.org/2000/svg"
            fill="yellow"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="yellow"
          >
            <path
              d="M11.48 3.499a.562.562 0 011.04 0l2.125 5.111a.563.563 0 00.475.345l5.518.442c.499.04.701.663.321.988l-4.204 3.602a.563.563 0 00-.182.557l1.285 5.385a.562.562 0 01-.84.61l-4.725-2.885a.563.563 0 00-.586 0L6.982 20.54a.562.562 0 01-.84-.61l1.285-5.386a.562.562 0 00-.182-.557l-4.204-3.602a.563.563 0 01.321-.988l5.518-.442a.563.563 0 00.475-.345L11.48 3.5z"
            />
          </svg>
          <span>3.3M </span>
          <svg
            class="star"
            xmlns="http://www.w3.org/2000/svg"
            fill="yellow"
            viewBox="0 0 576 512"
            stroke-width="1.5"
            stroke="yellow"
          >
            <path
              d="M309 106c11.4-7 19-19.7 19-34c0-22.1-17.9-40-40-40s-40 17.9-40 40c0 14.4 7.6 27 19 34L209.7 220.6c-9.1 18.2-32.7 23.4-48.6 10.7L72 160c5-6.7 8-15 8-24c0-22.1-17.9-40-40-40S0 113.9 0 136s17.9 40 40 40c.2 0 .5 0 .7 0L86.4 427.4c5.5 30.4 32 52.6 63 52.6H426.6c30.9 0 57.4-22.1 63-52.6L535.3 176c.2 0 .5 0 .7 0c22.1 0 40-17.9 40-40s-17.9-40-40-40s-40 17.9-40 40c0 9 3 17.3 8 24l-89.1 71.3c-15.9 12.7-39.5 7.5-48.6-10.7L309 106z"
            />
          </svg>
          <span> Top 5 : mejores credores de ejercicios</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
body {
  margin: 0;
  padding: 0;
}
.container {
  background-color: white;
}
.content {
  display: flex;
  height: 100px;
  margin-top: 7%;
  margin-left: 15%;
  background-color: #f1f2f4;
  border-radius: 10px;
}

.text {
  width: 100%;
  margin-left: 2%;
}
.text-name {
  margin: 0%;
  padding: 0%;
  color: #369fd1;
  font-family: "Open Sans", sans-serif;
}

.image {
  padding: 5px;
  margin-left: 50px;
  margin-top: -25px;
  border-radius: 5px;
  height: 100%;
}

.star {
  margin-right: 10px;
  margin-top: 10px;
  height: 25px;
}
.icons {
  align-items: end;
  opacity: 0.3;
  padding-left: 3%;
}
</style>
