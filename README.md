# Website-html-and-css
## Aim:
To create a website using HTML and CSS.
## Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sweet Tooth</title>
</head>
<style>
    .fnt{
        margin-top: 2px;
    }
    .c1{
        
            top: 0cm;
            position:relative;
            height: 500px;
            width: 80%;
            margin-left: 0px;
            margin-right: 0%;
            opacity: 60%;
             
        }
    .but{
        padding-top: 8px;
        margin-top: -200px;
    }
    .b2{
        position: absolute;
        height: 8px;
        margin-top:6cm;
        justify-content: space-between;
}       
.cont{
  position: absolute;
  width: 150px;
  height: 280px;
  display: flex;
  top: 12cm;
  justify-content: space-between;
  
}
    
    .cakee{
        position:absolute;
        display: flex;
        justify-content: space-around;
        justify-content: center;
        top:8cm;
        
    }
    .top-left {
     position:absolute;
    top: 3cm;
    left: 2cm;
    color: rgb(240, 250, 149);
    font-size: 60px;
    font-family: 'Papyrus';
}
.top-left2 {
     position:absolute; 
   float : right;
   right: 9cm;
    color: rgb(240, 250, 149);
   
    font-family: 'Papyrus';
}
.c2{
    opacity: 60%;
    background-size: cover;
    position: absolute;
    width: 30cm;
    height:20cm;
}
.op1{
    
        position:absolute;
       display: flex;
        justify-content: space-between;
        top : 11cm;
        height: 150px; 
        padding-right: 20px;    
    }
.des{
    position: absolute;
       display: flex;
        justify-content: space-evenly;
        margin-left: 10.5cm;
        top : 17cm;
        height: 195px;  
        font-family: cursive;
    }
.description{
    top: 10cm;
    position: absolute;
    margin-left: 10px;
    color: rgb(209, 15, 15);
    font-size: 25px;
    text-shadow: 0 0 3px #861a1a, 0 0 5px #1e1e72;
    font-family:'Cursive';
}

.about{
            
  position:relative;
  height: 400px;
           width: 100%;
            top:300px;
            padding-right: 10cm ;
            margin-left:0%;
            padding-right: 20cm;
            background-color: rgb(22, 21, 21);
}
.aboutdes{
    position:relative; 
    float: left;
    margin-left: 5cm;
    font-size: 35px;
    color: rgb(211, 190, 74);
    font-family: 'Papyrus';
}
.aboutdes2{
    position:absolute; 
    margin-left: 4cm;
    font-size: 25px;
    top: 2cm;
    color: rgb(211, 190, 74);
    font-family: 'Papyrus';
}
.aboutdes3{
    position:relative; 
    font-size: 25px;
    top: 2cm;
    color: rgb(211, 190, 74);
    font-family: 'Papyrus';
    
}
.crown{
    height: 4cm;
    margin-left: 13cm;
    margin-top: 0%;
    font-size: 25px;
    color: rgb(211, 190, 74);
    font-family: 'Papyrus';
}
</style>
<body style="position: absolute; background-color: black; margin-left: 0%;">
    
    <div>
        <img class="c1" src="./pcake2.png" >

        <p class="top-left"><i>Bon Appetit!</i></p>
        <img  class="top-left2" src="./st-removebg-preview.png">
         <p class="description">Common pancake characteristics include a crisp exterior and soft, airy interior. <br/>They are made from thinner batter than actual cakes, and a little hot grease sets the outer surface<br/> quickly; this allows the inside to remain fluffy and light.</p>

        <div class="b2">
            <button style="background-color:rgb(0, 0, 0); border-radius: 5px;  height: 1.5cm; width: 3.5cm;"><i>Cakes</i></button>
            <button style="background-color:rgb(0, 0, 0); margin-left: 6.5cm; border-radius: 5px; height: 1.5cm; width: 3.5cm; "><i>Piece</i></iButterScoth></button>
            <button style="background-color: rgb(0, 0, 0); margin-left:7cm; border-radius: 5px; height: 1.5cm; width: 3.5cm;"><i>Ice<br/>cakes</i></button>
            <button style="background-color: rgb(0, 0, 0); margin-left:7cm; border-radius: 5px; height: 1.5cm; width: 3.5cm;"><i>Make<br/>a wish</i></button>

        </div>


        <div class="cont">
        <img src="./c3-removebg-preview.png" style="border-radius: 30px; height: 5cm; margin-top: 50%;">
        <img src="./download-removebg-preview.png"  style=" border-radius: 30px; margin-left: 5cm;">
        <img src="./cakee22-removebg-preview.png" style=" border-radius: 30px;margin-left: 5cm; height: 4.8cm;margin-top: 2cm;">
        <img src="./sweet2-removebg-preview.png" style=" border-radius: 30px; margin-left: 5.8cm; margin-top: 50%;">
        
    </div>

     <div class="about">

        <h5 class="aboutdes" style="margin-top:95px;"><u>Sweet Tooth</u><br/></h5>
        <br/>
        <hr/>
        <div class="aboutdes2" style="margin-top:65px;">
            <br/>Eighth Avenue 487, New York<br/>+548125635<br/>pastery@sweethtooth.com</h5>
        </div>
         
        <img class="crown" src="./crown-removebg-preview.png">
        <div class="crown">
           <p style="margin-top: 0%; margin-left: 8.5cm;">" We deliver the purest form of pastry<br/> get from the prosperous resources<br/> all over the world "</p>
       
       
    </div> 
    </div> 
</body>
</html>
```
## Output:
![image](https://github.com/Archana2003-Jkumar/Website-html-and-css/assets/93427594/c2da237f-61b1-4bfb-ba0c-2e7273abe794)
## Result:
Hence the code has been successfully executed.
