<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>webpage Design</title>
    <link rel=" stylesheet" href="style.css">
</head>
<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">AIR ONE</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">BOOK & MANAGE</a></li>
                    <li><a href="#">SEARCH FLIGHTS</a></li>
                    <li><a href="#">CHECK IN</a></li>
                    <li><a href="#">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Enter Flight Details">
                <a href="#"> <button class="btn">Search</button></a>
            </div>

        </div>
        <div class="content">
            <h1>AIR ONE <br><span> Fly at Ease</span> <br> Travel With Pride</h1>
            <p class="par">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, enim soluta. Provident quibusdam <br> accusamus delectus, iusto similique, est doloremque tempora <br> mollitia eos commodi tempore maxime culpa aliquid velit sit obcaecati.</p>
        <button class="cn"><a href="#">Join us</a></button>

        <div class="form">
            <h2> Login Here</h2>
            <input type="email" name="email" placeholder="#deepakkumaravel17@gmail.com">
            <input type="password" name="" placeholder="Enter Password Here">
            <button class="btnn"><a href="#">Login</a></button>

            <p class="link">Don't have an account<br>
            <a href="#">Sign up </a> here</a>
            <p class="liw">Login with</p>

            <div class="icon">
                <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
                <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
                <a href="#"><ion-icon name="logo-google"></ion-icon></a>
                <a href="#"><ion-icon name="logo-skype"></ion-icon></a>
            </div>
            </div>
        </div>
        </div>
    </div>
    <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script> 
</body>


*{
    margin: 0;
    padding: 0;

}

.main{
    width: 100%;
    background: linear-gradient(to top, rgba(0,0,0,0.5)50%, rgba(0,0,0,0.5)50%), url(1.jpg);
    background-position: center;
    background-size: cover;
    height:100vh;
}

.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}

.icon{
    width: 200px;
    float: left;
    height: 70px;
}

.logo{
    color:orangered;
    font-size: 35px;
    font-family: Arial;
    padding-left: 20px;
    float: left;
    padding-top: 10px;

}

.menu{
    width: 400px;
    float: left;
    height: 70px;
}

ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}

ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
}

ul li a{
    text-decoration: none;
    color:black;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}

ul li a:hover{
    color:orangered;
}

.search{
    width: 330px;
    float: left;
    margin-left: 270px;

}

.srch{
    font-family: "Times New Roman";
    Width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #ff7200;
    margin-top: 13px;
    color:white;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px; 
}

.btn{
    width: 100px;
    height: 40px;
    background: orangered;
    border: 2px solid orangered;
    margin-top: 13px;
    color: white;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;

}

.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

.content{
    width: 1200px;
    height: auto;
    margin: auto;
    color:black;
    position: relative;
}

.content .par{
    padding-left: 20px;
    padding-bottom: 25px;
    font-family: Arial;
    letter-spacing: 1.2px;
    line-height: 30px;
}

.content h1{
    font-family: "Times New Roman";
    font-family: 50px;
    padding-left: 20px;
    margin-top: 9%;
    letter-spacing: 2px;

}

.content .cn{
    width: 100px;
    height: 30px;
    background: black;
    border: none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    transition: 3. ease;
}

.content .cn{
    text-decoration: none;
    color: black;
    transition: .3s ease;

}

.cn:hover{
    background-color: orangered;
}

.content span{
    color: white;
    font-size: 60px;

}

.form{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top, rgba(0,0,0,0.5)50%, rgba(0,0,0,0.5)50%);
    position: absolute;
    top: -20px;
    left: 870px;
    border-radius: 10px;
    padding: 25px;
}

.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: orangered;
    font-size: 22px;
    background-color: white;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;
}

.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid orangered;
    border-top: none;
    border-right: none;
    border-left: none;
    color: black;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;
}

.form input:focus{
    outline: none;
    font-family: Arial;
}

::placeholder{
    color: white;
    font-family: Arial;
}

.btnn{
    width: 240px;
    height: 40;
    background: orangered;
    border: none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color: white;
    transition: 0.4s ease;
}

.btnn:hover{
    background: white;
    color: orangered;
}

.btnn a{
    text-decoration: none;
    color: black;
    font-weight: bold;
}

.form .link{
    font-family: Arial, Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;
}

.form .link a{
    text-decoration: none;
    color: orangered;
}

.liw {
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;

}

.icon a{
    text-decoration: none;
    color: white;
}

.icon ion-icon{
    color: white;
    font-size: 22px;
    padding-left: 14px;
    padding-top: 5px;
    transition: 0.3s ease;
}

.icon ion-icon:hover{
    color: orangered;
}