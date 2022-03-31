<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto Netflix</title>
    <link href="//netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome.css" rel="stylesheet">
    <link rel="stylesheet" href="neflix.css" type="text/css">
</head>
<body>
    <header>
        <div class="center">
            <div class="header-left">
                <a href=""><img src="netflix-logo-1-1.png"</a>
                <div class="menu-header">
                    <ul>
                        <li><a href="#topo">Inicio</a></li>
                        <li><a href="Series.html">Series</a></li>
                        <li><a href="Filmes.html">Filmes</a></li>
                        <li><a href="Adicionados.html">Adicionado Recentementes</a></li>
                        <li><a href="minhalista.html">Minha Lista</a></li>
                    </ul>
                </div><!--header-menu-->
            </div><!--header-left-->
            <div class="header-right">
                <div class="search">
                    <i class="icon-search"></i>
                </div><!--search-->
                <a href="infantil.html">INFANTIL</a>
                <i class="icon-gift"></i>
                <div class="notifications">
                    <div class="circle-notifications">
                        <span>5</span>
                    </div><!--circle-notifications-->
                    <i class="icon-bell-alt"></i>
                </div><!--notifications-->  
            </div><!--header-right-->
            <div class="clear"></div>
        </div> <!--center-->

        <section class="destaque">

            <video autoplay muted loop id="video-destaque">
                <source src="images/editado2.mp4" type="video/mp4">
            </video>

            <div class="overlay"></div><!--overlay-->
            <div class="texto-destaque">
                <h2>Peaky Blinders</h2>
                <h3>Assista a 6 temporada completa agora!<h3>
                <p>Uma notória gangue da Inglaterra de 1919 é liderada <br>pelo cruel Tommy Shelby, um criminoso disposto a subir na vida a qualquer preço.<p>
                <br>
                <a href=""><i class="icon-play"></i> Assitir</a>
                <a href=""><i class="icon-plus-sign-alt"></i> Minha Lista</a>
                <a href=""><i class="icon-info"></i> Mais Informações</a>
                </div><!--texto-destaque-->
            </div><!--center>-->
        </section><!--destaque-->
            <div class="filmes-destaques">
                <h4>POPULARES NA NETFLIX</h4>
            </div>         
            
            <section class="vitrine">
                 <div class="vitrine-flex">
                <div class="vitrine-single-banner">
                    <div class="vitrine-wraper" style="background-image: url('images/11.jpg');"><a src="https://www.youtube.com/watch?v=hp8BN5j26m0"></a> </div>
                </div>
                <div class="vitrine-single-banner">
                    <div class="vitrine-wraper" style="background-image: url('images/peaky2.jpg');"></div>
               </div>   
               <div class="vitrine-single-banner">
                    <div class="vitrine-wraper" style="background-image: url('images/velozos.jpg');"></div>    
                </div>
                <div class="vitrine-single-banner">
                    <div class="vitrine-wraper" style="background-image: url('images/dark.jpg');"></div>
                </div>
                <div class="vitrine-single-banner">
                    <div class="vitrine-wraper" style="background-image: url('images/4.jpeg');"></div>
               </div>
               <div class="vitrine-single-banner">
                    <div class="vitrine-wraper" style="background-image: url('images/galinha2.jpg');"></div>
                </div>

                <br>
                                     
        </section><!--vitrine-->
                <div class="terror">
                    <h3>FILMES DE TERROR</h3>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/11.jpg');"></div>
                    </div>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/24.jpg');"><a src="https://www.youtube.com/watch?v=hp8BN5j26m0"></a> </div>
                    </div>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/20.jpg');"><a src="https://www.youtube.com/watch?v=hp8BN5j26m0"></a> </div>
                    </div>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/22.jpg');"><a src="https://www.youtube.com/watch?v=hp8BN5j26m0"></a> </div>
                    </div>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/23.jpg');"><a src="https://www.youtube.com/watch?v=hp8BN5j26m0"></a> </div>
                    </div>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/21.jpg');"><a src="https://www.youtube.com/watch?v=hp8BN5j26m0"></a> </div>
                    </div>
                </div>
                        
                <break>
                <div class="açao">
                    <h3>FILMES DE AÇÃO</h3>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/.jpg');"></div>
                    </div>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/.jpg');"></div>
                    </div>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/.jpg');"></div>
                    </div>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/.jpg');"></div>
                    </div>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/.jpg');"></div>
                    </div>
                    <div class="vitrine-single-banner">
                        <div class="vitrine-wraper" style="background-image: url('images/.jpg');"></div>
                    </div>
                </div>
                </break>
                
    <script src="jquery.js"></script>
    <script src="slick.min.js"></script>

   <script>
        $('.vitrine-flex').slick({
            dots: false,
            arrows: false,
            infinite: false,
            centerMode: false,
            speed:1000,
            slidesToShow: 6,
                autoplay: true,
                autoplaySpeed: 3000,
                pauseOnHover: false,
        });
    </script>
</body>
</html>  
