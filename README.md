# Fake-Spotify
 Usando bootstrap para criar uma réplica do site Spotify

 <!doctype html>
<html lang="pt-br">

<head>
   <!-- Required meta tags -->
   <meta charset="utf-8">
   <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

   <!-- Bootstrap CSS -->
   <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
      integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">

      
   <!-- CSS -->
   <link rel="stylesheet" href="style.css">

   <!-- Font Awesome -->
   <script src="https://kit.fontawesome.com/d24de72b8a.js" crossorigin="anonymous"></script>

   <!-- HTML Shiv -->
   <!--[if lt IE 9]>
	<script src="bower_components/html5shiv/dist/html5shiv.js"></script>
   <![endif]-->

   <!-- Tab icon -->
   <link rel="shortcut icon" href="imagens/favicon.png" type="image/x-icon">

   <style>
      

   
   </style>

   <title>Músicas para todos - Spotify</title>
</head>

<body>

   <!-- Início cabeçalho -->
   <header>
      <nav class="navbar navbar-expand-md navbar-light fixed-top" id="transparente">
         <div class="container">
            <!-- logo -->
            <a href="index.html" class="navbar-brand">
               <img src="imagens/spotify.svg" alt="logo spotify" width="142">
            </a>
            <!-- humnurguer button -->
            <button class="navbar-toggler" data-toggle="collapse" data-target="#hamb-button">
               <i class="fas fa-bars text-white"></i>
            </button>
            <!-- menu -->
            <div class="collapse navbar-collapse" id="hamb-button">
               <ul class="navbar-nav ml-auto">
                  <li class="nav-item">
                     <a href="" class="nav-link">Premium</a>
                  </li>
                  <li class="nav-item">
                     <a href="" class="nav-link">Ajuda</a>
                  </li>
                  <li class="nav-item">
                     <a href="" class="nav-link">Baixar</a>
                  </li>
                  <li class="nav-item divisor"></li>
                  <li class="nav-item">
                     <a href="" class="nav-link">Inscrever-se</a>
                  </li>
                  <li class="nav-item">
                     <a href="" class="nav-link">Entrar</a>
                  </li>
               </ul>
            </div>

         </div>
      </nav>
   </header>
   <!-- Fim Cabeçalho -->

   <!-- Capa -->
   <section id="home" class="d-flex">
      <div class="container align-self-center">
         <div class="row">
            <div class="col-md-12 capa">

               <div class="carousel slide" data-ride="carousel" id="carousel-spotify">
                  <div class="carousel-inner">

                     <div class="carousel-item active">
                        <h1>Música para todos</h1>
                        <a href="" class="btn btn-lg btn-custom btn-roxo">Aproveite o Spotify Free</a>
                        <a href="" class="btn btn-lg btn-custom btn-branco">Obter Spotify Premium</a>
                     </div>

                     <div class="carousel-item">
                        <h1>As melhores rádios</h1>
                        <a href="" class="btn btn-lg btn-custom btn-branco"><i class="fas fa-music"></i> Ouça agora</a>
                     </div>

                  </div>

                  <!-- Controles -->

                  <a href="#carousel-spotify" class="carousel-control-prev" data-slide="prev"><i class="fas fa-angle-left fa-3x"></i></a>

                  <a href="#carousel-spotify" class="carousel-control-next" data-slide="next"><i class="fas fa-angle-right fa-3x"></i></a>

                  <!-- Fim controles -->
               </div>

            </div>
         </div>
      </div>
   </section>
   <!-- Fim capa -->

   <!-- Conteúdos -->
   <section id="servicos">
      <div class="container">
         <div class="row">
            <!-- Imagens -->
            <div class="col-md-6">              
               <div class="row albuns">
                  <div class="col-md-6">
                     <img src="imagens/img1.jpg" class="img-fluid foto">
                  </div>
                  <div class="col-md-6">
                     <img src="imagens/img2.jpg" class="img-fluid foto">
                  </div>
               </div>
               <div class="row albuns">
                  <div class="col-md-6">
                     <img src="imagens/img3.jpg" class="img-fluid foto">
                  </div>
                  <div class="col-md-6">
                     <img src="imagens/img4.jpg" class="img-fluid foto">
                  </div>
               </div>              
            </div>
            <!-- Fim imagens -->
            <!-- Textos -->
            <div class="col-md-6">
               
               <h2>O que o Spotify tem?</h2>

               <h3>Músicas</h3>
               <p>O Spotify tem milhões de músicas. Escute seus sons favoritos, descubra novas músicas e reúna seus favoritos em um só lugar.</p>

               <h3>Playlists</h3>
               <p>No Spotify você encontra uma playlist para cada momento. Todas feitas por fanáticos e especialistas da música.</p>

               <h3>Novos lançamentos</h3>
               <p>Escute os novos lançamentos de singles e álbuns da semana e veja o que está bombando no Top 50.</p>

            </div>
            <!-- Fim textos -->
         </div>
      </div>
   </section>
   <!-- Conteúdos -->

   <!-- Recursos -->
   <section id="recursos">
      <div class="container">
         <div class="row">
            <!-- Textos -->
            <div class="col-md-4">

               <h2>Fácil</h2>
               <h3>Buscar</h3>
               <p>Já sabe o que quer escutar? É só procurar e apertar o play.</p>

               <h3>Navegar</h3>
               <p>Veja os novos lançamentos, o que está bombando nas paras e as melhores playlist para o seu momento.</p>

               <h3>Descobrir</h3>
               <p>Curta músicas novas toda segunda-feira com uma playlist personalizada para você. Ou relaxe e curta uma das rádios.</p>

            </div>
            <!-- Fim textos -->
            <!-- Imagens -->
            <div class="col-md-8">
               <div class="row rotacionar">
                  <div class="col-md-6">
                     <img src="imagens/iphone1.png" class="img-fluid d-none d-md-block">
                  </div>
                  <div class="col-md-6">
                     <img src="imagens/iphone3.png" class="img-fluid d-none d-md-block">
                  </div>
               </div>
            </div>
            <!-- Fim imagens -->
         </div>
      </div>
   </section>
   <!-- Fim recursos -->

   <!-- Rodapé -->
   <footer>
      <div class="container">
         <div class="row">
            <div class="col-md-2">
               <img src="imagens/spotify.svg" width="142">
            </div>
            <div class="col-md-2">
               <h4>Company</h4>
               <ul class="navbar-nav">
                  <li>
                     <a href="">Sobre</a>
                  </li>
                  <li>
                     <a href="">Empregos</a>
                  </li>
                  <li>
                     <a href="">Imprensa</a>
                  </li>
                  <li>
                     <a href="">Novidade</a>
                  </li>
               </ul>
            </div>
            <div class="col-md-2">
               <h4>Comunidades</h4>
               <ul class="navbar-nav">
                  <li>
                     <a href="">Artista</a>
                  </li>
                  <li>
                     <a href="">Desenvolvedores</a>
                  </li>
                  <li>
                     <a href="">Marcas</a>
                  </li>
               </ul>
            </div>
            <div class="col-md-2">
               <h4>Links úteis</h4>
               <ul class="navbar-nav">
                  <li>
                     <a href="">Ajuda</a>
                  </li>
                  <li>
                     <a href="">Presentes</a>
                  </li>
                  <li>
                     <a href="">Player da web</a>
                  </li>
               </ul>
            </div>
            <div class="col-md-4">
               <ul>
                  <li>
                     <a href="">
                        <img src="imagens/facebook.png" alt="">
                     </a>
                  </li>
                  <li>
                     <a href="">
                        <img src="imagens/instagram.png" alt="">
                     </a>
                  </li>
                  <li>
                     <a href="">
                        <img src="imagens/twitter.png" alt="">
                     </a>
                  </li>
               </ul>
            </div>
         </div>
         <div id="copy">
            <p>&copy; Todos os direitos reservados - Allan</p>
         </div>
      </div>
   </footer>
   <!-- Fim rodapé -->

   <!-- Optional JavaScript -->
   <!-- jQuery first, then Popper.js, then Bootstrap JS -->
   <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
      integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
      crossorigin="anonymous"></script>
   <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
      integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
      crossorigin="anonymous"></script>
   <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"
      integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI"
      crossorigin="anonymous"></script>

</body>

</html>
