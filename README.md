<!doctype html>
<html lang="ru">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Домашняя страничка Иванов Иван</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Моя страничка</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" href="Лаба 5.html">Главная</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="Лаба 5 мой вуз.html">Мой вуз</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="Лаба 5 моя группа.html">Моя группа</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <header class="bg-light py-5">
      <div class="container text-center">
        <h1>Обо мне</h1>
        <div class="row justify-content-center">
          <div class="col-md-3">
            <img src="avatar.jpg" class="img-fluid rounded-circle" alt="Avatar">
          </div>
        </div>
        <p class="mt-3">Привет, меня зовут Никита Корчаков. Я студент, увлекаюсь программированием.</p>
      </div>
    </header>
    <div class="container mt-5">
      <h2>Мои увлечения</h2>
      <ul>
        <li>Программирование</li>
         </ul>
      <h3>Мои фотографии</h3>
      <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="image1.jpg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="image2.jpg" class="d-block w-100" alt="...">
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <h3>Мои данные</h3>
      <table class="table table-bordered">
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">Информация</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>Имя</td>
            <td>Корчаков Никита</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td>Увлечения</td>
            <td>Программирование</td>
          </tr>
        </tbody>
      </table>
      <button class="btn btn-primary" onclick="alert('Спасибо за посещение!')">Нажми меня</button>
    </div>

    <footer class="bg-dark text-white text-center py-3">
      <p>25 ноября 2024</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
  </body>
</html>
