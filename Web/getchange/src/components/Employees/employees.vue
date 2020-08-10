<template>
  <div>
    <div class="contain">
      <div class="row">
        <div class="col-auto mr-auto header">
          <h5>Employees</h5>
        </div>
        <div class="col-auto">
          <button class="add__btn" data-toggle="modal" data-target="#exampleModalCenter">Add New</button>
        </div>

        <!-- Modal -->
<div class="modal fade" id="exampleModalCenter" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLongTitle">Add New Employee</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
 <form>
      <div class="login-form">
        <div class="form">
          <h2>Create your free account</h2>
          <p>
            Already registered?
            <span><a href="/">Sign in</a></span>
          </p>
          <div class="form-card">
            <div class="names">
              <div class="form-gap lastname">
                <label for="firstName">First Name</label>
                <br />
                <div class="form-field">
                  <input type="text" placeholder="Joshua" name id="firstName" />
              
                </div>
                <hr />
              </div>
              <div class="form-gap lastname">
                <label for="lastName">Last Name</label>
                <br />
                <div class="form-field">
                  <input type="text" placeholder="Bakare" name id="lastName" />
              
                </div>
                <hr />
              </div>
            </div>
            <div class="email">
              <label for="email">Email</label>
              <br />
              <div class="form-field">
                <input
                  type="email"
                  placeholder="Josh.bakery@gmail.com"
                  name
                  id="mail"
                />
               
              </div>
              <hr />
            </div>
            <div class="password">
              <label for="email">Password</label>
              <br />
              <div class="form-field">
                <input
                  type="password"
                  placeholder="*********"
                  name
                  id="password"
                />
             
              </div>
              <hr />
            </div>
            <div class="button">
              <input class="submit" type="button" value="Continue" />
            </div>
          </div>
        </div>
        <div class="footer">
          <p>
            By signing up, you agree to our
            <span><a href="#">Terms</a></span>
            and
            <span><a href="#">Privacy Policy</a></span>
          </p>
          <p>© 2019 Tinylabs. All rights reserved</p>
        </div>
      </div>
      </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Submit</button>
      </div>
    </div>
  </div>
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
// const axios = require('axios')
export default {
  name: 'employees',
  data(){
    return{
      employee:{

      }
    }
  },

  methods:{
   async addEmployee(){
     try{
       let response = await this.$http.post(
         'https://crudcrud.com/api/3058e6a8a96443e3991b50d1bca9028a'
       )
       console.log(response)
     }
     catch (error){
    console.log(error)
     }
    }
  }
}
</script>
<style scoped>
.contain {
  padding: 80px 150px 0px 150px;
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
.add__btn:focus,
.add__btn:focus,
[type='button']:focus {
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
