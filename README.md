# searchBrowser

<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">

    <title>google search</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@1,100&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./css/style.css">
  </head>
  <body>
    

     <section class="bg-white">
         <div class="container-fluid">
             <!-- navbar -->
             <nav class="navbar navbar-expand-lg ">
                <a class="navbar-brand" href="#"><img src="./img/google1.png" alt=""></a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"><img src="./img/switch-on1.png" alt=""></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                  <ul class="navbar-nav ">
                    <li class="nav-item ">
                    <a class="nav-link text-dark" href="https://accounts.google.com/">Email</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link text-dark" href="https://www.google.co.in/imghp?hl=en&tab=ri&ogbl">Images</a>
                    </li>
                  </ul>
                </div>
              </nav>
             <!-- navbar -->


            
         </div>
     </section>
     <section class="mt-5">
         <div class="container-fluid">
        <div class="row justify-content-center brand mb-4" style="font-family: Arial, Helvetica, sans-serif; ">
            <span class="text-primary">S </span>
            <span class="text-danger"> e</span>
            <span class="text-warning">a</span>
            <span class="text-primary">r</span>
            <span class="text-success">c</span>
            <span class="text-danger">h</span>
            <span class="text-info">I</span>
            <span class="text-warning">t</span>
            
         </div>
         <div >
            <form class=" text-center " id="searchForm">
                <input type="text" id="resSea" class="btn-lg col-lg-5 rounded-pill"  placeholder="search here">
                <input type="submit" value="search" class="btn-lg rounded-pill mx-4 my-3">
            </form>
         </div>
        </div>
     </section>
     <section>
         <!-- results  -->
         <div class="container mt-5" id="loading">
            <div class="row" >
             <div class="col-8" >
              
                <div class="row " id="movieRes">
                    <!-- <div class="col-8  my-2" id="design"> -->
           
                   <!-- <p class="mb-n1">${res.displayed_url}</p>
                   <h4 id="colors">${res.title}</h4>
                   <p>${res.snippet}</p>
                   <p class="mt-n1">${res.domain}</p> -->
                
                   
                   </div>
             </div>
             <div class="col-4">
                <div id="mapres">
                    <!-- <div class="col-4"  >
                        <h5>title</h5>
                        <address></address>
                       <img src="" alt=""> -->
                    </div>
             </div>
            </div>
         
        </div>      
    
     </section>

     <section class="mt-5">
         <div class="container" >
            <ul class="row justify-content-between" id="queryRes">
                 
                <!-- <div class="col-sm-6 col-md-6 col-lg-6 mx-auto " id="queryRes"> -->
                   <!-- <a href="${res1.url}"><h5 class="rounded-pill">${res1.Squery}</h5></a> -->

            </ul>  
             </div>
         </div>
     </section>

     <footer class="page-footer font-small blue">

      <!-- Copyright -->
      <div class="footer-copyright text-right justify-content-end py-5">
        <h6><small>&copy;Ravi Prakash : All Rights Reserved</small></h6>
        
      </div>
      <!-- Copyright -->
    
    </footer>

    

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>

    <script src="./js/search.js"></script>
  </body>
</html>
