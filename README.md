<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Portfólio do João</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #f8f9fa;
      font-family: 'Segoe UI', sans-serif;
    }
    .profile-img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #0d6efd;
    }
    .skills span {
      border: 1px solid #0d6efd;
      padding: 5px 10px;
      border-radius: 20px;
      margin: 5px;
      display: inline-block;
      color: #0d6efd;
    }
    .card {
      border-color: #0d6efd;
    }
    .card-title {
      font-weight: bold;
    }
    .contact a {
      text-decoration: none;
      color: #0d6efd;
      font-weight: bold;
    }
  </style>
</head>
<body>

<div class="container text-center mt-5">
  <img src="mario.jpg" alt="Foto de perfil do João" class="profile-img">
  <h6 class="text-muted mt-3">Olá, meu nome é João</h6>
  <h1 class="fw-bold">Eu estudo Programação</h1>
  <p class="mt-3">
    Sou estudante do 2º ano do Ensino Médio e estou aprendendo tudo do mundo da programação.<br>
    Veja abaixo os projetos que já desenvolvi ao longo dos meus estudos.
  </p>

  <div class="skills my-3">
    <span>HTML</span>
    <span>CSS</span>
    <span>JavaScript</span>
    <span>Scratch</span>
    <span>p5.js</span>
  </div>
</div>

<div class="container mt-5">
  <h3 class="fw-bold mb-4">Meus projetos</h3>
  <div class="row row-cols-1 row-cols-md-3 g-4">
    <div class="col">
      <div class="card h-100">
        <iframe src="https://scratch.mit.edu/projects/1041498458/embed" allowtransparency="true" width="100%" height="200" frameborder="0" scrolling="no" allowfullscreen></iframe>
        <div class="card-body">
          <h5 class="card-title">Projeto no Scratch</h5>
          <p class="card-text">Esse é um dos meus projetos desenvolvidos na plataforma Scratch.</p>
          <a href="https://scratch.mit.edu/projects/1041498458" target="_blank" class="text-decoration-none text-primary fw-bold">Ver projeto</a>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <iframe src="https://editor.p5js.org/joao0000ooo/full/dBUNPDZjh" width="100%" height="200" frameborder="0"></iframe>
        <div class="card-body">
          <h5 class="card-title">Projeto com p5.js</h5>
          <p class="card-text">Experimento visual interativo usando a biblioteca p5.js.</p>
          <a href="https://editor.p5js.org/joao0000ooo/full/dBUNPDZjh" target="_blank" class="text-decoration-none text-primary fw-bold">Ver projeto</a>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <iframe src="https://editor.p5js.org/joaohenrique16/sketches/rHa5VBAbk" width="100%" height="200" frameborder="0"></iframe>
        <div class="card-body">
          <h5 class="card-title">Animação com p5.js</h5>
          <p class="card-text">Animação criativa desenvolvida com JavaScript e p5.js.</p>
          <a href="https://editor.p5js.org/joaohenrique16/sketches/rHa5VBAbk" target="_blank" class="text-decoration-none text-primary fw-bold">Ver projeto</a>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="container text-center mt-5 contact mb-5">
  <h3 class="fw-bold">Entre em contato</h3>
  <p><a href="#">@seuInstagram_ou_email</a></p>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html># Alura
