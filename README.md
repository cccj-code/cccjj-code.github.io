# cccjj-code.github.io
es mi pagina
<!DOCTYPE html>
<html>
<title>MECANICA</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Oswald">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open Sans">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
h1,h2,h3,h4,h5,h6 {font-family: "Oswald"}
body {font-family: "Open Sans"}
</style>
<body class="w3-light-grey">

<!-- Navigation bar with social media icons -->
<div class="w3-bar w3-black w3-hide-small">
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-facebook-official"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-instagram"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-snapchat"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-flickr"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-twitter"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-linkedin"></i></a>
  <a href="#" class="w3-bar-item w3-button w3-right"><i class="fa fa-search"></i></a>
</div>
  
<!-- w3-content defines a container for fixed size centered content, 
and is wrapped around the whole page content, except for the footer in this example -->
<div class="w3-content" style="max-width:1600px">

  <!-- Header -->
  <header class="w3-container w3-center w3-padding-48 w3-white">
    <h1 class="w3-xxxlarge"><b>MECHANIC SERVICE</b></h1>
    <h6>EL ALIADO DE TU  <span class="w3-tag">CAMINO</span></h6>
  </header>

  <!-- Image header -->
  <header class="w3-display-container w3-wide" id="home">
    <img class="w3-image" src="velo.jpeg" alt="Fashion Blog" width="1600" height="1060">
    <div class="w3-display-left w3-padding-large">
      <h1 class="w3-text-white">.</h1>
      <h1 class="w3-jumbo w3-text-white w3-hide-small"><b>REGISTRATE CON NOSOTROS</b></h1>
      <h6><button class="w3-button w3-white w3-padding-large w3-large w3-opacity w3-hover-opacity-off" onclick="document.getElementById('subscribe').style.display='block'">REGISTRATE Y OBTEN BENEFICIOS</button></h6>
    </div>
  </header>

  <!-- Grid -->
  <div class="w3-row w3-padding w3-border">

    <!-- Blog entries -->
    <div class="w3-col l8 s12">
    
      <!-- Blog entry -->
      <div class="w3-container w3-white w3-margin w3-padding-large">
        <div class="w3-center">
          <h3>¿QUIENES SOMOS?</h3>
          <h5> <span class="w3-opacity">JULIO,07,2021</span></h5>
        </div>

        <div class="w3-justify">
          <img src="herra.jpeg" alt="Girl Hat" style="width:60%" class="w3-padding-16">
          <p><strong>EN MECHANIC SERVICE!</strong> BRINDAMOS LOS MEJORES SERVICIOS AUTOMOTRICES DESDE CHOQUES HASTA CAMBIOS DE NEUMATICOS,SOMOS UNA EMPRESA INDEPENDIENTE PARA VEHICULOS DE CUALQUIER MARCA,MODELO Y SOBRE TODO OFRECEMOS NUESTROS SERVICIOS ENGRAN PARTE DE MORELOS,CUMPLIENDO LOS NIVELES  DE CALIDAD DEL SECTOR.NUESTRA META ES OFRECER  EL MEJOR SERVICIO PARA SU VEHICULO,HAREMOS LO NECESARIO PARA GANARNOS SU CONFIANZA Y SER ALAIDO DE TU CAMINO  </p>
          <p></p>
          <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
          <p class="w3-right"><button class="w3-button w3-black" onclick="myFunction('demo1')" id="myBtn"><b>FUNDADORES </b> <span class="w3-tag w3-white">1</span></button></p>
          <p class="w3-clear"></p>
          <div class="w3-row w3-margin-bottom" id="demo1" style="display:none">
            <hr>
              <div class="w3-col l2 m3">
                <img src="fa.jpeg" style="width:80px;"><p>JESUS FARELAS</P>
                <img src="ca.jpeg" style="width:80px;"><P>CRISTIAN CARMONA</P>
                <img src="gre.jpeg" style="width:80px;"><P>GRECIAS GARCIA</P>
                <img src="ale.jpeg" style="width:80px;"><P>ALEJANDRA RAMIREZ</p>
              </div>
              <div class="w3-col l10 m9"><P>
                <h4>FUNDADORES DE MECHANIC SERVICE<span class="w3-opacity w3-medium"></span></h4>
                 <p></P>>
              </div>
          </div>
        </div>
      </div>
      <hr>



      <div class="w3-container w3-white w3-margin w3-padding-large">
        <div class="w3-center">
          
          
          <!-- Example of comment field -->
          <div id="demo2" style="display:none">
            <div class="w3-row">
              <hr>
              <div class="w3-col l2 m3">
                <img src="/w3images/girl_train.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>Amber <span class="w3-opacity w3-medium">April 26, 2015, 10:52 PM</span></h4>
                <p>Love your blog page! Simply the best! Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p><br>
              </div>
            </div>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="/w3images/girl.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>Angie <span class="w3-opacity w3-medium">April 23, 2015, 9:12 PM</span></h4>
                <p>Love hats!!</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Blog entry -->
      <div class="w3-container w3-white w3-margin w3-padding-large">
        <div class="w3-center">
         
          
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
video {
  width: 100%;
  height: auto;
}
</style>
</head>
<body>

<video width="400" controls>
  <source src="666.mp4" type="video/mp4">
  <source src="666.mp4" type="video/ogg">
  Your browser does not support HTML5 video.
</video>

<p>Resize the browser window to see how the size of the video player will scale.</p>

</body>
</html>

          
          <!-- Example of comment field -->
          <div id="demo3" style="display:none">
            <hr>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="/w3images/girl_mountain.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>Jane <span class="w3-opacity w3-medium">April 10, 2015, 7:22 PM</span></h4>
                <p>That was a great runway show! Thanks for everything.</p>
              </div>
            </div>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="/w3images/boy.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>John <span class="w3-opacity w3-medium">April 8, 2015, 10:32 PM</span></h4>
                <p>Keep up the GREAT work! I am cheering for you!! Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
              </div>
            </div>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="/w3images/girl_hood.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>Anja <span class="w3-opacity w3-medium">April 7, 2015, 9:12 PM</span></h4>
                <p>Cant wait for the runway to start!</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      
    <!-- END BLOG ENTRIES -->
    </div>

    <!-- About/Information menu -->
    <div class="w3-col l4">
      <!-- About Card -->
      <div class="w3-white w3-margin">
        
        <div class="w3-container w3-black">
          <h4></h4>
          <div class="w3-container w3-light-grey" style="padding:18px 16px" id="contact">
  <h3 class="w3-center">CONTACTO</h3>
  <p class="w3-center w3-large">MANTENGAMONOS EN CONTACTO,MANDANOS UN MENSAJE:</p>
  <div style="margin-top:48px">
    <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> EMILIANO ZAPATA</p>
    <p><i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i> TELEFONO:4432160424</p>
    <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> EMAIL:MECHANICSER.@GMAIL.COM</p><BR>
          <p>NUESTRA GARANTIA ES SU SATISFACCION  
           </p>
        </div>
      </div>
      <hr>

      <!-- Posts -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>SERVICIOS FRECUENTES</h4>
        </div>
        <ul class="w3-ul w3-hoverable w3-white">
          <li class="w3-padding-16">
            <img src="COLI.jpg" alt="Image" class="w3-left w3-margin-right" style="width:230px">
            <span class="w3-large">REPARACION DE DAÑOS POR COLISION</span>
            <br>
            
          </li>
          <li class="w3-padding-16">
            <img src="ASI.jpg" alt="Image" class="w3-left w3-margin-right" style="width:230px">
            <span class="w3-large">ASISTENCIA EN CARRETERA URGENTE</span>
           
          </li>
          <li class="w3-padding-16">
            <img src="NEU.jpg" alt="Image" class="w3-left w3-margin-right" style="width:230px">
            <span class="w3-large">CAMBIO DE NEUMATICOS</span>
            <br>
            
          
          </li>
        </ul>
      </div>
      <hr>

      <!-- Advertising -->
      <div class="w3-white w3-margin">
      
      <hr>
      
      <!-- Subscribe -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>¿EN QUE TE AYUDAMOS?</h4>
        </div>
        <div class="w3-container w3-white">
          <p>.</p>
          <p><input class="w3-input w3-border" type="text" placeholder="NOMBRES" style="width:100%"></p>
          <p><input class="w3-input w3-border" type="text" placeholder="TELEFONO" style="width:100%"></p>
          <p><input class="w3-input w3-border" type="text" placeholder="ASUNTO" style="width:100%"></p>
          <p><input class="w3-input w3-border" type="text" placeholder="UBICACION" style="width:100%"></p>
          <p><input class="w3-input w3-border" type="text" placeholder="MENSAJE" style="width:100%"></p>
          <p><button type="button" onclick="document.getElementById('subscribe').style.display='block'" class="w3-button w3-block w3-red">¡ENVIAR!</button></p>
        </div>
      </div>
      <hr>

      <!-- Tags -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>OTROS SERVICIOS</h4>
        </div>
        <div class="w3-container w3-white">
          <p>
            <span class="w3-tag w3-black w3-margin-bottom">¿QUE NECESITAS?</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">REVISION DE FRENOS </span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">CAMBIO DE RIN</span>
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">SIN GASOLINA</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">SUSPENSIONES</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">GRUA</span>
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom"></span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom"></span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">CALENTAMIENTO DE MOTOR</span>
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">CAMBIO DE NEUMATICO</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">CAMBIO DE ACEITE</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">LLANTA PONCHADA</span>
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">FILTRO DE ACEITE</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">OTROS</span>
          </p>
        </div>
      </div>
      <hr>

      <!-- Inspiration -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>Inspiration</h4>
        </div>
        <div class="w3-row-padding w3-white">
          <div class="w3-col s6">
            <p><img src="/w3images/jeans.jpg" alt="Jeans" style="width:100%"></p>
            <p><img src="/w3images/team1.jpg" alt="Jeans" style="width:100%"></p>
          </div>
          <div class="w3-col s6">
            <p><img src="/w3images/avatar_hat.jpg" alt="Men in Hats" style="width:100%" class="w3-grayscale"></p>
            <p><img src="/w3images/team4.jpg" alt="Jeans" style="width:100%"></p>
         </div>
        </div>
      </div>
      <hr>
<CENTER>
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>HORARIOS</h4>
          <H4>VISITANOS</H4>
        </div>
       <CENTER>
          <H4>LUNES A DOMINGO</H4>
          <H4>LAS 24 HORAS DEL DIA</H4>
          <H4>LOS 7 DIAS DE LA SEMANA</H4>
        </div>
      </div>
      <hr>
      
      <!-- Subscribe -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>REGISTRAR</h4>
        </div>
        <div class="w3-container w3-white">
          <p>.</p>
          <p><input class="w3-input w3-border" type="text" placeholder="NOMBRES(S)" style="width:100%"></p>
          <p><input class="w3-input w3-border" type="text" placeholder="APELLIDOS" style="width:100%"></p>
          <p><input class="w3-input w3-border" type="text" placeholder="TELEFONO CELULAR" style="width:100%"></p>
          <p><input class="w3-input w3-border" type="text" placeholder="CORREO ELECTRONICO" style="width:100%"></p>
          <p><button type="button" onclick="document.getElementById('subscribe').style.display='block'" class="w3-button w3-block w3-red">¡REGISTRAR!</button></p>
        </div>
      </div>

    <!-- END About/Intro Menu -->
    </div>

  <!-- END GRID -->
  </div>

<!-- END w3-content -->
</div>

<!-- Subscribe Modal -->
<div id="subscribe" class="w3-modal w3-animate-opacity">
  <div class="w3-modal-content" style="padding:32px">
    <div class="w3-container w3-white">
      <i onclick="document.getElementById('subscribe').style.display='none'" class="fa fa-remove w3-transparent w3-button w3-xlarge w3-right"></i>
      <h2 class="w3-wide">SUBSCRIBE</h2>
      <p>Join my mailing list to receive updates on the latest blog posts and other things.</p>
      <p><input class="w3-input w3-border" type="text" placeholder="Enter e-mail"></p>
      <button type="button" class="w3-button w3-block w3-padding-large w3-red w3-margin-bottom" onclick="document.getElementById('subscribe').style.display='none'">Subscribe</button>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-container w3-dark-grey" style="padding:32px">
  <a href="#" class="w3-button w3-black w3-padding-large w3-margin-bottom"><i class="fa fa-arrow-up w3-margin-right"></i>IR A INICIO</a>
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
</footer>

<script>
// Toggle between hiding and showing blog replies/comments
document.getElementById("myBtn").click();
function myFunction(id) {
  var x = document.getElementById(id);
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}

function likeFunction(x) {
  x.style.fontWeight = "bold";
  x.innerHTML = "✓ Liked";
}
</script>

</body>
</html>
