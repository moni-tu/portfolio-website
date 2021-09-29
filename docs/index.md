<!DOCTYPE html>

<html>
        
    <head>
        <meta charset="utf-8">
        <title>Monica Turani Web Developer Portfolio </title>
        <link rel="icon" href="Img/Monica_icon.png">
        <!-- viewport is the user's visible area of a web page-->
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" type="text/css" href="CSS/normalize.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
        <link rel="stylesheet" type="text/css" href="./css/style.production.css">
    </head>

    

    <body>
        <header class="page-header">

            <img src="./Img/Monica-logo.png" alt= "logo" class="Monica-logo">
        
            <nav class="page-header_item navigation-list" role="menubar"> 
                <ul>
                    <li>
                        <!-- HTML checker says the following alt element should not be allowed at this point -->
                        <a href="Index.html" alt= "Home" role="menuitem" class="navigation-list_item navigation-list_item--active"> Home </a>
                    </li>
                    
                    <li role="presentation">
                        <a href="About.html" role="menuitem" alt= "About" class="navigation-list_item" > About-me </a>     
                    </li>

                    <li>
                        <a href="work.html" role="menuitem" alt="my-work" class="navigation-list_item"> My Work </a>
                    </li>
        
                    <li>
                        <a href="Contact.html" alt= "Contact" class="navigation-list_item"> Contact </a>
                    </li>
                </ul>    
            </nav>
        </header>
    

        <div class="profile">
            <img src="./Img/Monica portrait_icon.jpeg" alt= "Image of me" class="profile_portrait">
            <h1> Hi Everyone! </h1>
            <p> My name is Monica and I am a <span>web</span> developer from Italy. I believe that re-inventing oneself and keep learning is the key to a fulfilling life. 
                I am excited to set on a new journey in my professional life 
            </p>
            <a href="#"> Check out some of my code </a>
        </div>
        
        <footer class="page-footer">
            <p>Find me on </p>
            <div class="social-media">
                <!--HTML checker says 30px is a bad value for width and height-->
                <img src="img/insta_icon.png" alt="Instagram" width="30px" height="30px"> 
                <img src="img/face_icon.png" alt="Facebook" width="30px" height="30px">
            </div>
            
        </footer> 

    </body>

    <!-- HTML checker says the following is a stray start tag-->
    <script src="js/tota11y.min.js"> </script>
</html>


