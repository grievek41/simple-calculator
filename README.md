# simple-calculator
<!DOCTYPE html>
<html>
  <head></head>
  <body>
    <h3>Simple Calculator</h3>
    <br/>
    <style>
      #calc{width:300px;height:250px;}
      #btn{width:100%;height:40px;font-size:20px}
    </style>
    <form Name="calc">
    <table id="calc"border=2>
      <tr>
        <td colspan=5><input id="btn"name="display" onkeypress="return event.charcode>=48&&event.charcode<=57"type="text"></td>
        <td style="display:none"><input name ="M"type="number"></td>
      </tr>
      <tr>
        <td><input id="btn" type=button value="MC"onclick="calc.M.value=''"></td>
          <td><input id="btn" type=button value="0"onclick="calc.display.value+='0'"></td>
        <td><input id="btn" type=button value="1"onclick="calc.display.value+='1'"></td>
        <td><input id="btn" type=button value="2"onclick="calc.display.value+='2'"></td>
        <td><input id="btn" type=button value="+"onclick="calc.display.value+='+'></td>
          </tr>
          <tr>
          <td><input id="btn" type=button value="MS"onclick="calc.M.value=calc.display.value"></td>
          <td><input id="btn" type=button value="3"onclick="calc.display.value+='3'"></td>
          <td><input id="btn" type=button value="4"onclick="calc.display.value+='4'"></td>
          <td><input id="btn" type=button value="5"onclick="calc.display.value+='5'"></td>
          <td><input id="btn" type=button value="-"onclick="calc.display.value+='-'"></td>
          </tr>
          <tr>
          <td><input id="btn" type=button value="MR"onclick="calc.display.value=calc.M.value"><?td>
          <td><input id="btn" type=button value="6"onclick="calc.display.value+='6'"></td>
                                       
