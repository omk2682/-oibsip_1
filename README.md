<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
    <style type="text/css">
        *{padding:0;margin:0;box-sizing: border-box;}
        header{
            width: 100%;
            height: 100vh;
            background: url('/images/travelling\ image.jpg');
            background-size: cover;
            font-family: sans-serif;
        }
        nav{
            width:100%;
            height:100px;
            color:white;
            display:flex;
            justify-content: space-around;
            align-items: center;
        }
        .logo{
            font-size:2em;
            letter-spacing: 2px;
        }
        .menu a{
            text-decoration: none;
            color:white;
            padding: 10px 20px;
            font-size: 20px;
            position:relative;
        }
        .menu a:before{
            content:'';
            position:absolute;
            top:0;
            left:0;
            width:0%;
            height:100%;
            border-bottom: 2px solid indianred;
            transition: 0.4s linear;
        }
        .menu a:hover:before{
            width:90%;
        }
        .register a{
            text-decoration: none;
            color:white;
            padding: 10px 20px;
            font-size: 20px;
            background: indianred;
            border-radius: 8px;
            transition: 0.4s;
        }
        .register a:hover{
            background: transparent;
            border: 1px solid indianred;
        }

        .h-txt{
            max-width: 650px;
            position:absolute;
            top:50%;
            left:50%;
            transform: translate(-50%,-50%);
            text-align: center;
            color:white;
        }
        .h-text span{
            letter-spacing: 5px;
        }
        .h-txt h1{
            font-size: 3.5em;
        }
        .h-txt a{
            text-decoration: none;
            background:indianred;
            color:white;
            padding:10px 20px;
            letter-spacing: 5px;
            transition:0.4s;
        }
        .h-txt a:hover{
            background: transparent;
            border: 1px solid indianred;
        }
    </style>
</head>
<body>
    <header>
       <nav>
        <div class="logo">
            TRIPIFY
        </div>
        <div class="menu">
            <a href="#">HOME</a>
            <a href="#">TRENDING LOCATIONS</a>
            <a href="#">BEST OFFERS</a>
            <a href="#">SERVICES</a>
            <a href="#">CONTACT</a>
        </div>
        <div class="register">
            <a href="#">REGISTER</a>
        </div>
       </nav>
       <section class="h-txt">
        <span>EXPLORE</span>
        <h1>INTERNATIONAL TRAVEL AGENCY</h1>

        <br>
        <a href="#">Book your Trip</a>
       </section>
       <footer>
        <div class="footer-content">
            <ul class="socials">
                <li><a href="https://www.facebook.com/yash.chhajed.104" ><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
                <li><a href="https://github.com/YashChhajed/oibsip_1.git"><i class="fa fa-github" aria-hidden="true"></i></a></li>
                <li><a href="https://www.instagram.com/yash_1101_"><i class="fa fa-instagram" aria-hidden="true"></i></a></li>
                <li><a href="https://www.linkedin.com/in/yash-chhajed-a10185231/"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
            </ul>
        </div>
        <div class="footer-bottom">
            <p>copyright &copy;2022 tripify.made in <span>❤️ with India</span></p>
        </div>
       </footer>
       
    </header>
        
    </div>  
    
</body>
</html>
