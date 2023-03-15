# ES-PROJECT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>eTechno Solutions</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
</head>
<body>
    
    /* Navbar styling */
.navbar-expand-lg {
    background-color: hsl(340, 17%, 86%);
    box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
    
   
}


.navbar-brand {
    width: 380px;
    height: 120px;
}
  

.nav-link {
    font-size: 1.2rem;
    margin-right: 1rem;
    font-weight: 650;
    padding: 5px 0px;
    border: black;
    box-sizing: border-box;
    box-shadow: thistle;
    color: black;
}


h1{
    color: black;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

p {
    color: rgb(13, 13, 13);
    font-size: medium;
    
}

span{
    font-weight: 700;
}

.navbar-toggler-icon {
    background-image: url("data:image/svg+xml,%3csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3e%3cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");
}

/* Jumbotron styling */
.jumbotron {
    background-color: cadetblue;
    background-size: cover;
    background-position: center;
    color: #fff;
    padding: 5rem;
}

/* Development section styling */
#development {
    background-color: #f7f7f7;
    padding: 5rem 0;
    text-align: center;
    padding-bottom: 5px;
}

.aligncenter{
    text-align: center;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;

}

.img{
    text-align: left;
    background: transparent;
    padding-bottom: 10px;
}

b{
    font-size: larger;
    text-underline-offset: auto;
}

p{
    font-size: larger;
}
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg">
        <div>
            <img class="navbar-brand" src="images/img.1.jpg" alt="">
        </div>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Development</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Training</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Digital Marketing</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">SAP Courses</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Jumbotron -->
    <div class="jumbotron jumbotron-fluid">
        <div class="container">
            <h1 class="display-4">Welcome to eTechno Solutions</h1>
            <p class="lead"><span> Offer Expert Solutions for Development, Training, and Digital Marketing. Enroll in our SAP Courses to advance your career.</span></p>
        </div>
    </div>

    <!-- Development Section -->
    <section class="ABOUT Our Company">
        <div class="container">
            <div class="row">
                <div class="col-md-12" data-aos="zoom-in">
                    <div class="aligncenter">
                        <h2 class="aligncenter">ABOUT Our Company</h2>

                    </div>
                    <br/>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6"data-aos="fade-right">
                    <img class="img" src="images/img.5.jpg" alt="">
                    <div class="space"></div>
                </div>
                <div class="col-md-6"data-aos="fade-left">
                    <p><b>ETECHNO SOLUTION:- </b> <br>
                        Etechno Solution, is a Global provider of high quality Information Technology services in the areas of Enterprise Resource Planning (ERP), Customer Relationship Management (CRM), Data Warehousing, e-Business related technologies. Vendor specific technologies include SAP, Oracle, Microsoft, Java and IBM.
                        
                       
                    </p>
                    <p><b>Find Best Web Designing Company:- </b> <br>
                        If you're seeking for the Best Web Design Company, there are several considerations that you have to keep in mind. You want to choose a Web Designer that has a good experience of the industry and who has gained a good reputation within his or her industry. A Professional Web Designer should also be able to deliver excellent design, SEO strategies, search engine optimization, and good communication skills.

                </div>
            </div>

        </div>
    </section>

    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
        AOS.init({
         duration: 1500
     });
       </script>
