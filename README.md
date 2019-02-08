# NHS-Computer-Science
NHS Computer Science
<html>
<head>
<title>no u</title>
<style>
table, tr, td   {
                border:solid 1px;
                border-collapse: collapse;
}
        body {
                color:#ff9400
                }
</style>

<script>
function clicked_one(){
  document.getElementById('mytextbox').value+='1'; 
}
function clicked_two(){
  document.getElementById('mytextbox').value+='2';
}
function clicked_three(){
  document.getElementById('mytextbox').value+='3';
}
function clicked_add(){
  document.getElementById('mytextbox').value+='+';
}



function clicked_four(){
  document.getElementById('mytextbox').value+='4';
}
function clicked_five(){
  document.getElementById('mytextbox').value+='5';
}
function clicked_six(){
  document.getElementById('mytextbox').value+='6';
}
function clicked_sub(){
  document.getElementById('mytextbox').value+='-';
}



function clicked_seven(){
  document.getElementById('mytextbox').value+='7';
}
function clicked_eight(){
  document.getElementById('mytextbox').value+='8';
}
function clicked_nine(){
  document.getElementById('mytextbox').value+='9';
}
function clicked_multi(){
  document.getElementById('mytextbox').value+='*';
}

function clicked_zero(){
  document.getElementById('mytextbox').value+='0';
}
function clicked_eq(){
  //document.getElementById('mytextbox').value+='=';
  var result = eval(document.getElementById('mytextbox').value);  
  document.getElementById('mytextbox').value=result; 
}
function clicked_divi(){
  document.getElementById('mytextbox').value+='/';
}

function clicked_c(){
	document.getElementById('mytextbox').value=' ';
}
function clicked_deci(){
	document.getElementById('mytextbox').value+='.';
}
</script>
</head>




<table>
		<tr>
        	<td colspan="4" style="background-color:white;width:125px;height:75px;"><input type="text" style="width:332px;height:125px;font-size:32px;" id="mytextbox"></input></td>
            </tr>
        <tr>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"> <input type="button" style="width:80px;height:75px;"value="       1        " onclick="clicked_one()"></td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:80px;height:75px;" value="       2        " onclick="clicked_two()"> </td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button"style="width:80px;height:75px;" value="       3        " onclick="clicked_three()"> </td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:80px;height:75px;" value="       +        " onclick="clicked_add()"></td>
             </tr>        

             
		<tr>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:80px;height:75px;" value="       4        " onclick="clicked_four()"> </td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:80px;height:75px;" value="       5        " onclick="clicked_five()"> </td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:80px;height:75px;" value="       6        " onclick="clicked_six()"> </td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:80px;height:75px;" value="        -        " onclick="clicked_sub()"></td>
		</tr>
        
        <tr>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:80px;height:75px;" value="       7        " onclick="clicked_seven()"> </td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:80px;height:75px;" value="       8        " onclick="clicked_eight()"> </td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"> <input type="button" style="width:80px;height:75px;" value="      9         " onclick="clicked_nine()"></td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:80px;height:75px;" value="        *        " onclick="clicked_multi()"></td>
		</tr>
        
       <tr>
               
                <td colspan="2" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:165px;height:75px;" value="                   =                  " onclick="clicked_eq()"></td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"><input type="button" style="width:80px;height:75px;" value="       0        " onclick="clicked_zero()"> </td>
                <td rowspan="1" style="background-color:white;width:75px;height:75px;"> <input type="button" style="width:80px;height:75px;" value="        /        " onclick="clicked_divi()"></td>
		</tr>
        <tr>
        <td colspan="2" style="background-color:white;width:125px;height:35px"> <input type="button" style="width:165px;height:35px;" value="     C     " onclick="clicked_c()"></td>
        <td rowspan="1" style="background-color:white;width:80px;height:35px;"> <input type="button" style="width:80px;height:35px;" value="       .      " onclick="clicked_deci()"></td>
        </tr>
</table>
</body>
</html>
