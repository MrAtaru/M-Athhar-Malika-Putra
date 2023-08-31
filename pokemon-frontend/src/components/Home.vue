<template>
  <div class="">
    <div class="card grid md:grid-cols-4 gap-8">
      <div class="bg dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-2xl p-8 md:p-12">
        <p
          href="#"
          class="text-md font-medium inline-flex items-center px-2.5 py-0.5 dark:bg-gray-700 dark:text-green-400 mb-2"
        >
          #1
        </p>
        <img src="" class="pokemon-image" alt="pokemon image" />
        <div class="name">
          <p>Pokemon name</p>
        </div>
        <div class="type">
          <p>type</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.bg{
  background-color: white;
}
.card {
  margin: auto;
  align-items: center;
  margin-top: 2%;
  margin-left: 8%;
}
.pokemon-image {
  width: auto;
  height: 270px;
  border: 1px solid;
  border-radius: 5px;
}
.type {
  background-color: lightgray;
  width: 80px;
  text-align: center;
  margin-top: 5%;
  border-radius: 5px;
}
.name {
  color: #E51C23;
text-align: center;
font-family: Noto Sans;
font-size: 23.064px;
font-style: normal;
font-weight: 600;
line-height: normal;
text-transform: capitalize;
}

</style>
