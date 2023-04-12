# My-PortfolioProject
Beginner first portfolio project

**********************************
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Personal Info</title>
   <link rel="stylesheet" href="personalinfo.css">
</head>
<body>
   <div class="hero">
      <nav>
         <img src="imgp/pro.jpg">
         <h2>Prajwal Pal</h2>
         <p>“ In order to be irreplaceable, one must always be different”</p>
         <ul>
          <button><a href="#">Instagram</a></button><br>
          <button><a href="#">Snapchat</a></button><br>
          <button><a href="#">College</a></button><br>
          <button><a href="#">Laptop Name</a></button><br>
          <button><a href="#">Work Location</a></button><br>
          <button><a href="#">Mobile No.</a></button><br>
         </ul>
      </nav>
   </div>
</body>
</html>



*{
   margin: 0;
   padding: 0;
   box-sizing: border-box;
}
.hero{
   width: 100%;
   min-height: 100vh;
   background: linear-gradient(to right,#094282,#6d00ff 70%,#6d00ff 70%);
   color: white;
   padding: 10px 8%;
   position: relative;
}
nav img{
   width: 200px;
   position: absolute;
   right: 43%;
   top: 10%;
   z-index: 2;
   border: 1px solid grey;
   border-radius: 50%;
}
nav h2{
   font-size: 35px;
   line-height: 90px;
   font-weight: 500;
   position: absolute;
   right: 44.5%;
   top: 35%;
   z-index: 2;
}
nav p{
   position: absolute;
   right: 37%;
   top: 45%;
   z-index: 2;
}
.hero button{
   width: 100%;
   padding: 10px 200px;
   background: white;
   border: 0;
   outline: 0;
   margin-top: 10px;
   margin-right: 0;
   border-radius: 30px;
   font-weight: 500;
   cursor: pointer;
}
.hero ul{
   position: absolute;
   right: 34%;
   top: 52%;
}
.hero ul{
   margin-top: 1%;
   max-width: 600px;
}

button:hover{
   background-color: aquamarine;
   transform: rotate(1deg);
}
