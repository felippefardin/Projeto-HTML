# Projeto-HTML
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Projeto-HTML</title>
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css"
      integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N"
      crossorigin="anonymous" />
    <link rel="stylesheet" href="css/index.css" />
    <script
      src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"
      integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
      crossorigin="anonymous"></script>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct"
      crossorigin="anonymous"></script>
    <script src="js/index.js"></script>
  </head>

  <body>
    <div class="nome text-center">
      <h1>Sua locadora</h1>
    </div>

    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">Sua locadora</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarScroll"
        aria-controls="navbarScroll"
        aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarScroll">
        <ul
          class="navbar-nav mr-auto my-2 my-lg-0 navbar-nav-scroll"
          style="max-height: 100px">
          <li class="nav-item active">
            <a class="nav-link" href="#"
              >Home <span class="sr-only">(current)</span></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Novidades</a>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              role="button"
              data-toggle="dropdown"
              aria-expanded="false">
              Filmes
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Ação</a></li>
              <li><a class="dropdown-item" href="#">Comédia</a></li>
              <li><hr class="dropdown-divider" /></li>
              <li><a class="dropdown-item" href="#">Animação</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled">Opções</a>
          </li>
        </ul>
        <form class="d-flex">
          <input
            class="form-control mr-2"
            type="search"
            placeholder="Search"
            aria-label="Search" />
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </nav>

    <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
          <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="img/1ce1f7a439f3eee7d877123b98060453490bf0fdr1-1280-321v2_hq.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>First slide label</h5>
              <p>Some representative placeholder content for the first slide.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="img/baby-ioda-1024x256.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Second slide label</h5>
              <p>Some representative placeholder content for the second slide.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="img/wpid-picsart_1442695203206.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Third slide label</h5>
              <p>Some representative placeholder content for the third slide.</p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-target="#carouselExampleCaptions" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-target="#carouselExampleCaptions" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </button>
      </div>

    <h1>
      <div class="conteiner bg-info nome text-center">
        <h2>Filmes</h2>
      </div>
    </h1>

    <div class="conteiner">
      <div class="row"></div>
      <div class="col-md-3"></div>
      <img
        class="imagem-tamanho"
        src="img/0fc43fd1869a104f5bafa33398657210.jpg"
        class="img-fluid"
        alt="..." />
      <img
        class="imagem-tamanho"
        src="img//obra_13173214.jpg"
        class="img-fluid"
        alt="..." />
      <img
        class="imagem-tamanho"
        src="img/737e23f8-f9b2-4e5c-8777-5c0512418782930d91eeb33549b58977cf8d302f2ae231838797filmecirculodefogocartazpostervintagequadroretro79077132365931600x600.webp"
        class="img-fluid"
        alt="..." />
    </div>

    <h1>
      <div class="conteiner bg-info nome text-center">
        <h2>Série<s/h2>
      </div>
    </h1>

    <div class="col-md-3"></div>
    <img
      class="imagem-tamanho"
      src="img/Diabolical_Key_Art_Full_thumb.jpg"
      class="img-fluid"
      alt="..." />
    <img
      class="imagem-tamanho"
      src="img/krVFRIeIhp.jpg"
      class="img-fluid"
      alt="..." />
    <img
      class="imagem-tamanho"
      src="img/unnamed.jpg"
      class="img-fluid"
      alt="..." />

    <h1>
      <div class="conteiner bg-info nome text-center">
        <h2>Documentários</h2>
      </div>
    </h1>

    <div class="col-md-3"></div>
    <img
      class="imagem-tamanho"
      src="img/img-0738.jpg"
      class="img-fluid"
      alt="..." />
    <img
      class="imagem-tamanho"
      src="img/Framing_Britney_Spears.jpg"
      class="img-fluid"
      alt="..." />
    <img
      class="imagem-tamanho"
      src="img/lady-gaga-761x1024.jpg"
      class="img-fluid"
      alt="..." />
  </body>
</html>
