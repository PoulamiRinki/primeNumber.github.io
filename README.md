<!DOCTYPE html>
<html lang="en"> 
    <head> 
        <meta charset="UTF-8" />
         <meta http-equiv="X-UA-Compatible" content="IE=edge" /> 
         <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <html> 
    <head> 
    <title> Check a number is Prime or not using JavaScript </title> 
    <script type="text/javascript"> 
    function p() { 
     var n, i, flag = true; 
    n =  document.myform.n.value; 
    n = parseInt(n) 
    for(i = 2; i <= n - 1; i++) 
    if (n % i == 0) { 
    flag = false; 
    break; 
    } 
    if (flag == true) 
    alert(n + " is prime"); 
    else
    alert(n + " is not prime"); 
    
    } 
    
        </script> 
    
    </head> 
    
     <body> 
    
        <center> 
    
            <h1>PRIME NUMBER OR NOT </h1> 
    
              
    
            <h4>check number is prime or not</h4> 
    <hr color="Green"> 
    <form name="myform"> 
    Enter the number: <input type="text" name=n value=""> 
    <br><br> 
     <input type="button" value="Check" onClick="p()"> 
    
    <br> 
    </form> 
    
