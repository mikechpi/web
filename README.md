# web

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mike page</title>

    <link rel="stylesheet" href="css/bootstrap.css">

    <link rel="icon" type="image/png" href="me.png" />

</head>

<body>

    <header class="blog-header py-3">

        <center>
            <h1>Mike</h1>
        </center>
        <!--</div>
            <div class="col-4 d-flex justify-content-end align-items-center">
                <a class="text-muted" href="#" aria-label="Search">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="mx-3" role="img" viewBox="0 0 24 24" focusable="false"><title>Search</title><circle cx="10.5" cy="10.5" r="7.5"/><path d="M21 21l-5.2-5.2"/></svg>
                </a>
                <a class="btn btn-sm btn-outline-secondary" href="#">résumé</a>
            </div>
         </div>-->


        <div class="nav-scroller py-1 mb-2">
            <nav class="nav d-flex justify-content-between">
                <a class="p-2 text-muted" href="index.html">Présentation</a>
                <a class="p-2 text-muted" href="formation.html">Formation</a>
                <a class="p-2 text-muted" href="projets.html">Projets</a>
                <a class="p-2 text-muted" href="expérience.html">Expérience</a>
                <a class="p-2 text-muted" href="dePlus.html">De plus</a>
            </nav>
        </div>
    </header>





    <div id="myCarousel" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
            <li data-target="#myCarousel" data-slide-to="1"></li>
            <li data-target="#myCarousel" data-slide-to="2"></li>
        </ol>

        <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="https://via.placeholder.com/150x50" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>First slide label</h5>
                        <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="https://via.placeholder.com/150x50" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Second slide label</h5>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="https://via.placeholder.com/150x50" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Third slide label</h5>
                        <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p>
                    </div>
                </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>


        <div class="container">

            <hr>

            <div class="row featurette">
                <div class="col-md-7">
                    <h2 class="who I am">Qui suis-je ?</h2>
                    <p class="lead">Je me présente Mike CHING PI, jeune étudiant plein d'ambition. Depuis mes 9 ans je suis attiré par la technologie et j'étais déjà déterminé à travailler dedans en m’informant et pratiquant plusieur projets touchant à la technologie,
                        tout jeune bachelier je décide de développer mes connaissances pour prêt à intégrer le monde actif.
                    </p>
                </div>
                <div class="col-md-5">
                    <img src="https://via.placeholder.com/400x400?text=test" alt="">
                </div>
            </div>

            <hr>

            <div class="row featurette">
                <div class="col-md-7 order-md-2">
                    <h2>Mes projets</h2>
                    <p class="lead">Mon projet principal est de finir mes études et d'être diplômé. En parallèle j’offre mes connaissances de développeurs pour faire la plateforme des entreprises qui m'accordent leur confiance telle que Draw My Futurs.
                    </p>
                </div>
                <div class="col-md-5 -md-1">
                    <img src="https://via.placeholder.com/400x400?text=test" alt="">
                </div>
            </div>

            <hr>

            <div class="row featurette">
                <div class="col-md-7">
                    <h2 class="idk">Ce qui me qualifie</h2>
                    <p class="lead">Je suis une personne autonome sociable, patient, aime aider autrui et le travaille d’équipe très attentif qui assimile très vite ce que l’on me demande. Je transmets facilement ma joie de vivre à ce qui m'entoure
                    </p>
                </div>
                <div class="col-md-5">
                    <img src="https://via.placeholder.com/400x400?text=test" alt="">
                </div>
            </div>

            <hr>

        </div>


        <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"></script>

        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>

        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
</body>

</html>
