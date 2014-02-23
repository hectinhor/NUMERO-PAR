NUMERO-PAR
==========
<!doctype html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
  <script language="javascript"> </script>

</head>

<body>

<form method="post" onSubmit="return validar();">
   /* aqui  pido que ingrese un numero par  */
<script type="text/javascript">
  var scrib;
  <label>  PROGRAMA QUE CALCULA NUMEROS PARES  </label>
  <label> "INGRESE UN NUMERO "</label>
  <input type="text" name="scrib" id="scrib"  />

  if (scrib % 2 == 0)
  {
    {
      document.write('El numero  es par');
    }
  else 
    {
      document.write('El numero  es impar');
    }
  }
</script>

</body>
/* aqui escribo la funcion validar */
<script> 
function validar()
{
  var scrib = document.getElementsById('escriba mumero').value
  if(scrib=="")
  {
    alert("debes ingresar un numero");
    return false;
  }
}
</script>

</html>
