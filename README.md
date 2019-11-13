<!DOCTYPE html>
<html>
<style>
@font-face
{font-family: "Times New Roman", Times, serif;}
#numele{
color:blue;
}
#email{
color:red;
}
#citat{
color:yellow;
}
#materii{
color:orange;
}
#tabel{
color:green;
}
#hobby{
color:gray;
}

body {
    margin: 0;
    width: 100%;
    height: 100vh;
    font-family: "Exo", sans-serif;
    color: #fff;
    background: linear-gradient(-45deg, #ff6600, #ff3300, #ffcc00, #00ffff);
    background-size: 400% 400%;
    animation: gradientBG 15s ease infinite;
}

 

@keyframes gradientBG {
    0% {
        background-position: 0% 50%;
    }
    50% {
        background-position: 100% 50%;
    }
    100% {
        background-position: 0% 50%;
    }
}

 

.container {
    width: 100%;
    position: absolute;
    top: 35%;
    text-align: center;
}

 

h1 {
    font-weight: 300;
}

 

h3 {
    color: #eee;
    font-weight: 100;
}

 

h5 {
    color:#eee;
    font-weight:300;
}

 

a,
a:hover {
    text-decoration: none;
    color: #ddd;
}

 

h1   {color: blue;}
h3   {color: red;}
table {color: green;}
table {background-color: white;}
#poza{
align:center;
border-radius:50%;
}
table,th,td{
border: 1px solid black;
}
th{
text-align:left;
}
table{
width: 100%;
}
#hobby{
border: 1px solid black;}
</style>
<head>
<script>
function myFunction(){
		      document.getElementByById("demo").innerHTML = "Vanca Rafael"
			  
			  var tabelEducație = document.getElementById("tabelEducație");
			      tabelEducație.rows[0].cells[0].innerHTML = "";
			      tabelEducație.rows[0].cells[2].innerHTML = "";
			      tabelEducație.rows[1].cells[0].innerHTML = "";
			      tabelEducație.rows[1].cells[2].innerHTML = "";
			      tabelEducație.rows[2].cells[0].innerHTML = "";
			      tabelEducație.rows[2].cells[1].innerHTML = "Anul II(Licenta)";
			      tabelEducație.rows[2].cells[2].innerHTML = "";
			  
			  document.getElementById("1.jpg").src="2.jpg";
			  
			  document.body.style.backgroundColor ="white";
			  
			  var par = document.getElementsByTagName("p");
			  var i;
			  
			  for(i=0; i<par.length; i++) {
			      par(i).style.color = "maroon";
				  }
			document.getElementById("pozaProfil").style.opacity = "1.0";
			document.getElementById("pozaProfil").style.border = "15px";
		}
		
		function arataVarsta()   {
		     var azi = new Data;
			 var varstaMea;
			 
			 var anNasc = document.getElementById("varsta").innerHTML;
			 var anCurent = azi.getFullYear();
			 
			 varstaMea= anCurent - parseInt(anNasc);
			 
			 document.getElementById("varsta").innerHTML = varstaMea;
			 }
</script>
<title>Stefancu Dragos-Alexandru</title>
<body>
<h1 id="demo">Stefancu Dragos</h1>
<button onclick="myFunction()">Click</button
<p><b>Nume:</b> <i>Stefancu</i></p>
<p><b>Prenume:</b> <i>Dragos-Alexandru</i></p>
<p><b>mail:</b> <i>Stefancu.Dr.Dragos@utcluj.didatec.ro</i></p>
<p><b>mail:</b> <i>alex_stefancu@yahoo.com</i></p>
<img src="1.jpg"></img>
<p><b>Citat:</b><i>Distractia dureaza o noapte, educatia iti va ramane toata viata</i></p>
<p><b>Discipline</p></b>
<table style="width:100%"  border="1">
<tr>
<th>Discipline</th>

</tr>

<tr>
<td><center>Programarea calculatoarelor-Limbaje Anul 1</center></td>
<td><center></i><a href="url">https://etti.utcluj.ro/files/FiseDisciplina/TstRo/EL3101.pdf</a></center></td>
</tr>

<tr>
<td><center>Fizica Anul 1</center></td>
<td><center></i><a href="url">https://etti.utcluj.ro/files/FiseDisciplina/TstRo/EL3103.pdf</a></center></td>
</tr>

<tr>
<td><center>Analiza Anul 1</center></td>
<td><center></i><a href="url">https://etti.utcluj.ro/files/FiseDisciplina/TstRo/EL3101.pdf</a></center></td>
</tr>
</table>
<p><b>Hobby-uri:</b></p> 
<li><i>Tenis de masa</i></li>
<li><i>Desen</i></li>
<li><i>Sport la nivel amator</i></li>


</body>
</html>
