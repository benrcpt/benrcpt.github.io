<!DOCTYPE html>
<html>
<head>
  <title>Membuat profolio</title>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="web.css">
  <style>
  
  body{
    height: 400px;
    background-size: cover;
    background-image: linear-gradient( to left,#c9edfd,#75eafb,#c9edfd);
    margin: 0;
    padding: 0;
    
   }

   .container {
        
          width: 500px;
          height: 150px;
          box-shadow: 0 2px 10px 0;
          margin-top: 20px;
          border-radius: 0 0 0 0;
          background-image: Radial-gradient(circle at top,rgb(127,246,255,0.5),rgb(255,255,255),rgb(127,246,254,0.5));
           background-repeat: no-repeat;
           background-size: cover;
           border: 2px  solid  black ;
           position: relative;
        
        
  }
  .container img{
     width: 100px;
    animation: bumianimation 10s ease infinite alternate;
    opacity: .9 ;
    background-color: rgb(255,255,255,0.10)   ;
  }
  @keyframes bumianimation {
    0% { 
      width: 140px;
  }
    50%{
    width: 160px;
    background-size: cover;
    transform: rotate(690deg);
  }
    100%{
      width: 160px;
    }
  
  }
  
  
  
   .container h1{
     position: absolute; 
     top: 0;
     bottom: 1;
     left: 0;
     right: 0;
     font-size: 50px;
     margin-top: 60px;
     text-align: center;
     text-shadow: 0 3px 10px black;
     
   }

     
         



.web{
    
     text-shadow: 2px 2px 5px rgb(0,0,0),-2px -2px 4px rgb(19,165,200);
  
}
.web h1{
  margin-top: 60px;
  margin-right: 30px;
  margin-left: 0px;
  font-size: 40px;
  position: absolute;
  top: 0;
  left: 1;
  right: 0;
  bottom: 0;
  text-align: center;
  
 
  
  
}
h1{
  animation: webanimation 10s ease  1 alternate ;
}
@keyframes webanimation{
  0%{
    right: 20px;
    
  }
  50%{
    right: 40px;
  }
  100%{
    right; 60px;
  }
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
img{
 
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

 .tulisan {
  float: left;
  margin-top: 50px;
  margin-left: 10px;
  width: 200px;
  height: 150px;
}
.tulisan p{
  float: left;
}

#bacaan{
  float: right;
  margin-left: 40px;
  width: 160px;
  height: 120px;
  margin-top: 50px;
  margin-left: 30px;
  
}
#bacaan p{
  float: right;
  margin-left: 0px;
  line-height: 20px;
  font-size: 10px;
  text-align: center;
  
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
    <div class="container">
       <img src="bumi.png" id="bumi"><h1>Woles Hospital</h1>
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
      
     <div class="tulisan">
         <p>
          RDI (dahulu merupakan singkatan dari Radio Dangdut Indonesia) adalah sebuah stasiun radio yang di bawah naungan MNC Radio Networks milik MNC dan kakak perusahaan PT. Serum Nagari Buana. Dahulu dikenal dengan sebutan Radio Monalisa, kemudian Radio Dangdut TPI. Sejak 20 Oktober 2010, bersamaan dengan pergantian nama udara TPI menjadi MNCTV, Radio Dangdut TPI berganti nama udara menjadi Radio Dangdut Indonesia dan sejak 20 Mei 2015    sekarang nama udaranya RDI.
     </p>
     </div>
     <div id="bacaan">
       <p>
       copyright tahun 2021
       Rcpt.bene
       </p>
       <img src="daftar.png">
    </div>
    
    <div class="footer">I hope you feel at home</div>
  
</body>
</html>
