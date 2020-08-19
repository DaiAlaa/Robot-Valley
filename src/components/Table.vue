<template>
  <div>
    <table>
      <tr class="table-head">
        <th>Features</th>
        <th>Enterprice</th>
        <th>Enterprice</th>
        <th>Enterprice</th>
        <th>Enterprice</th>
      </tr>
      <tr class="first-row">
        <td>COMPARE PACKAGE FEATURES</td>
        <td class="cell-99">$99.99</td>
        <td class="cell-99">$99.99</td>
        <td class="cell-99">$99.99</td>
        <td class="cell-99">$99.99</td>
      </tr>
      <tr class="rest-rows">
        <td>An awesome description</td>
        <td>icon</td>
        <td>icon</td>
        <td>icon</td>
      </tr>
      <tr class="rest-rows">
        <td>42 Rad Features</td>
        <td>icon</td>
        <td>icon</td>
        <td>icon</td>
        <td>icon</td>
      </tr>
      <tr class="rest-rows">
        <td>7GB of power</td>
        <td>icon</td>
        <td>icon</td>
        <td>icon</td>
        <td>icon</td>
      </tr>
      <!-- row of buttons -->
      <tr class="rest-rows">
        <td>
          <button class="buy-button">Buy Now</button>
        </td>
        <td>
          <button class="buy-button">Buy Now</button>
        </td>
        <td>
          <button class="buy-button">Buy Now</button>
        </td>
        <td>
          <button class="buy-button">Buy Now</button>
        </td>
        <td>
          <button class="buy-button">Buy Now</button>
        </td>
      </tr>
    </table>
  </div>
</template>

<style scoped>
table 
{
  width: 96%;
  margin-left: 2%;
  margin-bottom: 2%;
}
.table-head 
{
  background-color: black;
  color: white;
  text-align: center;
  height: 40px;
}
.first-row 
{
  text-align: center;
  background-color: lightgrey;
  height: 55px;
}
.cell-99 
{
  font-size: 30px;
}
.rest-rows 
{
  text-align: center;
  height: 50px;
}
.buy-button 
{
  background-color: rgb(109, 109, 235);
  color: white;
  border: none;
  width: 50%;
  height: 30px;
}
table,
th 
{
  border: 1px solid lightgrey;
}
td 
{
  border-top: 1px dashed lightgrey;
  border-bottom: 1px dashed lightgrey;
  border-left: 1px solid lightgrey;
  border-right: 1px solid lightgrey;
}
</style>

<script>
export default {
    name: "Table"
};
</script>
