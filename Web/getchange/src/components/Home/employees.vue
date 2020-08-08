<template>
  <div>
    <gnav></gnav>
    <sidebar></sidebar>

    <div class="contain">
      <div class="row">
        <div class="col-auto mr-auto header">
          <h5>Employees</h5>
        </div>
        <div class="col-auto">
          <button class="add__btn">Add New</button>
        </div>
      </div>

      <div class="row mt-4 josh__bakery p-3">
        <div class="col-auto mr-auto header">
          <h2>Josh Bakery Ventures</h2>
        </div>
        <div class="col-auto">
          <p class="address">62, Bode Thomas, Surulere, Lagos</p>
        </div>
      </div>

      <div class="row mt-5">
        <div class="col-auto mr-auto header">
          <h5>Employees</h5>
        </div>
        <div class="col-auto">
          <button class="add__btn">Add New</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import gnav from '../Partials/navbar'
import sidebar from '../Partials/sidebar'
export default {
  name: 'employees',
  components: {
    gnav,
    sidebar,
  },
}
</script>
<style scoped>
.contain{
    padding:80px 150px
}
.header h5 {
  text-align: center;
  color: #013c61;
  font-size: 24px;
  font-family: 'Roboto', sans-serif;
}
.header h2 {
  font-size: 32px;
  font-weight: 500;
  font-family: 'Roboto', sans-serif;

  letter-spacing: -0.9px;
}
.add__btn {
  border-radius: 3px;
  color: white;
  background-color: var(--main-bg-color);
  border: none;
  font-size: 16px;
  padding: 10px 40px;
}
.add__btn :focus {
  outline: none;
}
.josh__bakery {
  background: white;
  border-radius: 5px;
}
.address {
  font-weight: normal;
  font-size: 20px;
  letter-spacing: -0.55px;
  color: #013c61;

}
</style>
