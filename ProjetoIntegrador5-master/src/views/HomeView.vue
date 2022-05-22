<template>
  <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
    <div class="carousel-indicators">
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="1"
        aria-label="Slide 2"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="2"
        aria-label="Slide 3"
      ></button>
    </div>
    <div class="carrosel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="../assets/carrossel.jpg"
            width="100px"
            height="500px"
            class="d-block w-100 img-carrossel"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>First slide label</h5>
            <p>Some representative placeholder content for the first slide.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img
            src="../assets/carrossel1.png"
            class="d-block w-100 img-carrossel"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Second slide label</h5>
            <p>Some representative placeholder content for the second slide.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img
            src="../assets/carrossel2.jpeg"
            class="d-block w-100 img-carrossel"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Third slide label</h5>
            <p>Some representative placeholder content for the third slide.</p>
          </div>
        </div>
      </div>

      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <div class="row">
    <div class="col-lg-15 div-home">
        <img src="../assets/racao.jpg" id="oi" class="rounded-circle img-home"  alt="gato">
        <title>Placeholder</title>
      <h2 class="fw-normal">Heading</h2>
      <p>
        Some representative placeholder content for the three columns of text
        below the carousel. This is the first column.
      </p>
      <p><a class="btn btn-secondary" href="#">View details &raquo;</a></p>
    </div>
    <div class="col-lg-15 div-home">
        <img src="../assets/brinquedo.jpg" id="oi" class="rounded-circle img-home"  alt="gato">
        <title>Placeholder</title>
      <h2 class="fw-normal">Heading</h2>
      <p>
        Another exciting bit of representative placeholder content. This time,
        we've moved on to the second column.
      </p>
      <p><a class="btn btn-secondary" href="#">View details &raquo;</a></p>
    </div>
    <div class="col-lg-15 div-home">
        <img src="../assets/agua.jpg" id="oi" class="rounded-circle img-home"  alt="gato">
        <title>Placeholder</title>
      <h2 class="fw-normal">Heading</h2>
      <p>
        And lastly this, the third column of representative placeholder content gosot de fazer programação e café com leite.
      </p>
      <p><a class="btn btn-secondary" href="#">View details &raquo;</a></p>
    </div>
  </div>
  </div>

  <link href="../assets/dist/css/bootstrap.min.css" rel="stylesheet" />

 
  
</template>
