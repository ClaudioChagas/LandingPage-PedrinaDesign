# LandingPage-PedrinaDesign

<!DOCTYPE html>

<html lang="pt-br">
    <head>
        <meta charset="utf-8">
        <title>pedrinadesign</title>
        <link rel="stylesheet" href="./style.css">
        <meta name="viewport" content="width=device-width, inicial-scale=1.0, maximum-scale=1.0">
        <link rel="shortcut icon" href="./WhatsApp Image 2021-10-21 at 15.08.31.jpeg" type="image/x-icon">
        <link rel="stylesheet" href="./bootstrap/bootstrap-5.1.0-dist/css/bootstrap.min.css">


    </head>

    <body>
        <div class="page">
           
            <header class="cabeca">
                <a href="https://pedrinadesign.com/" target="_blanck">
                    <img src="./logo.png" alt="pedrinadesign">
                </a>
                <div class="links">
                    <a href="https://pedrinadesign.com/">Início</a>
                    <a href="https://pedrinadesign.com/produtos/">Produtos</a>
                    <a href="https://pedrinadesign.com/contato/">Contato</a>
                    <a href="https://pedrinadesign.com/quemsomos/">Quem somos</a>
                    <a href="https://pedrinadesign.com/crieseuacessorio/">Personalize</a>
                </div>
            </header>

            <div class="container">
                <div class="texto">
                    <h1>Você pode ter um acessório do seu jeitinho e nós vamos te contar como:</h1>
                    <h3>seja pra alterar o tamanho, a cor, ou ainda tirar do papel um modelo mega exclusivo, estamos aqui pra fazer tudo isso ser real pra você!</h3>
                    <button>Conheça</button>
                </div>

               
                <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active" data-bs-interval="0">
                            <img src="./brinco.jpg" class="d-block w-100" alt="imagem1">
                        </div>
                        <div class="carousel-item" data-bs-interval="0">
                            <img src="./brinco2.jpg" class="d-block w-100" alt="imagem2">
                        </div>
                        <div class="carousel-item">
                            <img src="./presilha.jpg" class="d-block w-100" alt="imagem3">
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>

                <div class="instagram">
                    <a href="https://www.instagram.com/pedrina.design/"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAABmJLR0QA/wD/AP+gvaeTAAAEjUlEQVRoge2ZP2xTVxTGf+c5TkJJVdEh/AlThZoKE9s8d0Bi74JoniNFbdWMyEPbkRRQl0wVSaZWHRqqbgEJQRuH0qWqqk6oUYkTJxiQgAkKykwIcuy808Ek+Ll+/0u7+JMy3KNz3v1O7jvfp/sMHXTQQQf/JyRMcmo01d1T67IEtRRM4CCwOyaHZ8AjgZIixWqyXqxcqWwGLQ7cgJnPjKA6DbwVhWUIPEBlvDRfnguSnPDNmMAw30hPAl8Be2KSC4I3ET7Y/86+1558uPYbv6Neyb4NmHvSU8D4v0YvOI4fWNvX++Tu2q9eSZ6v0IvX5oeWcFWVGQMu1Z5za+WXlWdxWKbfS+9O7uKIioyBFoBuJ0HNLxZXi271rg00BjZxh+Z3XvhL2TqxNFcpxyHthqyVzRpiX0cZaKJ4X/q7Di9eWKy1q+lye1hPrcsCbR7Y6qsgnxvJnlC1Z0RRm62CsWWctA39g52T0EP2Wm0YuNqu3nB7sKBW81qVmVfyn7ftb1EGFA4KMnPzWnkJle+cXMRyK3c9ASDXvEiIXPTj4uITEFbnEzqLzacvO9B33VJdT0Bhf/P6ebJ+22tPM58ZacyMXlb4CBikYXK7gcFGTC/31BK3zeFMfrvORgsCj4CHCAWAXfVqpeXxB9z2dR1i00o79LdUXGmfO4FhLqXPI2GlVqZK2fI5JrDj7O96AkFhltOT4ckD6Oe5cubLuPvHaqDhE5xuCVdV+VqUY/UN+uob9IlyDOQbwPHuq+qZnDXkOqBB4DXEnkiNprqp6bQjuO0TxX+o1QKwkLWy37fqvGJM5wq5n9103g+RT6DhE4TyieXi8rKxJSdxnMSOzkdC5Aai+kRYnfdDnBkI7RMvk3XWsfbQeT9EbkBbtNnPJ5pRTWzdagkNtE0MgNgyGgV9630t+2pbLwiCGDPA4+Z172YiFbR2s3ejJVeeROURuQEbbjo56MdBa0VlzBnRP6PyiHECMu+ggBSyVjbrV5cbSZvAKUetOp8VBpEbqCbrReBBU6jHEPu6VxO5kbSpNj/hvHXdM/YmIzcQ2YkrVyqb5nBmHNEfd4LKgIG9YFqZCyr2pc0uexWgu24MicqY2pxqIa9qc7oU0YUhpgqV5stzKNMt4W7Qz0TlRk8t8bSnlngqKjeAT2i576rq5NK1lWtxOMSW0dLRlbMgUyHLVEQml46ufhF3f68GnjYvUqOpvrZZE9ilYvmMoHmQ+wH2vGeL5hfnymfd7gLH3x983YtLMzzuxDi02U/nF4urRenvOqzKKCoXUe4C6y/+7oDOqjIq/cnU8tyq59BuJLqPtIQet03EY4htuCnw9k6gofMLnk00hvEqLl8QgiKMT3icQDSdj4uwPuHaQBSdj4soPuH9aXE4k3fofAObIDs6X7lSWY/BmdRoqm/bJ6CtT1heUuv7ed0cTk9Fu7THh6qeX5pfPeeV4+sDEXU+LgL7ROAfOHLWkKUY06CH4nHzxT1bdNxParcR6iemXCGXtNdqw407rOYQDgLtDS441oGHoIuqMm/sTc5H/ULRQQcddPDf429zE+Yh4JyrjQAAAABJRU5ErkJggg=="></a>
                    <!--
                     <a href="https://icons8.com/icon/85154/instagram">Instagram icon by Icons8</a> ->
                    --> 
                </div>

            </div>
        
        </div>
        <script src="./main.js"></script>
        <script src="./bootstrap/bootstrap-5.1.0-dist/js/bootstrap.min.js"></script>
    </body>


</html>
