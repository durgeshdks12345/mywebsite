<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="vieport" content="width=device, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie-edge">
        <title>SAHANI FITNESS</title>
    </head>
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
/*  CSS RESET   */
body{
    /*background-image: url(paper.gif);
    background-repeat: repeat-y;*/
    font-family: 'Baloo Bhai', cursive;
    color: white;
margin: 0px;
padding: 0px;
background: url('img/dk.jpg');
background-repeat: no-repeat;
background-attachment: fixed;

height: 4635px;
}
.left{
    position: absolute;
    left: 60px;
    top: 20px;
    
    display: inline-block;
    /*border: 2px solid red;*/
}
.text{
    color: rgb(206, 201, 201);
}
.left img{
    width: 116px;
    filter: invert(100%);
}
.left div{
    text-align: center;
}
.mid{
    display: block;
    width: 40%;
    margin: 29px auto;
  /*  border: 2px solid green;*/

}
.right
{
    position: absolute;
    right: 34px;
    top: 43px;
    display: inline-block;
    /*border: 2px solid yellow;*/
}
.navbar{
    display: inline-block;
}
.navbar li{

    display: inline-block;
    font-size: 20px;
}
.navbar li a{
    color: white;
    text-decoration: none;
    padding:10px 5px;
}
.navbar li a:hover, .navbar li a.active{
    text-decoration: underline;
    color: grey;
}
.btn{
    font-family: 'Baloo Bhai', cursive;
    margin: opx 9px ;
    background-color: black;
    color: white;
    padding:4px 14px ;
    border: 2px solid grey;
    border-radius: 10px;
    font-size: 20px;
    cursor: pointer;

}
.btn:hover{
    background-color: rgb(63, 62, 62);
}
.container{
    border: 2px solid white;
    margin:106px 80px;
    padding: 75px;
    width: 75%;
    border-radius: 28px;
}
.form.group input{
    text-align: center;
    display: block;
    width: 508px;
    padding: 1px;
    border: 2px solid black;
    margin:11px auto;
    font-size: 25px;
    border-radius: 8px;
    font-family: 'Baloo Bhai', cursive;
}
.container h1{
    text-align: center;
}
.container button{
    display: block;
    width: 74%;
    margin: 24px auto;
}

.row{
    display: flex;
    flex-wrap: wrap;
}
.footer-col{
    padding: 54px;
    margin: 3px;
    line-height: 1.8;
}
.social-link{
    /* padding: 20px; */
    width: 20px;
    margin: 3px;
    align-items: center;
}
    </style>
    <body>
        <header class="header">
            <!--Left box for logo-->
            <div class="left">
                <img src="img/logo.jpg" alt="">
                <div>SAHANI FITNESS</div>
            </div>
            <!--Mid box for navbar-->
            <div class="mid">
                <ul class="navbar">
                    <li><a href="#" class="active">Home</a></li>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Fitness Calculater</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
            <!--Right box for buttons-->
            <div class="right">
<butto class="btn">Call Us Now</butto>
<butto class="btn">Email Us</butto>
            </div>
        </header>
        <div class="container">
            <h1>Join The Best GMY On Delhi Now</h1>
            <form action="noaction.php">
                
                <div class="form group">
                    <input type="text" name="" placeholder="Enter your Name">
                </div>
                <div class="form group">
                    <input type="text" name="" placeholder="Enter your Age">
                </div>
                <div class="form group">
                    <input type="text" name="" placeholder="Enter your Gender">
                </div>
                <div class="form group">
                    <input type="text" name="" placeholder="Enter your Locality">
                </div>
                <button class="btn">Submit</button>
                </div>
            </form>
            <footer class="footer">
                <div class="container">
                    <div class="row">
                        <div class="footer-col">
                            <h4>Company</h4>
                            <ul>
                               
                                <li><a href="#">About Us</a></li>
                                <li><a href="#">Our Services</a></li>
                                <li><a href="#">Privacy Policy</a></li>
                                <li><a href="#">Affiliate Programe</a></li>
                            </ul>
                        </div>
                        <div class="footer-col">
                            <h4>Get Help</h4>
                            <ul>
                                <li><a href="#">FAQ</a></li>
                                <li><a href="#">Shipping</a></li>
                                <li><a href="#">Returns</a></li>
                                <li><a href="#">Order Status</a></li>
                                <li><a href="#">Payment Option</a></li>
                            </ul>
                        </div>
                        <div class="footer-col">
                            <h4>Online Shope</h4>
                            <ul>
                                <li><a href="#">Watch</a></li>
                                <li><a href="#">Bag</a></li>
                                <li><a href="#">Shoes</a></li>
                                <li><a href="#">Dress</a></li>
                            </ul>
                        </div>
                        <div class="footer-col">
                            <h4>Follow US</h4>
                            <div class="social-link">
                                <a href="facebook.com"><i class="fab fa-facebook">Facebook</i></a>
                                <a href="#"><i class="fab fa-twitter">Twitte</i></a>
                                <a href="#"><i class="fab fa-instagram">Instagram</i></a>
                                <a href="#"><i class="fab fa-youtube">youtube</i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </footer>
            
        
    </body>
</html> 
