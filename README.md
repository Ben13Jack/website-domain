<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>t1</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css" integrity="sha384-r4NyP46KrjDleawBgD5tp8Y7UzmLA05oM1iAEQ17CSuDqnUK2+k9luXQOfXJCJ4I" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/js/bootstrap.min.js" integrity="sha384-oesi62hOLfzrys4LxRF63OJCXdXDipiYWBnvTl9Y9/TRlw5xlKIEHpNyvvDShgf/" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha384-nD2djOU2nQv4SKDJZ8s44K9Dd9Y7vZXrS6vJ1ZkAIAJ2/c8uf6KT+ZTdrGzv7Al1" crossorigin="anonymous">
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  
 
</head>
<style>
   p{
    width: 50ch;
    color:white;
   }
   body{
    background-color: hsla(97, 100%, 100%, 0.3);
   }
   .c{
    width:500px;
    height:500px;
   }
   img{
    opacity: 0.8;
    float:center;
   }
   a:hover{
    color:aqua;
   }
   
.overlay {
    position: fixed; 
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.7); 
    display: none; 
    justify-content: center;
    align-items: center;
    z-index: 5000; 
  }
  
  .overlay-content {
    background-color: white;
    padding: 30px;
    border-radius: 8px;
    text-align: center;
    height:530px;
    width:390px;
    
  }

</style>
<body>
           <nav class="navbar navbar-expand-sm navbar-light bg-white shadow">
               <div class="container-fluid">
                   <a class="navbar-brand" href="#"></a>
                   <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarID"
                       aria-controls="navbarID" aria-expanded="false" aria-label="Toggle navigation">
                       <span class="navbar-toggler-icon"></span>
                   </button>
                   <div class="collapse navbar-collapse" id="navbarID">
                       <div class="navbar-nav">
                           <a class="nav-link active " aria-current="page" href="#">Home</a>
                           <a class="nav-link" aria-current="page" href="#">About</a>
                           <a class="nav-link " aria-current="page" href="#">view</a>
                           <a class="nav-link " aria-current="page" href="#">blogs</a>
                           <a class="nav-link " aria-current="page" href="#">contact</a>
                       </div>
                   </div>
               </div>
           </nav>

    <div class="container mt-5 rounded-pill z">
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-bs-target="#myCarousel" data-bs-slide-to="0" class="active"></li>
            <li data-bs-target="#myCarousel" data-bs-slide-to="1"></li>
            <li data-bs-target="#myCarousel" data-bs-slide-to="2"></li>
        </ol>
    
        <div class="carousel-inner">  
            <div class="carousel-item active bg-info d-flex a1">
                <img src="./image.jpg" alt="Slide 1" width="300px" height="300px">
                <p>Lorem ipsum dolor sit, amet 
                    consectetur adipisicing elit. Ipsam commodi explicabo vel quam 
                    distinctio quasi iure veniam velit necessitatibus magni esse ex 
                    est modi possimus eveniet, suscipit omnis quidem? Nesciunt cupiditate alias 
                    id mollitia quibusdam voluptates repellendus, laborum cumque,
                     omnis velit exercitationem ea porro vitae tenetur qui repellat pariatur officia.</p>
            </div>
       
            <div class="carousel-item bg-success d-flex">
                <img src="./image.png" alt="Slide 2" width="300px" height="300px">
                <p class="p-5">Lorem ipsum dolor sit, amet 
                    consectetur adipisicing elit. Ipsam commodi explicabo vel quam 
                    distinctio quasi iure veniam velit necessitatibus magni esse ex 
                    est modi possimus eveniet, suscipit omnis quidem? Nesciunt cupiditate alias 
                    id mollitia quibusdam voluptates repellendus, laborum cumque,
                     omnis velit exercitationem ea porro vitae tenetur qui repellat pariatur officia.</p>
            </div>
            <div class="carousel-item bg-dark d-flex">
                <img src="./images.png" alt="Slide 3" width="300px" height="300px">
                <p class="p-5">Lorem ipsum dolor sit, amet 
                    consectetur adipisicing elit. Ipsam commodi explicabo vel quam 
                    distinctio quasi iure veniam velit necessitatibus magni esse ex 
                    est modi possimus eveniet, suscipit omnis quidem? Nesciunt cupiditate alias 
                    id mollitia quibusdam voluptates repellendus, laborum cumque,
                     omnis velit exercitationem ea porro vitae tenetur qui repellat pariatur officia.</p>
            </div>
        </div>
    
        <a class="carousel-control-prev" href="" data-bs-target="#myCarousel" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="" data-bs-target="#myCarousel" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
</div>
    
<div class="container mt-5">
<div class="flex-row mt-5 d-flex">
<div class="contanier c1" style="width:500px; height:500px;">
    <div class="col-md-5">
    <div class="card border border-0" style="width:500px;height:50px;">
        <h1>heading1</h1>
    <div class="card-body" data-target="#cont" style="width:100px;height:100px;">
        <a href=""><i class="material-icons">forward</i></a>
        <img src="./face10.jpg" class="rounded-pill" style="width:150px;height:150px;" alt="images">
        <p class="text-secondary border border-5 c p-5" style="height:300px;" href="#cont">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo pariatur reprehenderit soluta sapiente 
            dolores vitae illo molestiae laboriosam doloribus natus a in numquam dolore ad ex fuga, eum
             doloremque. Perferendis veniam possimus voluptas magnam ipsam enim sed velit blanditiis 
             harum, sapiente cum, illum necessitatibus quibusdam repellendus alias incidunt omnis 
             ipsum ab aliquid ex dolores beatae molestiae laborum. Rem molestias pariatur esse voluptate
              </p>
    </div>
    </div>
</div>
</div>
<div class="container c1" style="height:500px;width:500px;">
    <div class="col-md-5 col-sm-5">
    <div class="card border border-0" style="width:500px;height:100px;">
        <h1>heading2</h1>
        <div class="card-body" data-target="#bs" style="width:100px;height:50px;">
            <a href=""><i class="material-icons">forward</i></a>
            <img src="./face5.jpg" class="rounded-pill" style="width:150px;height:150px;" alt="">
            <p class="text-secondary border border-5 c p-5" style="height:300px;" href="#bs">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                Incidunt error expedita harum consequatur facilis molestiae soluta ipsa officia velit suscipit, 
                possimus quo fuga quod explicabo? Molestias officia odio et minima ducimus voluptatum rem,
                 necessitatibus corrupti omnis blanditiis dolor aut eum iste aspernatur consectetur commodi 
                 quod delectus aperiam! Eum placeat, error earum soluta officiis omnis autem doloremque impedit
                  electus excepturi eligendi rerum totam.</p>
        </div>
        </div>
    </div>
</div>
<div class="contanier c1" style="width:500px; height:500px;">
    <div class="col-md-5 bg-info">
    <div class="card border border-0" style="width:500px;height:100px;">
        <h1>heading3</h1>
    <div class="card-body" data-target="#image" style="width:100px;height:50px;">
        <a href=""><i class="material-icons">forward</i></a>
        <img src="./face8.jpg" class="rounded-pill" style="width:150px;height:150px;" alt="images">
        <p class="text-secondary border border-5 c p-5" style="height:300px;" href="#image">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo pariatur reprehenderit soluta sapiente 
            dolores vitae illo molestiae laboriosam doloribus natus a in numquam dolore ad ex fuga, eum
             doloremque. Perferendis veniam possimus voluptas magnam ipsam enim sed velit blanditiis 
             harum, sapiente cum, illum necessitatibus quibusdam repellendus alias incidunt omnis 
             ipsum ab aliquid ex dolores beatae molestiae laborum. Rem molestias pariatur esse voluptate.</p>
    </div>
    </div>
</div>
</div>
</div>
</div>
<div class="flex-row d-flex">

</div>
<br><br>
<div class="container mt-5 shadow">
    <div class="card border border-0">
        <div class="card-body">
            <h5 class="card-title">Title</h5>
            <p class="card-text">Content</p>
        </div>
        <div class="card-footer bg-light">
            <div class="row justify-content-between">
            <div class="col-md-1 col-sm-5 d-flex">
                <button class="rounded-5 border">
                <i class="material-icons">
                    mail</i>
                </button>
                <span>Mail</span>
            </div>
            <div class="col-md-1 col-sm-5 d-flex" style="border: none;">
                <button onclick="hideOverlay()" class="border-0 rounded-pill">
                    <i class="material-icons">
                        person</i>
                    </button>
                    <span>User</span>
                </div>
            <div class="col-md-1 col-sm-5"><i class="material-icons">aeroplane</i></div>
            <div class="col-md-1 col-sm-5"><i class="material-icons">apps</i></div>
            <div class="col-md-1 col-sm-5"><i class="material-icons">arrowright</i></div>
            <div class="col-md-1 col-sm-5"><i class="material-icons">build</i></div>
            </div>
        </div>
    </div>
</div>


<script>

    function showOverlay() {
        const overlay = document.getElementById('overlay');
        overlay.style.display = 'flex';
      }
      
      function hideOverlay() {
        const overlay = document.getElementById('overlay');
        overlay.style.display = 'none'; 
      }
    
    </script>

<style>
    .overlay i:hover{color:black;}
</style>
<div id="overlay" class="overlay">
    <div class="overlay-content">
      <p class="h3 w-25" style="margin-left: 3px;">Log in</p>
      <form action="./loginPHP.php" class="">
          <div class="col-12 mt-3">
            <div class="row d-block">
                    <div class="col-8" >
                        <div class="row mr-2">
                            <label for="email" class="m-2 w-25" style="font-size:20px; ">Email</label></div>
                            <input type="text" class="border border-1 email" id="email" style=" border: none; border-radius: 5px; height: 40px; width: 300px;">
                        </div>
                    <div class="col-8">
                        <div class="row mr-2">
                            <label for="password"style="font-size:20px;">Enter your password</label></div>
                            <input type="text" class="password border border-1" id="password" style=" border: none; border-radius: 5px; height: 40px; width: 300px;">
                        </div>
            </div>
        </div>
        <div class="col-8 offset-5 mt-3">
              <a href="#">Forgot your password</a>
        </div>
        <div class="col-12" style="margin-top: 40px; border-radius: 5px; font-size:20px;">
              <button class=" w-100 h-100 border border-1" style="font-size: 20px; border: none; border-radius: 10px; background-color: chartreuse;">Log in</button>
        </div>
        <div class="row mt-2">
          <p style="font-size:20px;">Don't have semrush account&nbsp;<a href="./signUpoverlay.html" style="text-decoration: none; font-size:20px;">Sign up</a></p>
        </div>
    </form>
    </div> 
  </div> 



</body>
</html>
](https://github.com/Ben13Jack/website-domain)
