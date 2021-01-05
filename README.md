<!DOCTYPE html>
<html>
<head>
  <title>Membuat profolio</title>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="web.css">
  <style>
  
  body{
    width: 400px;
    background-size: cover;
    background-image: linear-gradient( to left,#c9edfd,#75eafb,#c9edfd);
    margin: 0;
    padding: 0;
    
   }

   .container {
        position: fixed;
        top: 0;
        bottom: 0;
       left: 0;
       right: 0;
       height: 150px;
        box-shadow: 0 2px 10px 0;
        margin-top: 20px;
        font-size: 35px;
        border-radius: 0 0 0 0;
        background-image: Radial-gradient(circle at top,rgb(127,246,255,0.5),rgb(255,255,255),rgb(127,246,254,0.5));
        background-repeat: no-repeat;
        
        
  }
    .logo img{
      
      position: absolute;
      left: 0;
      top: 1;
      right: 0;
      bottom: ;
      float: left;
      margin-bottom: 50px;
      margin-top: 20px;
      width: 150px;
      
  }
  
     
   



.web{
  
  text-shadow: 2px 2px 5px rgb(0,0,0),-2px -2px 4px rgb(19,165,200);
  
}
.web h1{
  margin-top: 80px;
  margin-right: 10px;
  margin-left: 30px;
  margin-bottom: 50px;
  font-size: 40px;
  position: relative;
  float: right;
  
  
}


.pelayanan{
  float: right;
  
  
}
.pelayanan img{
  display: inline-block;
  position: relative;
  margin-bottom: 0px;
  float: left;
  width: 50px;
  height: 45px;
  margin-top: 10px;
  
}
.pelayanan #pelayanan1{
  margin-top: 30px;
  
}
.pelayanan h4{
 float: right;
 font-size: 10px;
 margin-top: 30px;
 
}
  
  
  
}
.cek{
  float: left;
}

.cek img{
  width: 50px;
  height: 45px;
  float: left;
  margin-top: 10px;
  margin-left: 10px;
}

.cek #cek1{
  margin-top: 30px;
  float: left;
  
}
.cek h4{
  float: left;
  font-size: 10px;
  margin-top: 30px;
}


.kesehatan{
  float: right;
 
}

.kesehatan img{
  float: left;
  width: 50px;
  height: 45px;
  margin-top: 60px;
  margin-left: 20px;
  
 
  
}
  .kesehatan #kesehatan1{
        float: left;
        margin-top: 80px;
        margin-right: 0px;
       
}
.kesehatan h4{
  float: right;
  margin-top: 80px;
  margin-right: 35px;
  font-size: 10px;
  
}
.pengobatan{
  float: left;
}
.pengobatan img{
  float: left;
  width: 50px;
  height: 45px;
  margin-top: 60px;
  margin-left: 10px;
  
}
.pengobatan #pengobatan1{
    margin-top: 80px;
}
.pengobatan h4{
  float: right;
  margin-top: 80px;
  margin-left: 0px;
  font-size: 10px;
}


 







.footer{
  height: 20px;
  background-image: linear-gradient( to right,#e5e5e5,#4ce1fb,#9be9ff,#e5e5e5);
  position: fixed;
  top: 1;
  bottom: 0;
  left: 0;
  right: 0;
  text-align: center;
  box-shadow: 0 2px 10px 0;
}

    
  </style>
</head>
<body>
    <div class="container"></div>
      <div class="logo">
        <img src="bumi.png">
      </div>
      <div class="web"><h1>Woles Hospital</h1>
    </div>
      
    <div class="pelayanan" ><img src="pelayanan.png" >
         <input type="radio" id="pelayanan1" name="pilih">
         <h4>consultation</h4>
    </div>
    <div class="cek">
        <img src="cek.png">
        <input type="radio" id="cek1" name="pilih">
        <h4>medical check-up</h4>
     </div>
     <div class="kesehatan">
         <img src="kesehatan.png">
           <input type="radio" id="kesehatan1" name="pilih">
         <h4>health</h4>
     </div>
     <div class="pengobatan">
       <img src="pengobatan.png">
        <input type="radio" id="pengobatan1"
        name="pilih"><h4>treatment</h4>
     </div>
      
  
    
    
    
    <div class="footer">I hope you feel at home</div>
  
</body>
</html>
