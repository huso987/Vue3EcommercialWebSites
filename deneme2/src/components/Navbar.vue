<template>
      
    <section class="header-main border-bottom ">
      <section  class="container-fluid">
        <div class="row p-2 pt-3 pb-3 d-flex align-items-center" id="ata">
          <div id="r" class="col-md-2 mt-2">
            <a href="http://localhost:5173/" >
              <img class="d-none d-md-flex"  src="//cdn.shopify.com/s/files/1/0485/5264/0672/files/Aqua_di_Polo_Logo_150x167-new.png?v=1630" width="100" height="50" >
            </a>
          </div>
          <span class="col-md-8">            
            <div  class="d-flex form-inputs">
              <form  action="/search" method="get" class="aqua-search" role="search">
                <input id="s" type="hidden" name="type" value="product">
                <input id="sb" type="search" name="q" class="aqua-search-form" placeholder="    Ara.." aria-label="Search Site" autocomplete="OFF">
                  <button id="btsearch"  type="submit" class="btn icon-search">
                     <svg data-icon="search" viewBox="0 0 512 512" width="100%" height="100%">
                      <path d="M495,466.2L377.2,348.4c29.2-35.6,46.8-81.2,46.8-130.9C424,103.5,331.5,11,217.5,11C103.4,11,11,103.5,11,217.5   S103.4,424,217.5,424c49.7,0,95.2-17.5,130.8-46.7L466.1,495c8,8,20.9,8,28.9,0C503,487.1,503,474.1,495,466.2z M217.5,382.9   C126.2,382.9,52,308.7,52,217.5S126.2,52,217.5,52C308.7,52,383,126.3,383,217.5S308.7,382.9,217.5,382.9z"></path>
                    </svg> 
                  </button>
                </form>
            </div>
          </span>
          <section class="col-md-2">                     
              
            <section id="sp" style="font-size:30px;cursor:pointer" >
                  <a id="svg" href="#"  title="User Icon" class="icon-user" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight">
                    Üye Girişi          
                      <svg viewBox="0 0 32 32" width="23px" height="23px">
                        <path d="M 16 3 C 8.832031 3 3 8.832031 3 16 C 3 23.167969 8.832031 29 16 29 C 23.167969 29 29 23.167969 29 16 C 29 
                        8.832031 23.167969 3 16 3 Z M 16 5 C 22.085938 5 27 9.914063 27 16 C 27 22.085938 22.085938 27 16 27 C 9.914063 27 5 
                        22.085938 5 16 C 5 9.914063 9.914063 5 16 5 Z M 16 8 C 13.25 8 11 10.25 11 13 C 11 14.515625 11.707031 15.863281 12.78125
                        16.78125 C 10.53125 17.949219 9 20.300781 9 23 L 11 23 C 11 20.226563 13.226563 18 16 18 C 18.773438 18 21 20.226563 21 
                        23 L 23 23 C 23 20.300781 21.46875 17.949219 19.21875 16.78125 C 20.292969 15.863281 21 14.515625 21 13 C 21 10.25 18.75 
                        8 16 8 Z M 16 10 C 17.667969 10 19 11.332031 19 13 C 19 14.667969 17.667969 16 16 16 C 14.332031 16 13 14.667969 13 13 C 
                        13 11.332031 14.332031 10 16 10 Z">
                        </path>
                      </svg>         
                  </a>              
                </section>
                <section class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel">
                  <section class="offcanvas-header">
                     <h5  class="offcanvas-title" id="offcanvasRightLabel">Oturum Aç</h5>
                     <button id="butkapat" type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                  </section>
                   <div class="offcanvas-body">
                    <section class="ct-login">
                  <div class="form-group">
                    <label id="emaillabel" for="customer_email">
                      <span id="ep">
                        E-posta
                      </span>
                      <em id="yıldız1">*</em>
                    </label>
                    <input id="email" class="form-control" type="email" value="" name="customer[email]" placeholder="E-posta">
                  </div>
                  <div id="f2g" class="form-group">
                    <label for="customer_password">
                      <span  >
                        Şifre
                      </span>
                      <em id="yıldız">*</em>
                    </label>
                    <input id="pswi" class="form-control" type="password" value="" placeholder="Şifre" name="customer[password]">
                  </div>
                    <span id="login" class="action-btn">
                      <input id="üyeg" type="submit"  class="btn btn-login" value="Üye Girişi">
                        <a id="pswun" class="text-hover forgot-password" href="#">
                          Şifremi Unuttum
                        </a>
                    </span>
                    <span class="ct-register">
                      <a id="üyeol" href="#" class="btn btn-register">
                        Üye Olun
                      </a>
                    </span>
                    </section> 
                  </div>
                </section>
          </section>
        </div>
      </section>  
    </section> 
       
</template>

<style >
#offcanvasRightLabel {
  position: relative;
  left: 17px;
  top: 20px;
  font-size: 32px;
  letter-spacing: .055em;
  font-weight: 400;
  font-family: var( DM Serif Display);
  font-weight: 700;
  font-family: var(Overpass),"Arial","sans-serif"; /*bunu ara yazısı içinde uygulayabiliriz eşitlemesi için*/
}

.ct-login {
  position: relative;
  bottom: -80px;
}

body {
  font-family: "Lato", sans-serif;
  transition: background-color.5s;
}
#r {
  position: relative;  
  left: 170px;
  bottom: -1px;
}
#sb {
  position : relative;
  margin-left: 165px;
  top: 12px;
  width: 550px;
  height: 45px;
  background-color: white;
  box-shadow: 0 0 6px 4px rgb(237, 234, 234); 
  border:  2px white ;
  border-radius: 11px;
}
#sb::-webkit-input-placeholder { color : grey}
#sb::-webkit-input-placeholder{
  position: relative;
  bottom: 3px;
}
#sb:-moz-placeholder {color : rgb(128, 128, 128) }
#sb:-ms-input-placeholder { color : rgb(128, 128, 128) }
#btsearch {
  position: relative;
  width: 40px;
  height: 25px;
  left: -40px;
  top: 1px;
  border: white;
}
:root {
  color: white;
}
 
#emaillabel {
  position: relative;
  left: 20px;
  bottom: 75px;
}
#ep{
  position: relative;
  bottom: 0px;
}
#yıldız1 {
  position: relative;
  color: red;
  bottom: 3px;
}
#email {
  width: 350px;
  position: relative;
  left: 20px;
  bottom: 60px;
  height: 50px;
 
}
#f2g {
  position: relative;
  left: 20px;
  bottom: 30px;
}
#yıldız {
  position: relative;
  color: red;
  bottom: 10px;
}
#pswi {
  width: 350px;
  height: 50px;
  bottom: 10px;
  
}
#login {  
  
  position: relative;
  left: 20px;
  bottom: 5px; 
}
#üyeg {
  background-color: #293355;
  color: white;
  width: 350px;
  height: 60px;
  text-align: center;
  left: -5px;
  top: 5px;
  
  
}
#üyeg:hover{
  background-color: white;
  color: black;
}
#pswun {
  position: relative;
  bottom: 0px;
  color: black;
  left: 10px;
  font-size: small;
  position: relative;
  top: 10px;
 
}
#üyeol {
 
  position: relative;
  background-color:white;  
  color: black;
  width: 350px;
  height: 60px;
  text-decoration: none;
  text-align: center;
  left: 15px;
  top: 20px;
  box-shadow: 0 -1px 7px 1px #0003;
  
  font-size: 17px;
}
#üyeol:hover{
  background-color: #293355;
  color: white;
}
#sp{  
  position: relative;
  left: 0px;
  bottom: -10px;
}
#svg{
  position: relative;
  bottom: -11px;
  right: 45px;
  color: black;
  text-decoration: none;
  font-size: 14px;
} 
#svg:hover {
  color:black;
  text-decoration: underline
}

</style>

<script>

</script>