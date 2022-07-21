# aulacursoGuanabara
Sétima aula do curso do Guanabara em JavaScript

```

<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>aula 007 curso do Guanabara </title>
</head>
<style>
  input#but{
   color: blue;
   width: 70px;
   height: 40px;
   border: 50px;
   border-color: blue;
   border-width: 50px;
   text-align: center;
   line-height: 40px;
   left: 5px;
   border-left-width: 7770px;
  }
</style>

<body>
  
  <h1>
    adicionando números 
  </h1>
  <input type="number" name="text1" id="text1" placeholder="Digite um número" required="teb" > +
  <input type="number" name="text2" id="text2" placeholder="digite outro número">+
  <input type="button" value="somar" onclick="soma()" id="but">
  <script>
  function soma(){
   var var1 = window.document.getElementById("text1")
   var var2 = window.document.getElementById("text2")
   
   n1 = Number(var1.value)
   n2 = Number (var2.value)
   document.write(` <br> a soma entre ${n1} + ${n2} é igual a = ${n1 + n2}`)
    
    
  }
    
  </script>
</body>

</html>
```
