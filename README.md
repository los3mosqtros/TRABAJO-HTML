# TRABAJO-HTML
<br>
este codigo hace que el nombre ingresado por el usuario lo transforme para que la letra principal la pongo en mayuscula y lo demas l ponga en minuscula dandole un formato diferente sin importar como lo ingreso el usuario convina el html con javascript
<br>
<pre>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        var nom,ap1,ap2,mnom,map1,map2;
        while(nom==null){
            nom=prompt("INGRESA TU NOMBRE");

        }
        while(ap1==null){
            ap1=prompt("INGRESE SU PRIMER APELLIDO ");
        }
        while(ap2==null){
            ap2=prompt("INGRESE SU SEGUNDO APELLIDO");
        }

        mnom=nom.charAt(0).toUpperCase()+nom.slice(1).toLowerCase();
        map1=ap1.charAt(0).toUpperCase()+ap1.slice(1).toLowerCase();
        map2=ap2.charAt(0).toUpperCase()+ap2.slice(1).toLowerCase();
        


        document.write("<b>EL NOMBRE ES: "+ nom+" "+ap1+" "+ap2+"<br></b>");
        document.write("<br><b>EL NOMBRE MODIFICADO ES: "+ mnom+" "+map1+" "+map2+"</b>");

    </script>
</body>
</html>
  
</pre># TRABAJO-HTML
