html5
=====
<html>
<head>
</head>

<body onload="generar()">

</body>
</html>
<script>
function generar()
{
	document.write("<div><center><h1>REGISTRO</h1></center></div>");
				document.write("<div><center>APELLIDO &nbsp&nbsp&nbsp&nbsp<input type='text' id='apellido' placeholder='apellido' required></center></div>");
					document.write("<div><center>NOMBRE &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp<input type='text' id='nombre'  placeholder='nombre' required></center></div>");
						document.write("<div><center>CEDULA &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp<input type='text' id='cedula'  placeholder='cedula' required></center></div>");
					document.write("<div><center>NIVEL &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp<input type='text' id='nivel'  placeholder='nivel' required></center></div>");
				document.write("<div><center>PARALELO&nbsp&nbsp&nbsp&nbsp<input type='text' id='paralelo'  placeholder='paralelo' required></center></div>");
			document.write("<div><center>TELEFONO&nbsp&nbsp&nbsp&nbsp<input type='text' id='telefono'  placeholder='telefono' required></center></div>");
		document.write("<form><center>CORREO &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp<input type='text' id='correo'  placeholder='correo' required></center>");
		document.write("<center><input type='submit' value='validar'correo' onclick='validar(form.correo.value)'></center></form>");
	document.write("<div><center>DIRECCION&nbsp&nbsp&nbsp&nbsp<input type='text' id='direccion' placeholder='direccion' required></center></div>");
document.write("<center>Sexo<SELECT NAME='sexo'> <OPTION VALUE=1> Mujer <OPTION VALUE=2> Hombre</SELECT></center>");
	
		document.write("<center><input type='submit' value='Registrar' id='btnSubmit'></center>");
		document.write("<center><header>Progreso de mi pagina</header><progress value='13' max='100'></center>")
		document.write("<header></header><br>sonido</br><audio controls='controls'> <source src='MACKLEMORE  RYAN LEWIS   THRIFT SHOP FEAT WANZ (OFFICIAL VIDEO).mp3' type='audio/mp3'/></audio>");
		document.write("<footer>Ariel Alvarez - Copyright 2013</footer>");
		
}
function validar(valor)
	{
	if(/^[A-Z-a-z-0-9]+@+[a-z]+.+[a-z]/.test(valor))
		{
		alert("correo"+valor+"es valido");
		return(true);
		}
		else
		{
		alert("correo invalido");
		return(false);
		}
	}
</script>
