<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="assets/style/Style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Menu</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#achievment">Achievment</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact</a>
            </li>
           
          </ul>
        </div>
      </div>
    </nav>
    <!-- profile  -->
    <section id="Home" class="homes"> 
      <div class="container">
        <div class="profile">
          <img 
          class="rounded-circle profileimage" 
          src="assets/img/innahh.jpg" alt="innahh">
            <h2>설인아 </h2>
            <h3>Actress</h3>
        </div>
      </div>
    </section >
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#fff" fill-opacity="1" d="M0,224L48,213.3C96,203,192,181,288,149.3C384,117,480,75,576,85.3C672,96,768,160,864,165.3C960,171,1056,117,1152,117.3C1248,117,1344,171,1392,197.3L1440,224L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>
   
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
   
   <!-- about -->
    <section id="about" class="career">
      <div class="container">
        <h1 class="text-center about">ABOUT</h1>
        <div class="container text-center">
          <div class="row">
            <div class="col">
             <p>Seol in ah atau yang didkenal sebagai seorina merupakan seorang aktris asal wonogiri korea selatan dengan kelahiran 1997.</p>
            </div>
          <div class="col">
            <!-- Button trigger modal -->
<button type="button" class="btn btn-warning" data-bs-toggle="modal" data-bs-target="#exampleModal">
 SD
</button>
<button type="button" class="btn btn-warning" data-bs-toggle="modal" data-bs-target="#exampleModal5">
  SMP
</button>
<button type="button" class="btn btn-warning" data-bs-toggle="modal" data-bs-target="#exampleModal6">
  SMA
</button>

<!-- Modal1 -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel"> </h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        SDN Inchoen 
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">OK</button>
      </div>
    </div>
  </div>
</div>
<!-- modal2 -->
<div class="modal fade" id="exampleModal5" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel5"> </h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        SMPN Gangnam
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">OK</button>
      </div>
    </div>
  </div>
</div>
<!-- modal3  -->
<div class="modal fade" id="exampleModal6" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel6"> </h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        SMAN Gangdong
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">OK</button>
      </div>
    </div>
  </div>
</div>

</div>
<div class="col">
  inah memulai karir pertamanya sebagai aktris dalam sebuah drama korea yang berjudul " bussines proposal",debutnya bersama kim sejeong membawa namanya semakin dikenal. 
</div>
</div>
</div>
</div>
</section>
<!-- achievment -->
<section id="achievment" class="achievment text-center">
  <div class="container">
    <h1 class="achievment">ACHIEVMENT</h1>
    <div class="row">
      <div class="col-sm-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Tingkat Nasional</h5>
            <p class="card-text">berpartisipasi Dalam Kejuaraan Sepak Bola Internasional london 2069.</p>
            <button type="button" class="btn btn-warning" data-bs-toggle="modal" data-bs-target="#exampleModal2">
              see more
            </button>
            <div class="modal fade" id="exampleModal2" tabindex="-1" aria-labelledby="exampleModalLabel2" aria-hidden="true">
              <div class="modal-dialog">
                <div class="modal-content">
                  <div class="modal-header">
                    <h1 class="modal-title fs-5" id="exampleModalLabel2"> </h1>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                  </div>
                  <div class="modal-body">
                    JUARA UCL 15X
                  </div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary">OK</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Tingkat Kabupaten</h5>
            <p class="card-text">berpartisipasi dalam kejuaraan bola voli se-kabupaten 2019.</p>
            <button type="button" class="btn btn-warning" data-bs-toggle="modal" data-bs-target="#exampleModal3">
              see more
            </button>
            <div class="modal fade" id="exampleModal3" tabindex="-1" aria-labelledby="exampleModalLabel3" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel3"> </h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        JUARA 1 OLIMPIADE BOLA VOLI PARIS
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">OK</button>
      </div>
    </div>
  </div>
</div>

          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Tingkat Galaksi</h5>
            <p class="card-text">berpartisipasi dalam memperebutkan hatinya melawan orang kaya.</p>
            <button type="button" class="btn btn-warning" data-bs-toggle="modal" data-bs-target="#exampleModal4">
              see more
            </button>
            <div class="modal fade" id="exampleModal4" tabindex="-1" aria-labelledby="exampleModalLabel4" aria-hidden="true">
              <div class="modal-dialog">
                <div class="modal-content">
                  <div class="modal-header">
                    <h1 class="modal-title fs-5" id="exampleModalLabel4"> </h1>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                  </div>
                  <div class="modal-body">
                    MENANG BERSAING DENGAN ORANG KAYA 
                  </div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary">OK</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#fff" fill-opacity="1" d="M0,192L40,202.7C80,213,160,235,240,208C320,181,400,107,480,106.7C560,107,640,181,720,192C800,203,880,149,960,149.3C1040,149,1120,203,1200,202.7C1280,203,1360,149,1400,122.7L1440,96L1440,320L1400,320C1360,320,1280,320,1200,320C1120,320,1040,320,960,320C880,320,800,320,720,320C640,320,560,320,480,320C400,320,320,320,240,320C160,320,80,320,40,320L0,320Z"></path></svg>
<!-- contact  -->
<section id="contact" class="footer">
  <div class="contact-footer"><h1>CONTACT</h1></div>
    <div class="container text-center contact">
      <a href="https://www.instagram.com/_seorina/"><i class="fa-brands fa-square-instagram"></i></a>
      <a href="https://x.com/realmadrid"><i class="fa-brands fa-square-twitter"></i></a>
      <a href="https://www.youtube.com/@WindahBasudara"><i class="fa-brands fa-square-youtube"></i></a>
      <a href="https://github.com/"><i class="fa-brands fa-square-github"></i></a>
    </div>
    <div class="text-center"><p>created by xennz.2024</p></div>
</section>
</body>
</html>
