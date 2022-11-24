# Animation1
My first project in the Git Hub
<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	
 <title>Animatsiya</title>
 <style type="text/css" media="all">
   * {
     margin: 0;
     padding: 0;
     box-sizing: border-box;
   }
   body {
     display: flex;
     align-items: center;
     justify-content: center;
     min-height: 100vh ;
     background: #000;
   }
   .container {
     position: relative;
     width: 300px;
     height: 300px;
   }
   .container span {
     position: absolute;
     border: 5px solid red;
   }
   .container span:nth-child(1){
     
     top: 0;
     right: 0;
     bottom: 0;
     left: 0;
     animation: animate1 2s linear infinite;
     animation-delay: 0s;
   }
  .container span:nth-child(2){
     
     border-radius: 50%;
     top: 0;
     right: 0;
     bottom: 0;
     animation: animate3 2s linear infinite;
     left: 0;
   }
  .container span:nth-child(3){
    
     top: 45px;
     right: 45px;
     bottom: 45px;
     left: 45px;
     animation: animate2 2s linear infinite;
     animation-delay: 2s;
   }
  .container span:nth-child(4){
     border-radius: 50%;
     
     top: 45px;
     right: 45px;
     bottom: 45px;
animation: animate3 2s linear infinite;
     left: 45px;
   }
  .container span:nth-child(5){
     
     top: 75px;
     right: 75px;
     bottom: 75px;
     left: 75px;
animation: animate1 2s linear infinite;
animation-delay: 3s;
   }
  .container span:nth-child(6){
     border-radius: 50%;
     
     top: 75px;
     right: 75px;
     bottom: 75px;
animation: animate3 2s linear infinite;
     left: 75px;
   }
  .container span:nth-child(7){
     
     top: 100px;
     right: 100px;
     bottom: 100px;
     left: 100px;
animation: animate2 2s linear infinite;
animation-delay: 4s;
   }
  .container span:nth-child(8){
     border-radius: 50%;
    
     top: 100px;
     right: 100px;
     bottom: 100px;
animation: animate3 2s linear infinite;
     left: 100px;
   }
  .container span:nth-child(9){
    
     top: 117.5px;
     right: 117.5px;
     bottom: 117.5px;
     left: 117.5px;
animation: animate1 2s linear infinite;
animation-delay: 5s;
   }
  .container span:nth-child(10){
     border-radius: 50%;
    
     top: 117.5px;
     right: 117.5px;
     bottom: 117.5px;
     left: 117.5px;
animation: animate3 2s linear infinite;
   }
  .container span:nth-child(11){
     
     top: 130px;
     right: 130px;
     bottom: 130px;
     left: 130px;
animation: animate2 2s linear infinite;
animation-delay: 6s;
   }
  .container span:nth-child(12){
     border-radius: 50%;
     
     top: 130px;
     right: 130px;
     bottom: 130px;
animation: animate3 2s linear infinite;
     left: 130px;
   }
   @keyframes animate1 {
     0% {
       filter: hue-rotate(0deg);
       transform: rotate(0deg);
     }
     100% {
       filter: hue-rotate(360deg);
       transform: rotate(360deg);
     }
   }
   @keyframes animate2 {
     0% {
       filter: hue-rotate(0deg);
       transform: rotate(0deg);
     }
     100% {
       filter: hue-rotate(-360deg);
       transform: rotate(-360deg);
     }
   }
   @keyframes animate3 {
     0% {
       filter: hue-rotate(0deg);
       
     }
     100% {
       filter: hue-rotate(360deg);
    
     }
   }
 </style>
 </head>
 <body>
   <div class="container">
     <span></span>
     <span></span>
     <span></span>
     <span></span>
     <span></span>
     <span></span>
     <span></span>
     <span></span>
     <span></span>
     <span></span>
     <span></span>
     <span></span>
   </div>
 </body>
 </html>
