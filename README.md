<!DOCTYPE html> 
<html lang "en">
 <center>
<head
    <tittle>
       <h1>Calculator</h1>
     </tittle>

    

 </head></center>
 <Body bgcolor="#D32F2F"
 </Body>

 

<center>
    <p>Numbers down here</p>
</center>

<div private class="container">


<!--<input type="text" id="firstnumber" style =" width: 100PX; height: 250px;">
<input type="number" id="secondnumber" size="2">-->

<center><div class="caja" style =" width: 500px; height: 250px; background-color:#D32F2F;">
    <div private class="result">
    
        <div id=lye style="text-decoration-color: #692222;"></div>
    </div></center>
       
</div>


</div>

    <!--<div class="bignumba">
        <textarea id="bignumba2"  style =" width: 500px; height: 250px;"></textarea>-->

<center><p>What you want me to do?</p></center>
<!--

<div private class="grid">


<input type="button"  value="PLUS" onclick="PLUS()"></input>
<input type="button"  value="MINUS" onclick="MINUSTHIS()"></input>
<input type="button"  value="TIMES" onclick="TIMESTHIS()"></input>
<input type="button"  value="DIVIDE" onclick="Halfthis()"></input>


</div>-->
<div private class="numpad" >
    <input type="button" value="7" onclick="siete()" style="height:60px; width:60px; background-color: black;border-radius: 40px; color: white;">
    <input type="button" value="8" onclick="ocho()" style="height:60px; width:60px; background-color: black;border-radius: 40px; color: white;">
    <input type="button" value="9" onclick="nueve()" style="height:60px; width:60px; background-color: black;border-radius: 40px; color: white;"1>
    <input type="button" value="*" onclick="multiplicar()" style="height:60px; width:60px; background-color: mediumblue;border-radius: 40px; color: white;">



    
    
   




    <input type="button" value="4" onclick="cuatro()" style="height:60px; width:60px; background-color: black;border-radius: 40px; color: white;" >
    <input type="button" value="5" onclick="cinco()" style="height:60px; width:60px; background-color: black;border-radius: 40px; color: white;">
    <input type="button" value="6" onclick="seis()" style="height:60px; width:60px; background-color: black;border-radius: 40px; color: white;">
    <input type="button" value="-" onclick="resta()" style="height:60px; width:60px; background-color: mediumblue;border-radius: 40px; color: white;">
  


    
    
    
    <input type="button" value="1" onclick="uno()" style="height:60px; width:60px;background-color: black; border-radius: 40px; color: white;" >
    <input type="button" value="2" onclick="dos()" style="height:60px; width:60px;background-color: black; border-radius: 40px;color: white;" >
    <input type="button" value="3" onclick="tress()" style="height:60px; width:60px; background-color: black; border-radius: 40px;color: white;" >
    <input type="button" value="+" onclick="suma()" style="height:60px; width:60px; background-color: mediumblue;border-radius: 40px; color: white;">
    
    

    
<input type="button" value="0" onclick="cero()" style="height:60px; width:70px; background-color: black;border-radius: 40px;color: white;">
<input type="button" value="AC" onClick="Delete()" style="height:60px; width:60px; background-color: orange;border-radius: 40px; color: white;">

<input type="button" value="=" onclick="igual()" style="height:60px; width:60px; background-color: mediumblue; border-radius: 40px; color: white;" >
<input type="button" value="/" onclick="dividir()" style="height:60px; width:60px;background-color: mediumblue;border-radius: 40px; color: white;">

    
  
</div>

<!--<div id=numpad></div>-->

 


<script type="text/javascript">
 

 
/*  //SUMA
        function PLUS(){
    
        var firstnumber = document.getElementById('firstnumber').value;
        var secondnumber = document.getElementById('secondnumber').value;
        var result = (parseInt(firstnumber)+parseInt(secondnumber));
        document.getElementById('result').innerHTML=firstnumber + ' + ' + secondnumber + ' = ' + result
       
        }
      
        //RESTA
        function MINUSTHIS(){
            
            var firstnumber = document.getElementById('firstnumber').value
            var secondnumber = document.getElementById('secondnumber').value
            var result=(firstnumber-secondnumber);
            document.getElementById('result').innerHTML=firstnumber + '-' + secondnumber + '=' + result
            
        }
    
    
        //MULTIPLICACION
        function TIMESTHIS(){
            var firstnumber = document.getElementById('firstnumber').value
            var secondnumber = document.getElementById('secondnumber').value
            var result = (firstnumber*secondnumber)
            document.getElementById('result').innerHTML=firstnumber + '*' + secondnumber + '=' + result
        }
    
        //DIVIDIR
function Halfthis(){
    var firstnumber = document.getElementById('firstnumber').value
    var secondnumber = document.getElementById('secondnumber').value
    var result = (firstnumber/secondnumber)
    document.getElementById('result').innerHTML=firstnumber + ' / ' + secondnumber + ' = ' + result
}*/

operacion=''
suma1=''
suma2=''
significado=''
function Delete(){
    operacion=''
suma1=''
suma2=''
significado=''
document.getElementById('lye').innerHTML=  suma1 + operacion + suma2
}
function cero(){
    if (operacion== ''){ 
        suma1= suma1 + '0'
        document.getElementById('lye').innerHTML=  suma1  + " " + operacion  +" " + suma2
    } else {
        suma2= suma2 + '0'
        document.getElementById('lye').innerHTML= suma1  + " " + operacion  +" " + suma2
    }
}



" "

function uno(){
    if (operacion== ''){
    suma1= suma1 + '1'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

} else {
    suma2= suma2 + '1'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

}

}
function dos(){
    if (operacion== ''){
    suma1= suma1 + '2'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

} else {
    suma2= suma2 + '2'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

}
}
function tress(){
    if (operacion== ''){
    suma1= suma1 + '3'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

} else {
    suma2= suma2 + '3'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

}
}
function cuatro(){
    if (operacion== ''){
    suma1= suma1 + '4'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

} else {
    suma2= suma2 + '4'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

}}

function cinco(){
    if (operacion== ''){
    suma1= suma1 + '5'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

} else {
    suma2= suma2 + '5'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

}
}
function seis(){
    if (operacion== ''){
    suma1= suma1 + '6'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

} else {
    suma2= suma2 + '6'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

}
}
function siete(){

    if (operacion== ''){
    suma1= suma1 + '7'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

} else {
    suma2= suma2 + '7'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

}
}
function ocho(){
    if (operacion== ''){
    suma1= suma1 + '8'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

} else {
    suma2= suma2 + '8'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

}
}
function nueve(){
    if (operacion== ''){
    suma1= suma1 + '9'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

} else {
    suma2= suma2 + '9'
    document.getElementById('lye').innerHTML=suma1 + operacion + suma2

}
}
function suma(){

operacion= '+'
document.getElementById('lye').innerHTML=suma1 + operacion + suma2
}
function resta(){

operacion='-'
document.getElementById('lye').innerHTML=suma1 + operacion + suma2
}
function dividir(){

operacion='/'
document.getElementById('lye').innerHTML=suma1 + operacion + suma2
}
function multiplicar(){
operacion= '*'
document.getElementById('lye').innerHTML=suma1 + operacion + suma2


}
function igual() { 
    var result 
if(operacion == "*"){
   result = suma1 * suma2

}
if(operacion == "+"){
   result = (parseInt(suma1))+(parseInt(suma2))

}
if(operacion == "-"){
   result = suma1 - suma2

}
if(operacion == "/"){
   result = suma1 / suma2

}

document.getElementById('lye').innerHTML= suma1 + operacion + suma2 + " = " + result
}

    
 </script>


<style>
    .grid{
        display: grid;
       
        grid-template-columns: 10% 10% 10% 10%;
       
        gap: 5px;
        
        grid-template-rows:  25px 25px 25px 25px;
       
        display: container;
        
        display: result;
        
        
        
        
       
    }
    .numpad{
        display: grid;
            grid-template-columns:  65px 65px 65px 65px ;
            grid-template-rows: 65px  65px 65px 65px 65px;
           justify-content: center;
           column-gap: 6px;
           
    }
    

   
    
    .grid input:hover{

        border:5px solid #3700ff;
        
        
    }
   

    input{
        background: #00ffee
    }
    
    
    p{
        color: #ffffff
    }
    
    
    h1{
        color:white;

    .result div{
        color: white;
        
        font-size: 25px;
    
        
    
    }
    .container div{
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        color: black;
    }

</style>
