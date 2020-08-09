<template>
  <div>
    <div class="contain">
      <div class="row">
        <div class="col-auto mr-auto header">
          <h5>Employees</h5>
        </div>
        <div class="col-auto">
          <button class="add__btn">Add New</button>
        </div>
      </div>

      <div class="row p-3 mt-4 josh__bakery">
        <div class="col-auto mr-auto header pt-2">
          <h2>Josh Bakery Ventures</h2>
        </div>
        <div class="col-auto">
          <p class="address pt-3">62, Bode Thomas, Surulere, Lagos</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'employees',

}
</script>
<style scoped>
.contain{
    padding:80px 150px 0px 150px;
}
.header h5 {
  text-align: center;
  color: var(--primary-color);
 
  font-family: var(--main-font);
   font-size: 22px;
}
.header h2 {
  font-size: 30px;
  font-weight: 500;
color: var(--primary-color);
 
  font-family: var(--main-font);

  letter-spacing: -0.9px;
}
.add__btn {
  border-radius: 3px;
  color: white;
  background-color: var(--main-bg-color);
  border: none;
  font-size: 16px;
  padding: 7px 30px;
}
.add__btn :focus {
  outline: none;
}
.josh__bakery {
  background: white;

  border-radius: 5px;
}
.address {
  font-weight: 500;
  font-size: 16px;
  letter-spacing: -0.55px;
  color: var(--primary-color);

}
</style>
