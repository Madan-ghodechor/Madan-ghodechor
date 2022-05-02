<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-fQybjgWLrvvRgtW6bFlB7jaZrFsaBXjsOMm/tB9LTS58ONXgqbR9W8oWht/amnpF" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="website.css">
    <link rel="shortcut icon" href="favicon.ico">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

     <!-- Style CSS -->
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="dist/color-default.css">
    <link rel="stylesheet" href="dist/color-switcher.css">
    <link rel="stylesheet" href="css/fonts.css">
    <link rel="stylesheet" href="css/jquery.fancybox.css">
    <link rel="stylesheet" href="css/magnific-popup.css">
    <link rel="stylesheet" href="css/style_slider.css">
    <link rel="stylesheet" href="css/font-awesome.css">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/owl.css">
    <link rel="stylesheet" href="rs-plugin/css/settings.css">
    <link href="https://fonts.googleapis.com/css?family=Josefin+Sans:100,100i,300,300i,400,400i,600,600i,700,700i" rel="stylesheet">
    <script src='https://kit.fontawesome.com/a076d05399.js' crossorigin='anonymous'></script>
    <title> This is the Big Website demo </title>
    <style>
      .homecont{
    height: 650px;
     }
.nav-link{
    color: white !important;
    margin-left: 20px;
    font-size: 18px;
}
.nav-link:hover{
    color: goldenrod !important;
}
.nav_row{
    position: sticky;
}
.hedding_text{
    font-size: 70px !important;
    font-weight: 700;
    margin-top: 30px;
}
.hedding_text_down{
    font-weight: 600 !important;
    margin-top: 30px;
}
.btnhomes{
    color: white;
    outline: white !important;
    height: 40px;
    width: 200px;
}

#about-us{
    margin-top: 40px;
}
.mahiti{
    border: 2px solid rgb(230, 230, 230);
    height: 250px;
    width: 350px;
    padding-top: 55px !important;
    margin-top: 30px;
    background-color: rgb(245, 245, 245);
}
.mahiti:hover{
    background-color: white;
    border: none;
    box-shadow: 0px 0px 10px rgb(116, 116, 116);
    transition: 0.8s;
}
.boxchota{
    height: 60px;
    width: 80px;
    border: 2px solid silver;
    background-color: white;
    position: absolute;
    top:0px;
    right: 148px;
    /* z-index: 99999; */
}

.info_cards:hover .boxchota{
    background-color: rgb(255, 196, 0) !important;
    transition: 0.7s;
}

.info_cards:hover .icon{
    color: white !important;    
}

.btn_jobs{
    display: flex;
    justify-content: center;
}
.img_jobs{
    height: 250px !important;
    width: 300px !important;
}

.box_2{
    height: 100%;
    width: 70%;
    border: 2px solid rgb(255, 187, 0);
    border-radius: 15px;
}
.div_img img{
    height: 80px;
    width: 80px;
    border-radius: 50%;
    border: 3px solid white;
}
.div_img{
    height: 80px;
    width: 100%;
    background-color: transparent;
    display: flex;
    justify-content: center;
}
.form_cont{
  width: 1000px;
  background-color: white;
}

@media(max-width:627px){
    .boxchota{
        height: 60px;
        width: 80px;
        border: 2px solid silver;
        background-color: rgb(255, 255, 255);
        position: absolute;
        top:0px;
        right: 125px !important;
    }
    .dot{
         margin-left: 150px !important; 
         background-color: red;
    }
    .homecont{
        height: 900px;
    }
    .botans{
        width: 96% !important;
        margin-left: 18px !important;
    }
    .box_2{
        margin: auto !important;
    }
    .input_form{
        height: auto;
        width: 100% !important;
        margin-top: 10px !important;
    }
    .btnhomes{
        height: 40px !important;
        width: 40% !important;
    }


}
    </style>
</head>
<body>
   <div class="homecont container-fluid "style="background-image:url(https://jooinn.com/images/golden-gate-bridge-62.jpg);background-size:cover;">
        <div class="container" >
            <div class="row nav_row">
                <div class="col-3 col-md-2 text-center">
                    <img src="https://encrypted-tbn0.gstatic.com/imagesq=tbn:ANd9GcRpK5AqsYx0FgTm38guP7_ugMoCrLzClWRZyg&usqp=CAU" class="mt-2 mb-2" style="height: 50px; width: 80px;border-radius: 20px;">
                </div>
    
    
                <div class="meus col-9 col-md-10">
                    <nav class="navbar navbar-expand-lg navbar-light bg-transparent">
                        <!-- <a class="navbar-brand" href="#">Navbar</a> -->
                        <button class="dot navbar-toggler btn-outline-warning" style="margin-left: 190px;" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                          <span class="navbar-toggler-icon ml-2 mr-2 "></span>
                        </button>
                      
                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                          <ul class="navbar-nav ">
                            <li class="nav-item active">
                                <a class="nav-link" href="#home">Home</a>
                            </li>  
                            <li class="nav-item active">
                                <a class="nav-link" href="#about">About us</a>
                            </li>                        
                            <li class="nav-item active">
                                <a class="nav-link" href="#services">Services</a>
                            </li>  
                            <li class="nav-item active">
                                <a class="nav-link" href="#portfolio">Portfolio</a>
                            </li>  
                            <li class="nav-item active">
                                <a class="nav-link" href="#team">team</a>
                            </li>
                            <li class="nav-item active">
                                <a class="nav-link" href="#blog">Blog</a>
                            </li>    
                            <li class="nav-item active">
                                <a class="nav-link" href="#contact">Contact</a>
                            </li>   
                          </ul>
                        </div>
                      </nav>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <p class="text-white text-center mt-5">Valli Business HTML5 Template</p>
                </div>
                <div class="col-md-12">
                    <h1 class="hedding_text text-white text-center">
                        We Are <span class="text-warning">Strategy</span> Business
                    </h1>
                    <p class="hedding_text_down text-white text-center text-b">Lorem ipsum dolor sit, amet consectetur
                         adipisicing elit. Quod quam vel eos! Nisi omnis
                          dignissimos eligendi dicta vitae quas ex placeat natus quisquam quibusdam repellat,
                         voluptatibus ducimus incidunt quia eos.</p>
                </div>
            </div>
        </div>
        <div class="container mt-3">
            <div class="row">
                <div class="col-md-12 text-center">
                           <button class="btnhomes btn btn-outline-warning mt-4 mb-5 ">Get Started </button>
                           <button class="btnhomes btn btn-outline-warning mt-4 mb-5">Get Started </button>
                </div>
            </div>
        </div>
   </div>

   <!-- from this about us section start  -->
   <section id="about-us">
    <div class="about-info">
      <div class="s-header-shape"></div>
      <!--container start-->
      <div class="container"> 
        <!--row start-->
        <div class="row"> 
          <!--col start-->
          <div class="col-md-6">
            <div class="about-img"> <img src="https://st4.depositphotos.com/1485837/28401/i/450/depositphotos_284018646-stock-photo-neon-light-portrait-of-bearded.jpg" class="w-100" 
                     style="height: 420px;"      alt="Image"> </div>
          </div>
          <!--col end--> 
          <!--col start-->
          <div id="about"class="col-md-6">
            <div class="single_about">
              <div class="section-title">
                <h3 style="font-weight:700; font-size:40px;">About <span class="text-warning">Us</span></h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce aliquet, massa ac ornare feugiat, nunc dui auctor ipsum, sed posuere eros sapien id quam.Lorem ipsum dolor sit amet, consectetur adipiscing elit..</p>
              </div>
              <div class="about-description">
                <div class="team-skills">
                  <p>UI/UX</p>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:90%"><span>90%</span></div>
                  </div>
                  <p>Bootstrap</p>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100" style="width:70%"><span>70%</span></div>
                  </div>
                  <p>JavaScript</p>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:90%"><span>90%</span></div>
                  </div>
                  <p>WordPress</p>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100" style="width:70%"><span>70%</span></div>
                  </div>
                </div>
                    <button class="btn-dark mt-3 btn-large">Hire Me</button>
                </div>
            </div>
          </div>
          <!--col end--> 
        </div>
        <!--row end--> 
      </div>
      <!--container end--> 
    </div>
  </section>


    <!-- best services section starts -->
  <section id="services" class="mt-3">
      <div class="container mt-5 mb-3">
          <div class="row">
              <div class="col-md-12">
                  <h1 class="text-dark text-center">OUR BEST <span class="text-warning">SERVICES</span></h1>
              </div>
    </div>
     </div>
  </section>

  <div class="container">
      <div class="row">
          <div class="col-md-4 text-center mt-3">
              <div class="info_cards">
                <div class="boxchota"> 
                    <i class="icon fa fa-credit-card pt-1" style="font-size:48px;color:rgb(255, 187, 0)"></i>
                   </div>
                   <div class="mahiti">
                       <h5>ECOMMERCE SOLUTION</h5>
                       <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has dummy text.</p>
                   </div>
              </div>
          </div>
          <div class="col-md-4 text-center mt-3">
            <div class="info_cards">
              <div class="boxchota"> 
                  <i class="icon fa fa-graduation-cap mt-1" style="font-size:48px;color:rgb(255, 196, 0)"></i>
                 </div>
                 <div class="mahiti">
                     <h5 class="text-uppercase">Business Financing</h5>
                     <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has dummy text.</p>
                 </div>
            </div>
          </div>
          <div class="col-md-4 text-center mt-3">
            <div class="info_cards">
              <div class="boxchota"> 
                  <i class="icon fa fa-train pt-1" style="font-size:48px;color:rgb(255, 187, 0)"></i>
                 </div>
                 <div class="mahiti">
                     <h5 class="text-uppercase">Product Marketing</h5>
                     <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has dummy text.</p>
                 </div>
            </div>
          </div>
          <div class="col-md-4 text-center mt-5">
            <div class="info_cards">
              <div class="boxchota"> 
                  <i class="icon fa fa-shopping-bag pt-1" style="font-size:48px;color:rgb(255, 187, 0)"></i>
                 </div>
                 <div class="mahiti">
                     <h5 class="text-uppercase">Business Idea</h5>
                     <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has dummy text.</p>
                 </div>
            </div>
          </div>
          <div class="col-md-4 text-center mt-5">
            <div class="info_cards">
              <div class="boxchota"> 
                  <i class="icon fa fa-rocket pt-1" style="font-size:48px;color:rgb(255, 187, 0)"></i>
                 </div>
                 <div class="mahiti">
                     <h5 class="text-uppercase">Custom portfolio</h5>
                     <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has dummy text.</p>
                 </div>
            </div>
          </div>
          <div class="col-md-4 text-center mt-5">
            <div class="info_cards">
              <div class="boxchota"> 
                  <i class="icon fa fa-user pt-1" style="font-size:48px;color:rgb(255, 187, 0)"></i>
                 </div>
                 <div class="mahiti">
                     <h5 class="text-uppercase">Brand Promotion</h5>
                     <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has dummy text.</p>
                 </div>
            </div>
          </div>
      </div>
  </div>

    <!-- Business activites video section starts  -->
    <div class="container-fluid mt-5" style="background-image: url(https://www.asmboats.com/wp-content/uploads/2019/05/asm-34-min.jpg);">
      <div class="row">
        <div class="col-12">
            <h1 class="text-warning text-center pt-5 mt-3" style="font-size: 50px;">Business Activites Video</h1>
        </div>
        <div class="col-12">
             <p class="text-center text-white text-shadow p-0" style="font-size: 30px; text-shadow: 1px 1px black;">Creative Agency</p>
        </div>
        <div class="col-12">
              <i class="fa fa-play-circle mb-5 mt-3" style="font-size:68px;color:rgb(255, 208, 0);display: flex; justify-content: center;"></i>
        </div>

      </div>
    </div>

    <!-- Our  Recent Portfolios  -->
    <div id="portfolio" class="container mt-4">
      <div class="row">
            <div class="col-12">
           <h1 class="text-uppercase text-center mt-4"> Our Recent <span class="text-warning">portfolios</span></h1>
            </div>

           <div class="col-12">
           <p class="text-center text-dark mt-2">
             Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolore cupiditate, tenetur sunt accusantium obcaecati eaque,
              doloribus fugiat voluptatum incidunt exercitationem pariatur quae, laudantium expedita sit vero fuga deserunt blanditiis perspiciatis?
           </p>
           </div>

           <div class="btn_jobs w-100">
             <div class="row ">
                <div class="col-md-2">
                    <button class="botans btn btn-outline-info mt-3 ml-1 mr-1">All Jobs</button>
                </div>
                <div class="col-md-2">
                     <button class="botans btn btn-outline-info mt-3 ml-1 mr-1">Branding</button>
                </div>
                <div class="col-md-2">
                     <button class="botans btn btn-outline-info mt-3 ml-1 mr-1">Financing</button>
                </div>
                <div class="col-md-2">
                     <button class="botans btn btn-outline-info mt-3 ml-1 mr-1">Marketing</button>
                </div>
                <div class="col-md-2">
                     <button class="botans btn btn-outline-info mt-3 ml-1 mr-1">Promotion</button>
                </div>
             </div>
           </div>

           <div class="col-md-4 mt-5 pb-2 rounded shadow" style="display: flex; justify-content: center;">
               <img src="https://media.gettyimages.com/photos/grey-tshirt-on-white-background-picture-id1166499523?b=1&k=20&m=1166499523&s=170667a&w=0&h=B4ymxPXjjBUn1EdmHGdUH5DeTiPoiot6GzKVoepQfKg=" 
               class="img_jobs w-100 h-100 rounded">
           </div>
           <div class="col-md-4 mt-5 pb-2 rounded shadow" style="display: flex; justify-content: center;">
               <img src="https://img.freepik.com/free-photo/off-white-coffee-cup-with-hot-steam-smoke-wooden-table-grey-background-white-black_362520-1315.jpg" class="img_jobs w-100 h-100 rounded">
            </div>
            <div class="col-md-4 mt-5 pb-2 rounded shadow" style="display: flex; justify-content: center;">
               <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFK8h9QJlf-F_x0CtOytQ-0wjlayZWsS0xNw&usqp=CAU" class="img_jobs w-100 h-100 rounded">
             </div>

             <div class="col-md-4 mt-5 pb-2 rounded shadow" style="display: flex; justify-content: center;">
              <img src="data:image/jpeg;base64,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" 
              class="img_jobs w-100 h-100 rounded">
            </div>
             <div class="col-md-4 mt-5 pb-2 rounded shadow" style="display: flex; justify-content: center;">
              <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ3v6B0NZNSYFxqFC5-VJ94tMmbr0Fiqo5igQ&usqp=CAU" class="img_jobs w-100 h-100 rounded">
             </div>
            <div class="col-md-4 mt-5 pb-2 rounded shadow" style="display: flex; justify-content: center;">
              <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcScrzA7f3cdcrBr6tJCY5zWhTJlSAPBvc-Geg&usqp=CAU" class="img_jobs w-100 h-100 rounded">
            </div>

      </div>
    </div>

    <!-- Our team  -->
    <div id="team" class="container">
      <div class="row">
        <div class="col-md-12 mt-5">
           <h1 class="text-center text-uppercase">Our <span class="text-warning">team</span></h1>
        </div>
        <div class="col-md-12 mt-3">
           <p class="text-dark text-center">
             Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
             Atque, ex commodi, quidem dolores quas sequi molestiae assumenda
              eos accusamus in fugit consectetur placeat at pariatur 
              asperiores similique doloribus ab. Maiores.
           </p>
        </div>
         <div class="col-md-4 shadow p-3">
            <img src="https://wallpapercave.com/wp/wp6196277.jpg" class="h-100 w-100 rounded">
         </div>
          <div class="col-md-4 shadow p-3">
            <img src="https://c0.wallpaperflare.com/preview/516/857/262/adult-boy-casual-close-up.jpg" class="h-100 w-100 rounded">
         </div>
          <div class="col-md-4 shadow p-3">
            <img src="https://c.stocksy.com/a/uVN100/z9/328718.jpg" class="h-100 w-100 rounded">
          </div>
      </div>
    </div>

    <!-- our latest blog -->
    <div id="blog" class="container">
      <div class="row">
        <div class="col-12">
          <h1 class="text-center text-uppercase mt-5 mb-3">our latest <span class="text-warning">blog</span></h1>
        </div>
        <div class="col-12">
          <p class="mt-3 text-dark text-center">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit.
             Voluptatem, inventore quos autem velit culpa at?
              Temporibus maiores ipsam asperiores voluptatibus
               praesentium minima ipsa ea, laborum, nam ab, voluptate ex. Nostrum.
          </p>
         </div>
         <div class="col-md-4 shadow p-3">
            <div class="card">
            <img src="https://cdn2.hubspot.net/hubfs/3928454/What%20Are%20the%20Benefits%20of%20Having%20a%20Software%20Development%20Team.jpg" class="card-img-top w-100" style="height: 215px;">
            <div class="card-body">
              <h6 class="card-title text-warning p-0" style="font-size:19px; ">Duis ultricies aliquet mauris</h6>
              <br>
              <p class="text-center" style="font-size:medium;">By: <span style="font-weight: 700;">Admin</span> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; On :<span style="font-weight: 700;"> 1 may 2022</span> </p><hr>
              <p class="">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                 Sapiente ratione voluptatum sunt fuga quas vero similique accusantium 
              </p>
              <a href="#" class="btn btn-outline-white" style="font-weight: 700;">Read more</a>
            </div>
             </div>
         </div>
            <div class="col-md-4 shadow p-3">
            <div class="card">
            <img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/tester-or-developer-what-suits-you-the-most.jpg" class="card-img-top w-100" style="height: 215px;">
            <div class="card-body">
              <h6 class="card-title text-warning p-0" style="font-size:19px; ">Duis ultricies aliquet mauris</h6>
              <br>
              <p class="text-center" style="font-size:medium;">By: <span style="font-weight: 700;">Admin</span> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; On :<span style="font-weight: 700;"> 1 may 2022</span> </p><hr>
              <p class="">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                 Sapiente ratione voluptatum sunt fuga quas vero similique accusantium 
              </p>
              <a href="#" class="btn btn-outline-white" style="font-weight: 700;">Read more</a>
            </div>
             </div>
         </div>
            <div class="col-md-4 shadow p-3">
            <div class="card">
            <img src="https://www.bcs.org/media/8595/students-code.jpg?anchor=center&mode=crop&width=500&height=500&rnd=132914889170000000" class="card-img-top w-100" style="height:215px;">
            <div class="card-body">
              <h6 class="card-title text-warning p-0" style="font-size:19px; ">Duis ultricies aliquet mauris</h6>
              <br>
              <p class="text-center" style="font-size:medium;">By: <span style="font-weight: 700;">Admin</span> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; On :<span style="font-weight: 700;"> 1 may 2022</span> </p><hr>
              <p class="">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                 Sapiente ratione voluptatum
                  sunt fuga quas vero similique accusantium 
              </p>
              <a href="#" class="btn btn-outline-white" style="font-weight: 700;">Read more</a>
            </div>
             </div>
         </div>
         <div class="col-12 mt-4" style="display: flex; justify-content: center;">
          <div class="btn-toolbar" role="toolbar" aria-label="Toolbar with button groups">
            <div class="btn-group " role="group" aria-label="First group">
              <button type="button" class="btn btn-outline-warning">1</button>
              <button type="button" class="btn btn-outline-warning">2</button>
              <button type="button" class="btn btn-outline-warning">3</button>
              <button type="button" class="btn btn-outline-warning">4</button>
              <button type="button" class="btn btn-outline-warning">5</button>
              <button type="button" class="btn btn-outline-warning">6</button>
              <button type="button" class="btn btn-outline-warning">7</button>
              <button type="button" class="btn btn-outline-warning">8</button>
            </div>
          </div>
         </div>
      </div>
    </div>

    <!-- testimonial section starts form this  -->
    <div class="container-fluid mt-5" style="background-image: url(https://p1.pxfuel.com/preview/560/275/659/pencil-write-notebook-paper-desk-wooden.jpg);">
      <div class="row" style="background-color: rgba(0, 0, 0, 0.712);">
         <div class="col-12 ">
           <h1 class="text-center text-uppercase text-white mt-5" style="font-weight: 500;">testimonials</h1>
         </div>


          <div class="col-md-6 mt-4 mb-5" style="display:flex; justify-content: right;">
           <div class="box_2">
               <h5 class="text-white text-center text-uppercase mt-3">good experience with abc company...!</h5>
               <p class="text-white pr-4 pl-4 pb-2" style="font-size: 15px;">
                <i>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                  Quibusdam adipisci doloribus exercitationem, quidem placeat dignissimos eos aliquid mollitia, quisquam esse,
                   ducimus aliquam impedit distinctio sunt optio consequuntur qui. Maiores, in?
                </i>
               </p>
               <div class="div_img">
                  <img src="https://c0.wallpaperflare.com/preview/516/857/262/adult-boy-casual-close-up.jpg" class="box_images">
               </div>
                  <p class="text-warning text-center mt-2 mb-0"> John Doe</p>
                  <p class="text-white text-center"> -Manager</p>
           </div>
          </div>


          <div class="col-md-6 mt-4 mb-5">
           <div class="box_2">
               <h5 class="text-white text-center text-uppercase mt-3">good experience with abc company...!</h5>
               <p class="text-white pr-4 pl-4 pb-2" style="font-size: 15px;">
                <i>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                  Quibusdam adipisci doloribus exercitationem, quidem placeat dignissimos eos aliquid mollitia, quisquam esse,
                   ducimus aliquam impedit distinctio sunt optio consequuntur qui. Maiores, in?
                </i>
               </p>
               <div class="div_img">
                  <img src="https://c0.wallpaperflare.com/preview/516/857/262/adult-boy-casual-close-up.jpg" class="box_images">
               </div>
               <p class="text-warning text-center mt-2 mb-0"> John Doe</p>
               <p class="text-white text-center"> -Manager</p>
           </div>
         </div>
      </div>
    </div>

    <!-- this is the form section  -->
  
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-12 p-0 m-0 mt-5" style="height:450px;">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d30355.066699743064!2d76.05533188154405!3d18.007404927103135!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bc5be0a40876f91%3A0x57fb8af728b88e9d!2z4KSk4KWB4KSz4KSc4KS-4KSq4KWC4KSwLCDgpK7gpLngpL7gpLDgpL7gpLfgpY3gpJ_gpY3gpLAgNDEzNjAx!5e0!3m2!1smr!2sin!4v1651405259108!5m2!1smr!2sin" style="border:0;" class="p-0 w-100 h-100"></iframe>
        </div>
                  <!-- this is the form section  -->
         <div id="contact" class="form_cont container shadow mt-4">
            <div class="row">
         <div class="col-md-6 mt-5 mb-5 p-4">
           <h1 class="text-uppercase">get in touch</h1>
           <p>
             Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Inventore, nesciunt. Aut aliquid inventore autem 
              placeat labore sapiente voluptate nemo, sit eum quos
              dicta tempora culpa nihil sequi, excepturi quo cupiditate.
           </p>
           <h4> <i class="fa fa-map-marker" style="font-size:30px"></i>
            Address </h4>
           <p class="pt-0"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8005 lorem, New lspum, Dolor <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;amet sit 12301 </p> <br>

           <h4> <i class="fa fa-phone" style="font-size:30px"></i>
            Phone </h4>
           <p class="pt-0">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; +91 9309804106 <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; +91 9309804106 </p>

           <h4> <i class="fa fa-envelope" style="font-size:30px"></i>
            E-Mail</h4>
           <p class="pt-0">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Aikyam_hindustav2001@gmail.com </p>
           
         </div>
         <div class="col-md-6 mt-5 mb-5 p-4">
           <h1 class="text-uppercase">drop us a line</h1>
           <p class="text-secondary">
             Lorem ipsum dolor sit amet consectetur adipisicing elit. 
             Reprehenderit dolor ipsa, fugiat voluptatibus eos eum hic 
            </p>
            <input class="input_form"  type="text" placeholder="   Name" class="text-secondary"  style="width: 48.5%; height: 35px;">
            <input class="input_form"  type="text" placeholder="   Email" class="text-secondary ml-2"  style="width: 48.5%; height: 35px;">
            <textarea placeholder="   Message"  rows="9" class="text-secondary mt-3" style="width: 100%;"></textarea>
            <button class="btn btn-dark text-uppercase"> send Message</button>
         </div>
             </div>
           </div>
      </div>
    </div>

    <!-- this is my personal info  -->
    <div class="container mt-5">
        <div class="row">
            <div class="col">
                <p class="text-secondary  text-center" style="font-size:10px;">
                    Developed By :- <br>
                    @Madanghodechor <br>
                    9309804106
                </p>
            </div>
        </div>
    </div>
    <br><br><br><br><br><br><br><br><br><br><br><br><br><br>
</body>
</html>
