<!DOCTYPE html>
<html>
 <head>
  <title>Simple Calculator<?title>
</head>
<body bg color="black">
<form name="calculator">
<input type="textfield" name="ans" value="">
<br>
<h1>
<input type="button" value="1" onclick="document.calculator.ans.value+='1'">
         <input type="button" value="2" onclick="document.calculator.ans.value+='2'">
         <input type="button" value="3" onclick="document.calculator.ans.value+='3'">
         <input type="button" value="+" onclick="document.calculator.ans.value+='+'">
            <br>
         <input type="button" value="4" onclick="document.calculator.ans.value+='4'">
         <input type="button" value="5" onclick="document.calculator.ans.value+='5'">
         <input type="button" value="6" onclick="document.calculator.ans.value+='6'">
         <input type="button" value="-" onclick="document.calculator.ans.value+='-'">
            <br>
         <input type="button" value="7" onclick="document.calculator.ans.value+='7'">
         <input type="button" value="8" onclick="document.calculator.ans.value+='8'">
         <input type="button" value="9" onclick="document.calculator.ans.value+='9'">
         <input type="button" value="/" onclick="document.calculator.ans.value+='/'">
            <br>
         <input type="button" value="0" onclick="document.calculator.ans.value+='0'">
         <input type="button" value="C" onclick="document.calculator.ans.value=''">
         <input type="button" value="*" onclick="document.calculator.ans.value+='*'">
         <input type="button" value="=" onclick="document.calculator.ans.value=eval(document.calculator.ans.value)">
                                                 </h2>
                                                 </form>
                                                 </html>
