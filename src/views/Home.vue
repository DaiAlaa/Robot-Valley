<template>
  <div class="home">
    <h1>First Title</h1>
    <p id="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam similique consequuntur sapiente, sequi recusandae quis dolorum exercitationem. Eius, deserunt? Cum, tempora? Ipsum, enim in est incidunt labore facilis impedit deleniti.</p>
    <!-- the items component -->
    <Items/>
    <h2>Second Title</h2>
    <!-- the table component-->
    <Table/>
    <p>* Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima aliquam officiis porro sit sequi aperiam, fugit deserunt adipisci.</p>
    <p>* Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima aliquam officiis porro sit sequi aperiam, fugit deserunt adipisci.</p>
  </div>
</template>

<style scoped>
h1
{
  text-align: center;
  font-size: 35px;
}
#description
{
  text-align: center;
  padding-left: 12%;
  padding-right: 12%;
  margin-bottom: 50px;
}
h2 
{
  text-align: center;
  font-size: 35px;
  font-weight: bold;
  margin-top: 4%;
  margin-bottom: 4%;
}
p 
{
  padding-left: 5%;
}
</style>

<script>
// @ is an alias to /src
import Items from "@/components/Items.vue";
import Table from "@/components/Table.vue";

export default {
  name: "Home",
  components: {
    Items,
    Table
  }
};
</script>
