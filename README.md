<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EBELAA Lifestyle</title>
    <style>
        *{margin:0;padding:0;box-sizing:border-box;font-family:'Segoe UI',sans-serif;}
        body{background:#f8fafc;color:#1e293b;}
        header{
            background:linear-gradient(135deg,#1e40af,#3b82f6);
            padding:12px 20px;
            position:fixed;
            width:100%;
            top:0;
            z-index:1000;
            box-shadow:0 4px 15px rgba(0,0,0,0.1);
        }
        .logo{
            display:flex;
            align-items:center;
            color:white;
            font-size:26px;
            font-weight:900;
            text-decoration:none;
        }
        .logo img{
            height:55px;
            margin-right:15px;
            border-radius:10px;
        }
        nav{float:right;margin-top:12px;}
        nav a{
            color:white;
            text-decoration:none;
            margin-left:22px;
            font-weight:600;
        }
        .hero{
            height:100vh;
            background:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.6)), url('https://source.unsplash.com/random/1600x900/?fashion') center/cover;
            display:flex;
            flex-direction:column;
            justify-content:center;
            align-items:center;
            text-align:center;
            color:white;
            padding-top:80px;
        }
        .hero h1{font-size:50px;margin-bottom:15px;}
        .hero p{font-size:22px;margin-bottom:35px;}
        .btn{
            background:#fbbf24;
            color:#1e293b;
            padding:16px 45px;
            border-radius:50px;
            font-weight:bold;
            text-decoration:none;
            font-size:19px;
        }
        .whatsapp{
            position:fixed;
            bottom:20px;
            right:20px;
            background:#25d366;
            color:white;
            width:65px;
            height:65px;
            border-radius:50%;
            display:flex;
            align-items:center;
            justify-content:center;
            font-size:35px;
            box-shadow:0 5px 20px rgba(0,0,0,0.3);
            z-index:999;
        }
        @media(max-width:768px){
            .hero h1{font-size:38px;}
            .hero p{font-size:18px;}
            nav{float:none;text-align:center;margin-top:20px;}
            nav a{margin:0 12px;font-size:15px;}
        }
    </style>
</head>
<body>

<header>
    <a href="#" class="logo">
        <img src="logo.png" alt="EBELAA Logo">
        EBELAA Lifestyle
    </a>
    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h1>EBELAA Lifestyle</h1>
    <p>Premium Fashion from Lakshmipur, Bangladesh</p>
    <a href="#products" class="btn">Explore Collection</a>
</section>

<a href="https://wa.me/88017xxxxxxxxxx" class="whatsapp" target="_blank">WhatsApp</a>

</body>
</html>
