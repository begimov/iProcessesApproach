<template>
  <div>
    <div class="jumbotron jumbotron-fluid text-white">
      <div class="container">
        <div class="row">
          <div class="col"><img src="../assets/logo.png" class="logo" width="110"></div>
        </div>
        <h3 class="header-title">Электронная книга Александра Кочнева</h3>
        <h1 class="display-4 d-none d-sm-block text-uppercase"><strong>Как внедрить бизнес-процессы</strong></h1>
        <h1 class="display-5 d-sm-none text-uppercase">Как внедрить бизнес-процессы</h1>
      </div>
    </div>

    <div class="container">

      <div class="row mt-5">
        <div class="col-md-4 align-self-center d-none d-md-block pr-5"><img src="../assets/cover.png" class="img-fluid"></div>
        <div class="col-md-8 align-self-center">
          <div class="row">
            <div class="col">
              <h2>Получить книгу бесплатно</h2>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <Grform
                redirect="true"
                cta="ПОЛУЧИТЬ"
                campaign_token="nlgDi"
              />
            </div>
          </div>
        </div> 
      </div>
      
    </div>
  </div>
</template>

<script src="./home.js"></script>

<style scoped>
.header-title {
  margin-top: 30px;
}
.header-date {
  margin-top: 20px;
  margin-bottom: 10px;
}
.badge {
  font-size: 1.1em;
}
.last-row {
  margin-bottom: 50px;
}
h2 {
  margin-bottom: 20px;
}
.jumbotron {
  padding-top: 20px;
  background-image: url("../assets/bg.jpg");
  background-size: cover;
}
.container-fluid {
  padding: 20px 10px;
  margin-bottom: 50px;
}
.nav-tabs-links a {
  color: #fff;
  text-decoration: underline;
}
.logo {
  margin-bottom: 20px;
}
.card-accent {
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);
  border-width: 2px;
}
.mp-is-block {
  background-image: url("../assets/mp.jpg");
  background-size: cover;
  min-height: 150px;
}
.mp-is-usefull-block {
  background-image: url("../assets/usefull.jpg");
  background-size: cover;
}

@media (max-width: 767.98px) {
  .header-title {
    margin-top: 20px;
  }
}
@media (max-width: 575.98px) {
  .header-title {
    margin-top: 10px;
  }
}
</style>
