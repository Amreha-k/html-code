# html-code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Novel reading</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="./screenshot.PNG" alt="logo" width="150px">
        </div> 
        <nav>
            <ul>
            <li> <a href="#">home</a></li>
            <li> <a href="#">Genre</a></li>
            <li> <a href="#">New release</a></li>
            <li> <a href="#">Contact us</a></li>
            <li> <a href="#"class="signup-btn">signup</a></li>
        </nav>
    </header>
    <main>
        <div class="content-left"></div>
        <h1>Novel</h1>
        <h1>reading</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo sed rem ipsum quibusdam delectus sit nesciunt autem temporibus nam alias ullam, sequi neque, culpa ipsam id esse qui. Quo, corporis.</p>
        <button class="cta">learn more</button>
        <div class="content-right"></div>
        <img src="./download.jpeg" alt="" class="hero-image">
    </main>
    
</body>
</html>

style
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    font-family: 'Times New Roman', Times, serif;
}
header{
    height: 100px;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
ul{
    display: flex;
    list-style-type: none;
}
ul li a{
    padding: 0 20px;
    text-decoration: none;
    color: #3a3a3a;
    display: inline-block;
}
li ::after{
    content: '';
    display: block;
    height: 4px;
    width: 0;
    background: #c4c4f7;
    transition: all .5s;
}

li a:hover::after{
    width: 100%;
}

main{
    display: flex;
    border: 1px solid red;
    height: calc(100px -100px);
    align-items: center;
    justify-content: center;
}
.hero-image{
    max-width: 670px;
    height: auto;
}

.content-left{
    width: 30%;
}
main h1{
    font-size: 54px;
    color: #133b4f;
    text-transform: uppercase;

}
main h2{
    font-size: 25px;
    color: #fca70c;
    font-weight: 400;
    text-transform: uppercase;
    letter-spacing: 8px;
}
main p{
    font-size: 14px;
    font-weight: 400;
    color: #333;
    line-height: 31.5px;
    margin: 30px 0px;
}
.cta{
    padding: 15px 30px;
    
}
