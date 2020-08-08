<template>
  <div>
    <header>
      <section class="c">
        <nav class="navbar navbar-expand-lg  navbar-light">
          <a class="navbar-brand" href="#">
            <img src="../../assets/Bitmap.png" alt="Logo" />
          </a>
          <!-- <button class="navbar-toggler" style="color: lemonchiffon !important;" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button> -->

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto"></ul>

            <ul class="navbar-nav ">

              <li class="nav__holder active">
                <span class="dot"></span>
              </li>

              <li class="nav__holder active">
                <p>Hi, <span>Joshua</span></p>
              </li>
              <li class="nav-item active">
                <button
                  type="button"
                  class="btn dropdown-toggle dropdown-toggle-split"
                  data-toggle="dropdown"
                  aria-haspopup="true"
                  aria-expanded="false"
                >
                  <span class="sr-only">Toggle Dropdown</span>
                </button>
              </li>
            </ul>
          </div>
        </nav>
      </section>
    </header>
  </div>
</template>

<style scoped>
  header {
    width: 100%;
    background: #ffffff;
    border: 1px solid rgba(106, 126, 138, 0.1);
  }
  .dot {
  height: 25px;
  width: 25px;
background: #6A7E8A;
  border-radius: 50%;
  display: inline-block;
}
</style>
