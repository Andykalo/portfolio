<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style/style.css">
    <link rel="stylesheet" href="dist/css/bootstrap.css">
    <title>Accueil</title>
</head>
<body>
    <nav class="navbar navbar-expand-sm navbar-dark bg-dark justify-content-center fixed-top">
        <div class="container-fluid">
          <a class="navbar-brand" href="javascript:void(0)">Logo</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="mynavbar">
            <ul class="navbar-nav justify-content-center">
              <li class="nav-item">
                <a class="nav-link" href="javascript:void(0)">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="javascript:void(0)">Profil</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="javascript:void(0)">Skills</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="javascript:void(0)">Blog</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="javascript:void(0)">Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>


<div class="container-fluid pb-5 bg-image" id="about" style="background-image: url('assets/pexels-olia-danilevich-4974912.jpg');background-size: cover; background-position: center; background-repeat: no-repeat;
height: 100vh">
    <div class="row">   
        <div class="col-xs-8 col-md-4 text-center profile-picture">
            <img src="assets/img/me22.jpg" alt="Me" class="rounded-circle img-fluid" id="avatar">
        </div>
    </div>
    <div class="row">
        <div class="heading col-md-12 text-center">
            <h1 class="text-white">Andy KALOMBO</h1>
            <h3 class="text-dark">Développeur Web & Mobile</h3>
            <button type="button" class="btn btn-outline-primary"> <a href="assets/cv/andy_cv.pdf" class="text-white">Télécharger CV</a>
            </button>
        </div>
    </div>
</div>

<div class="container-fluid" id="skylls">
    <div class="row">
        <div class="text-center pt-2 text-danger">
            <h1 class="">COMPETENCE</h1>
        </div>
    </div>
</div>
<div class="container text-justify pt-5 mb-4">
  <div class="row">
    <div class="col-md-6">
           <div>
            <p>
                Lorem ipsum dolor sit amet. Aut veritatis autem a fugit maxime ad corporis debitis aut internos quidem et voluptatem saepe ad expedita suscipit! Et sunt facilis in officia nihil et cupiditate sapiente id consequatur repudiandae. Sit expedita provident ex corporis eveniet quo omnis dolor. Aut earum architecto et voluptate pariatur vel inventore ipsum.
                Ad saepe doloremque est rerum itaque 33 vero dolore At enim galisum in sapiente officiis quo sunt voluptatem. Sed optio exercitationem et beatae accusantium est galisum voluptas! Et voluptas alias eos magni magni ut veniam quis est sint nobis At quibusdam nemo?
                Ea enim recusandae hic ratione repellat et quaerat consequatur et asperiores ipsum et suscipit enim. Ut doloremque porro aut architecto modi sit suscipit sequi et dolores laudantium. Nam ducimus tempore ea deserunt magni rem accusantium obcaecati.
            </p>
           </div>              
    </div>
    <div class="col-md-6 text-center">
      <img src="assets/img/me.jpg" class="rounded mx-auto img-fluid" alt="Cinque Terre" style="height:500px ; width:400px">       
</div>
    
</div>
</div>

<div class="container-fluid" id="" style="background-image: url('assets/pexels-negative-space-34580.jpg');background-size: cover; background-position: center; background-repeat: no-repeat;
height: 80vh">
    <div class="row">
        <div class="text-center text-danger">
            <h1 class="">SKILLS</h1>
        </div>
    </div>
    <div class="row pt-4">
        <div class="col-md-6">
            <p>
                My soft and hard skill
            </p>
        </div>  

        <div class="col-md-6 bg-white">
          <div class="progress m-3" style="width: 50%;">
            <div class="progress-bar" style="width:70%">70%</div>
          </div>
          <div class="progress m-3" style="width: 50%;">
            <div class="progress-bar" style="width:70%">70%</div>
          </div>
          <div class="progress m-3" style="width: 50%;">
            <div class="progress-bar" style="width:70%">70%</div>
          </div>
          <div class="progress m-3" style="width: 50%;">
            <div class="progress-bar" style="width:70%">70%</div>
          </div>
          
        </div>
    </div>
</div>

<div class="container-fluid">
    <div class="row">
        <div class="col-md-6 bg-info">
            <h1>CONTACT ME</h1>
            <p>andykalombo@gmail.com</p>
            <p>+243 82 94 27 393</p>
            <p>linkedin.com/andykalo2</p>
        </div>
        <div class="col-md-6 bg-danger">
            <div class="container mt-3">
                <h2>Write a message</h2>
                <form action="/action_page.php">
                  <div class="mb-3 mt-3">
                    <label for="email">Email:</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter email" name="email">
                  </div>
                  <div class="mb-3 mt-3">
                    <label for="text">Name:</label>
                    <input type="text" class="form-control" id="text" placeholder="Enter your name" name="name">
                  </div>
                  <div class="mb-3 mt-3">
                    <label for="comment">Message:</label>
                    <textarea class="form-control" rows="5" id="comment" placeholder="Type your message" name="text"></textarea>
                  </div>
                  <button type="submit" class="btn btn-primary">Submit</button>
                </form>
              </div>
        </div>
    </div>
    
</div>


<div class="container-fluid bg-dark text-white text-center">
    <p>@2022 Copyright AndyK. Tous les droits sont réservés
    </p>
    <p>Designed by Andy KALOMBO
    </p>
</div>

 <script src="dist/js/bootstrap.js"></script>   
</body>
</html>
