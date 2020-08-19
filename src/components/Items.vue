<template>
  <!-- row of items -->
  <div class="row">
    <!-- first card -->
    <div class="card col-lg-25%">
      <img class="card-img" src="../assets/homecard.jpg" alt="Card image">
      <div class="card-body">
        <h4 class="card-title">Item one</h4>
        <p class="card-text">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Fugit laudantium dolores, est</p>
      </div>
    </div>
    <!-- second card -->
    <div class="card col-lg-25%">
      <img class="card-img" src="../assets/homecard.jpg" alt="Card image">
      <div class="card-body">
        <h4 class="card-title">Item two</h4>
        <p class="card-text">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Fugit laudantium dolores, est</p>
      </div>
    </div>
    <!-- third card -->
    <div class="card col-lg-25%">
      <img class="card-img" src="../assets/homecard.jpg" alt="Card image">
      <div class="card-body">
        <h4 class="card-title">Item three</h4>
        <p class="card-text">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Fugit laudantium dolores, est</p>
      </div>
    </div>
    <!-- fourth card -->
    <div class="card col-lg-25%">
      <img class="card-img" src="../assets/homecard.jpg" alt="Card image">
      <div class="card-body">
        <h4 class="card-title">Item four</h4>
        <p class="card-text">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Fugit laudantium dolores, est</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.row
{
  padding-left: 7%;
}
.card
{
  width: 23%;
  height: 250px;
  border: none;
}
.card-img
{
  width: 45%;
  height: 45%;
  margin-left: 27.5%;
}
.card-title
{
  text-align: center;
}
.card-text
{
  text-align: center;
}
</style>

<script>
export default {
  name: "Items",
};
</script>
