# Helloworld
Just basic 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css">
    <title>CA Amit Tenani</title>
    <style>
        *{
    margin: 0;
    padding: 0;
}

html{
    scroll-behavior: smooth;
}

#navbar
{
    display: flex;
    justify-content: center;
    position: sticky;
    top: 0px;
    background-color: black;
}
#navbar ul
{
    display: flex;
    flex-direction: row;
    list-style: none;
    
    margin: 0%;
    font-size: 1.5rem;
}
#navbar ul li a{
    display: block;
   text-decoration: none;
    color: white;
    border-radius: 20px;
    padding: 13px 79px;    
    
}
#navbar::before
{
    content: "    ";
    position: absolute;
    opacity: 35%;
    z-index: -1;
    height: 16%;
    width: 100%;
}
#navbar ul li a:hover
{
    color: rgba(167, 122, 71, 0.514);
    background-color: rgba(5, 2, 2, 0.479);
}
</style>        
</head>
<body>
    <!-- <img src="img/1.PNG" alt="" > -->
    <nav id="navbar">
        <ul>
            <li class="item" > <a href="#home"> Home</a></li>
            <li class="item" > <a href="#servces"> Services</a></li>
            <li class="item"> <a href="#clients"> Clients</a></li>
            <li class="item"> <a href="#blogs"> Blogs</a></li>
            <li class="item"> <a href="#news"> News</a></li>
            <li class="item"> <a href="#about"> About us</a></li>
        </ul>
    </nav>
   <section id="id">
       <img src="1.png" alt="" width="100% ">
       <h1 class="heading"></h1>
   </section>
    <img src="https://poojachugh24.github.io/helloworld/img/1.jpg" alt="alternatetext">
</body>
</html>
