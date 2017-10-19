<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
    $("p").on({
        mouseenter: function(){
            $(this).css("background-color", "lightgray");
        },  
        mouseleave: function(){
            $(this).css("background-color", "lightblue");
        }, 
        click: function(){
            $(this).css("background-color", "yellow");
        },
    });
});
$(document).ready(function(){
    $("input").focus(function(){
        $(this).css("background-color", "#cccccc");
    });
    $("input").blur(function(){
        $(this).css("background-color", "#ffffff");
    });
});
$
</script>
</head>
<style>
   body {
      background-color: gray;
   }
   h1{
      background-color:yellow;
      font-family:"MV Boli";	  
   } 
   h2{
      background-color:red;
	  font-family:"MV Boli"
   }
   div{
      hight:220;
	  width:220;
   }
   
   
</style>

<body>
<h1>THAMMASAT UNIVERSITY</h1>
<h2>PATTAYA CAMPUS</h2>
  <marquee bgcolor="#00CC99" >
     <img  src="http://tips.ninenic.com/download/tips_ninenic_com/slide1/show1_1.jpg" />
     <img src="http://tips.ninenic.com/download/tips_ninenic_com/slide1/show1_2.jpg" />
     <img src="http://tips.ninenic.com/download/tips_ninenic_com/slide1/show1_3.jpg" /> 
     <img  src="http://tips.ninenic.com/download/tips_ninenic_com/slide1/show1_4.jpg" />
     <img  src="http://tips.ninenic.com/download/tips_ninenic_com/slide1/show1_1.jpg" />
     <img src="http://tips.ninenic.com/download/tips_ninenic_com/slide1/show1_2.jpg" />
     <img src="http://tips.ninenic.com/download/tips_ninenic_com/slide1/show1_3.jpg" /> 
     <img  src="http://tips.ninenic.com/download/tips_ninenic_com/slide1/show1_4.jpg" />
  </marquee>

    Search:<input type="text" name="search">
<center>
	<p>FOOD RECOMMEND</p>
</center>
<label="food">ประเภทร้านอาหาร :</label>

<select>
  <option>ประเภทร้านอาหาร</option>
  <option>อาหารจานด่วน(อาหารตามสั่ง)</option>
  <option>ร้านขนมหวาน/ขนมปัง</option>
  <option>ร้านเครื่องดื่ม/แอลกอฮอล์/กาแฟ</option>
  <option>Buffet</option>
  <option>อื่นๆ</option>
</select>
<div="test_image">
    <img src="D:\SF100_Wabcode\test_image.jpg"width="100px"height="100px">
</div>
</body>
</html>
