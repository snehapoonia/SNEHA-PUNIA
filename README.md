# SNEHA-PUNIA
<- HTML ->
<!DOCTYPE html>
<html lang="en">
<head>
    <title>PAINTBOX</title>
    <link rel="stylesheet" href="style.css">
    </head>
<body>
    <div class="header">
        <div id="nav">
        <h1 id="h1"> Paint<span>Box</span></h1>
        <ul> 
           <li><a href="#">Home </a> </li>   
           <li><a href="#">Services </a> </li>    
           <li><a href="#">Contact </a> </li>    
           <li><a href="#">About Us </a> </li>  
         </ul>
         <a href="#" class="btn"> Sign Up</a>
        </div>
            <div class="content">
            <h4> Hello, my name is</h4>
            <h1>Sneha <span>Punia</span></h1>
            <br>
            <h4>Please enter your mail for registration</h4>
            <br>
            <div class="newsletter">
            <form>
                <input type="email" name="email" id="mail" placeholder="Enter your email">
                <input type="submit" name="submit" value="Sign">
            </form>
        </div>
    </div>  
    <div id="icons"> 
        <a href="#"><img src="./images/insta.png" alt="not found" height="60px" width="60px" id="img1"\> </a>
        <a href="#"><img src="./images/fb.jpg" alt="not found" height="60px" width="60px" id="img2" \> </a>
        <a href="#"><img src="./images/tweet.png" alt="not found" height="60px" width="60px" id="img3" \></a>
        <a href="#"><img src="./images/youtube.jfif" alt="not found" height="60px" width="65px" id="img4"\></a>
       </div>
       <img src="./images/back.png" height="100px" width="100px" alt="not found" id="art"/>
     
    </body>
</html>
  
  
  <- CSS ->
    *{
    padding: 0;
    margin: 0; 
    box-sizing: border-box;
 }
body{
    background-image: url(./images/abc.jpg);
  }
#h1{
   color: white;
   font-size: 55px;
   cursor: pointer;
   /* letter-spacing: 3px; */
}
span{
    color: orange;
    letter-spacing:3px;
}
#nav{ 
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 45px;
    padding-left: 8%;
    padding-right: 8%;
}
ul li {
    font-size: 30px;
    display: inline-block;
    padding: 10px 30px;
  }
ul li a{
    text-decoration: none;
    color: white;
    font-weight:bold;
  }
ul li a:hover{
    color: red;
}
.btn{
    background-color: orange;
    color:white;
    text-decoration: none;
    border:2px solid transparent;
    border-radius: 30px;
    font-weight: bold;
    padding: 10px 25px;
    transition: transform .6s;
}
.btn:hover{
    transform: scale(1.1);
    background-color: rgb(255, 7, 7);
}
.content{
    position:absolute;
    top:300px;
    left: 200px;
}
h1{
    color: white;
    margin: 20px 0 20px;
    font-size: 70px;
}
h3{
    color: white;
    font-size: 25px;
    margin-bottom: 50px;
  }
h4{
    color: white;
    font-size: 20px;
    letter-spacing: 2px;
}
.newsletter form{
    width: 400px;
    max-width: 100%;
    position: relative;
}
.newsletter form input:first-child {
  width: 100%;
  display: inline-block;
  padding: 14px 130px 14px 15px;
  border: 2px solid orange;
  border-radius: 30px;
}
.newsletter form input:last-child {
    position: absolute;
    display: inline-block;
    border: none;
    border-radius: 30px;
    padding: 10px 30px;
    background-color: orange;
    color: white;
    top: 6px;
    right: 6px;
    transition: transform .6s;
}
.newsletter form input:last-child:hover{
    transform : scale(1.1);
}
#icons{
    position: absolute;
    top: 600px;
    left:200px;
}
#img1{
     transition: transform .4s;
}
#img1:hover{
    transform:scale(1.1);
}
#img2{
    border-radius: 30%;    
    transition: transform .4s;
}
#img2:hover{
    transform:scale(1.1);
}
#img3{
    border-radius: 30%; 
    transition: transform .4s;   
}
#img3:hover{
    transform:scale(1.1);
}
#img4{
    border-radius: 30%;    
    transition: transform .4s;
}
#img4:hover{
    transform:scale(1.1);
}
#art{
    position: absolute;
    top:50px;
    left:20px;
    cursor: pointer;
}


