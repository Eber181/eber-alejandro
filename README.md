# sumaeber
primer proyecto con github

<html> <!--Nombre:Eber Alejandro Padilla Mar-->>
<head>
     <head> 
          <title>github</title>
          </head>
        <body>
              <font color="white" size="60">
                   <h4> suma </h4>
                   </font>
                   </div>
<form name="calc">
<p>x:<input type="number" name="operando1" value="0" size="10">
<br>
<p>y:<input type="number" name="operando2" value="0" size="10">
<br>
<br>
<input type="button" name="" value="suma +" onclick="calcula('+')">
<p>resultado:<input type="text" name="resultado" value="0" size="12">
        <input type="reset" value="resetear">

        </form>
        </body>

        <script>
           function calcula(operacion){
            var operando1 = document.calc.operando1.value
            var operando2 = document.calc.operando2.value
            var result = eval(operando1 + operacion + operando2)
            document.calc.resultado.value = result
           }
           </script>
           </body>
           </html>
           