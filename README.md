# heroku.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet"  href="css/all.css" > 
    <style>
        body{
    margin: 0;
    padding: 0;
}
.navbar{
    width: 100%;
    height: 60px;
    background-color: #262626
}
.contanier{
    width: 80%;
    height: 100%;
    margin: 0 auto;
    margin-right: 0px;
}
ul{
    margin: 0;
    padding: 0;
    float: right;
}
ul li{
    float: left;
    list-style: none;
}
ul li a{
    text-decoration: none;
    padding: 0 14px;
    position: relative;
    line-height: 50px;
    color: #fff;
    font-size: 17px;
    font-family: Arial, Helvetica, sans-serif;
    display: block;
    text-transform: uppercase;
    height: 100px;
    z-index: 1;
}
ul li a:before{
    content: '';
    position: absolute;
    top:0;
    left: 0;
    width: 100%;
    height: 0%;
    background-color:red;
    z-index: -1;
    transition: .5s;
}
ul li a:hover:before{
    height: 60%;
}
img{
    position:absolute;
    width: 93px;
    margin-left:30px;
    margin: 20px;
    
}

/*2nd Div Banner*/

.banner{
    position: absolute;
    background-image: url(image/zoomcarbanner.jpg);
    width: 100%;
    height: 70%;
    border: 2px solid;
    background-repeat: no-repeat;
    background-size: cover;
}

.banner h1{
    text-align: center;
    color: #fff;
    line-height: 270px;
    font-size: 43px;
    font-family: Arial, Helvetica, sans-serif;
}
.banner h2{
  position: absolute;
  top: 38%;
  left: 40%;
    text-align: center;
    color: #fff;
  
    font-size: 20px;
    font-family: Arial, Helvetica, sans-serif;
}
.bdiv{
    border: 1px solid #fff;
    width: 36%;
    height: 13%;
    border-radius:5px ;
    background-color: #fff;
    margin: 0 auto;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 20px;
    padding: 20px;
    box-sizing: border-box;
   cursor: pointer;
   margin-top: -70px;
   position: sticky;
  top: 40px;
}
/* 3nd Div*/

.zoomadvant{
    border: 2px solid;
    width: 100%;
    height: 70%;
    position: absolute;
    top: 78%;
    background: rgb(241, 236, 236);
}
.zoomadvant .fa-gas-pump{
    position: absolute;
    top: 10px;
    left: 100px;
    font-size: 50px;
}
.zoomadvant .fa-file-invoice-dollar{
    position: absolute;
    top: 10px;
    left: 365px;
    font-size: 50px;
}
.zoomadvant .fa-cubes{
    position: absolute;
    left: 80%;
    top: 10px;
    font-size: 50px;
}
.zoomadvant .fa-compass{
    position: absolute;
    left: 13%;
    top: 58%;
    font-size: 50px;
}
.zoomadvant .fa-parachute-box{
    position: absolute;
    left: 46%;
    top: 57%;
    font-size: 50px;
}
.zoomadvant .fa-car-crash{
    position: absolute;
    left: 78%;
    top: 57%;
    font-size: 50px;
}
.zoomadvant span{
    padding-top: 80px;
    font-size: 13px;
    font-family: Arial, Helvetica, sans-serif;
}
.griddiv{
    
    width: 50%;
    height: 60%;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: repeat(2,1fr);
    grid-gap: 10px;
    position: relative;
    left: 24%;
    text-align: center;
    line-height: 20px;
}

.zoomadvant h1{
   
    text-align: center;
    font-family:Arial, Helvetica, sans-serif ;

}
.zoomadvant h3{
    text-align: center;
    font-family:Arial, Helvetica, sans-serif ;
}



.iteams1{
    background: #fff;
}
.iteams2{
    background: #fff;
}
.iteams3{
    background: #fff;
}
.iteams4{
    background: #fff;
}
.iteams5{
    background: #fff;
}
.iteams6{
    background: #fff;
}

/*4nth Div*/
.SUPERMILER{
    width: 100%;
    height: 40%;
    position: absolute;
    top: 148%;
    background-image: url(image/banner3.jpg);
    background-position:  center;
    background-size: cover;
    background-repeat: no-repeat;
}
.SUPERMILER img{
    position: absolute;
    left: 40%;
    top: -5%;
    width: 18%;
}
.SUPERMILER h1{
    position: absolute;
    left: 42%;
    top: 18%;
    font-size: 30px;
    color: #fff;
    font-family: Arial, Helvetica, sans-serif;
}
.SUPERMILER span{
     position: absolute;
    left: 39%;
    top:39%;
    font-size: 14px;
    color: #fff;
    font-family: Arial, Helvetica, sans-serif;
}
.SUPERMILER h3{
     position: absolute;
    left: 45%;
    top:45%;
    font-size: 14px;
    color: #fff;
    font-family: Arial, Helvetica, sans-serif;
}
/*mid*/ 
.mid{
    width: 200px;
    height: 150px;
    background: #fff;
    z-index: 1;
    position: absolute;
    top: 177%;
    left: 44%;
    box-shadow: -2px 2px 10px #fff;
    border-radius: 3px;
}
.mid img{
    width: 30%;
    position: relative;
    left: 45px;
}
.mid h3{
    font-size: 15px;
    font-family: Arial, Helvetica, sans-serif;
    position: relative;
    left: 34px;
    top: -30px;

}

/*5th Div*/
.Z-Points{
    background: rgb(241, 236, 236);
    width: 100%;
    height: 30%;
    position: absolute;
    top: 188%;
    clear: both;
}
.Z-Points p{
    position: absolute;
    top: 35%;
    left: 45%;
    font-family: Arial, Helvetica, sans-serif;
   text-align: center
}
.Z-Points a{
    position: absolute;
    top:75%;
    left: 44%;
    font-family: Arial, Helvetica, sans-serif;
   text-align: center;
   text-decoration: none;
   border: 1px solid black;
   width:200px;
   height: 40px;
   padding:10px;
   box-sizing: border-box;
   font-size: 15px;
   color: black;
   cursor: pointer;
}

/*6th div*/
.HATCHBACK{
    width: 100%;
    height: 80%;
  
    position: absolute;
    top: 218%;
    background-image: url(image/banner4.jpg);
}

.HATCHBACK h1{
    font-family: Arial, Helvetica, sans-serif;
    color: #fff;
    text-align: center;
}
.HATCHBACK h3{
    font-family: Arial, Helvetica, sans-serif;
    color: #fff;
    text-align: center;
}
.HATCHBACK h2{
    font-size: 30px;
    text-align: center;
    color: #fff;
}
.HATCHBACK span{
    font-size: 20px;
    text-align: center;
    color: #fff;
    position: relative;
    left: 20%;
}
/*7th Div */
.zoomcar{
    width: 100%;
    height: 70%;
    background: rgb(241, 236, 236);
    position: absolute;
    top: 298%;
    
}
.zoomcar h1{
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    font-size: 25px;

}
.zoomcar span{
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    font-size: 15px;
    position: relative;
    left: 34%; 
    padding-top: 130px;

    
}

.griddiv2{
    
    width: 80%;
    height: 40%;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
    grid-gap: 25px;
    position: absolute;
    left: 10%;
    top: 40%;
    
}
.griddiv2 .iteam{
    border-radius: 10px;
    box-shadow: 5px 5px 15px black;
}
.griddiv2 img{
    width: 45%;
    position: absolute;
    top: 10px;
    left: 35px;
}
.griddiv2 .lock{
    width: 20%;
    position: absolute;
    left: 30%;
}
.griddiv2 .retrun{
    width: 20%;
    position: absolute;
    left: 30%;
}
 /*8th div*/
 .banner2{
    width: 100%;
    height: 78%;
   
    position: absolute;
    top: 367%;
    background-image: url(image/banner2.jpg);
    background-repeat: no-repeat;
    background-size: contain;
   object-fit: cover;
   background-position: center center;
}

 /*9th div*/
.Points{
    background: rgb(241, 236, 236);
    width: 100%;
    height: 40%;
    position: absolute;
    top: 445%;
    clear: both;
}
.Points span{
    display: block;
    width: 17%;
    height: 80%;
   
    position: relative;
    margin:21px;
    box-sizing: border-box;
    font-size: 20px;
    font-family: Arial, Helvetica, sans-serif;
    color: black ;
    float: left;
    padding-top: 70px;
    text-align: center;
    
}
.Points .fa-biking{
    position: absolute;
    top: 10px;
    left: 80px;
    font-size: 90px;
}
.Points .fa-laugh-wink{
    position: absolute;
    top: 10px;
    left: 80px;
    font-size: 90px;
}
.Points .fa-laugh-wink{
    position: absolute;
    top: 10px;
    left: 80px;
    font-size: 90px;
}
.Points .fa-tachometer-alt {
    position: absolute;
    top: 10px;
    left: 80px;
    font-size: 90px;
}
.Points .fa-car {
    position: absolute;
    top: 10px;
    left: 80px;
    font-size: 90px;
}
.Points .fa-star-half-alt{
    position: absolute;
    top: 10px;
    left: 80px;
    font-size: 90px;
}
 /*10th div*/
.ban{
   
    width: 100%;
    height: 70%;
    position: absolute;
    top: 485%;
    clear: both;
    background-image: url(image/banner5.jpg);
}
.ban img{
    width: 10%;
    position: relative;
    left: 43%;
}
.ban h2{
    font-family: Arial, Helvetica, sans-serif;
    color: #fff;
    text-align: center;
}

/*11th div*/ 
.add{
    width: 100%;
    height: 17%;
    position: absolute;
    top: 555%;
    background-image: url(image/ban.png);
    background-position: center center;
    background-repeat: no-repeat;
    background-size: contain;
}


/*12th div*/ 
.mouseho{
    width: 100%;
    height: 20%;
    background:rgb(45, 45, 87);
    position: absolute;
    top: 572%;
}
.mouseho span{
    display: inline-block;
    width: 20%;
    height: 100%;
    
    margin-left: 60px;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 20px;
    text-align: center;
    line-height: 150px;
}
.mouseho span:hover {
    background: rgb(27, 27, 83);
}
    </style> 
</head>
<body>
    <div class="navbar">
        <img src="image/zommcar.svg">
        <div class="contanier">
            <ul>
                <li><a href="#">OFFERS</a></li>
                <li><a href="#">SUBSCRIPTION</a></li>
                <li><a href="#">Amigo</a></li>
                <li><a href="#">ZMS</a></li>
                <li><a href="#">MobileApp</a></li>
                <li><a href="#">Signup</a></li>
                <li><a href="#">Login</a></li>
            </ul>
        </div>
    </div>

    <!--2nd Div Banner-->
    <div class="banner">
        <h1>DRIVE IN A SANITISED ZOOMCAR</h1>
        <h2>Self Drive Car Rental in Bangalore</h2>
        <div class="bdiv">Start your wonderful journey
        </div>
    </div>

     <!--3nd Div -->
     <div class="zoomadvant">
         
        <h1>THE ZOOMCAR ADVANTAGE</h1>
        <h3>We simplified car rentals, so you can focus on what's important to you.</h3>
        <div class="griddiv">
            <span class="iteam iteams1"><i class="fas fa-gas-pump"></i> Don't worry about mileage! All fuel costs are included. If you refill fuel, we'll pay you back!</span>
            <span class="iteam iteams2"><i class="fas fa-file-invoice-dollar"></i>Our prices include taxes and insurance.What you see is what you really pay!</span>
            <span class="iteam iteams3"><i class="fas fa-cubes"></i>One size never fits all! Choose a balance of time and kilometers that works best for you.</span>
            <span class="iteam iteams4"><i class="far fa-compass"></i>Our cars have all-India permits.  Just remember to pay state tolls and entry taxes.</span>
            <span class="iteam iteams5"><i class="fas fa-parachute-box"></i>We have round-the-clock, pan India partners. Help is never far away from you.</span>
            <span class="iteam iteams6"><i class="fas fa-car-crash"></i>All your bookings include damage insurance! Drive safe, but don’t worry!</span>
        </div>
     </div>

       <!--4nth Div -->
     <div class="SUPERMILER">
        <img src="image/mid1.svg">
        <h1>SUPERMILER CLUB</h1>
        <span>Premium club which rewards you everytime you drive with us</span>
        <h3>SUPERMILER PRIVILEGES</h3>
     </div>

     <div class="mid">
        <img src="image/mid.svg">
        <h3>EARN Z POINTS</h3>
     </div>

         <!--5th Div -->
         <div class="Z-Points">
            <p>Earn Z-Points for every <br> booking and redeem for<br> additional discount</p>
            <a href="#">LEARN MORE</a>
        </div>

     <!--6th Div -->
     <div class="HATCHBACK">
        <h1>A CAR FOR EVERY NEED</h1>
        <h3>We have a range of cars, so something will perfectly fit your trip</h3>
        <h1 class="head">HATCHBACK</h1>
        <h2>Price Starting at ₹ 70/hr (Fuel Free)</h2>
        <span>CARS AVAILABLE: FORD FIGO, MARUTI SWIFT, BALENO, MAHINDRA KUV 100, MARUTI RITZ,<br> HYUNDAI I20 ELITE, JAZZ SMT 1.5 IDTEC, <br>THE RAPTOR, GRAND I10</span>
        <h1 class="last">A quick drive to sunrise point</h1>
    </div>

    <!--7th Div -->
    <div class="zoomcar">
        <h1>HOW ZOOMCAR WORKS</h1>
        <span>Drive yourself to an adventure and back in 5 simple steps</span>
        <div class="griddiv2">
            <span class="iteam iteams1"><img src="image/book.svg"> for and book a car on our site!</span>
            <span class="iteam iteams2"><img src="image/licens.svg"> Upload your driver’s license, and pay a small security deposit.</span>
            <span class="iteam iteams3"><img src="image/ulock.png" class="lock"> We SMS your car details 20 minutes before pickup. Unlock it via the Zoomcar app.</span>
            <span class="iteam iteams4"><img src="image/zoom.svg"> Fill the start checklist in the Zoomcar app. Grab the keys from the glove-box and drive.</span>
            <span class="iteam iteams5"><img src="image/retrun.svg" class="retrun"> Return the car to the same location and fill the end checklist to end your trip.</span>
           
        </div>
    </div>

    
    <!--8th Div -->
    <div class="banner2">
        
    </div>

<!--9th Div -->
    <div class="Points">
       <span><i class="fas fa-biking"></i><h1>3,000+</h1>Rides Daily</span>
       <span><h1><i class="far fa-laugh-wink"></i>48,00,000+</h1>Happy users</span>
       <span><h1><i class="fas fa-tachometer-alt"></i>36,00,00,000+</h1>Km Travelled(enough for 470 round trips to the moon!)</span>
       <span><h1><i class="fas fa-car"></i>6,500+</h1>Number of Zoomcars</span>
       <span><h1><i class="fas fa-star-half-alt"></i>Rating 4.7/5.0</h1>Rated by 3,00,000+ customers over 10,00,000+ bookings</span>
    </div>
   
    <!--10th Div -->
    <div class="ban">
        <img src="image/comma.png">
        <h2>You certainly do have a very regular customer here... Must say, Greg went that extra<br> mile... You have a great journey together!</h2>
    </div>

    <!--11th Div -->
    <div class="add">
       
    </div>

    <!--12th Div -->
    <div class="mouseho">
        <span>How zoomcar works?</span>
        <span>Policies</span>
        <span>Help Support</span>
        <span>Zoom in safety</span>
    </div>

</body>
</html>
