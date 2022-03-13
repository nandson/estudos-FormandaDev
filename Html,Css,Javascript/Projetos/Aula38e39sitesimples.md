# # projeto site simples
"""js
index.html


<!DOCTYPE html> 

<html lang="pt-br"> 

<head> 

  <meta charset="utf-8">
  <title>site simples </title>

  <!-- link para conectar o arquivo .css -->
  <link rel= "stylesheet" href= "style.css">

</head> 



<body> 
    
   <head>

   <!-- cabeçalho, título -->
   <h1> titulo </h1>

  </head>
   
  <!-- onde ficar as div -->

  <section>

   <div> testando </div>

   <div> olá formando dev </div>

  </section>
    
  <!-- rodapé -->
  <footer>

   <p>&copy; formando dev </p>

  </footer>

  
<!-- conectar o arquivo script.js -->
<script src="script.js"></script>
</body> 



</html>


"""

"""js
style.css


/*estilização*/

  body {

     background-color: blue; /*cor de fundo*/
     font: normal 15pt arial

}

/*cabeçalho, titulo*/

head {
     
     color: white;
     text-align: center; /*cetralizar o texto no meio da tela*/
}

/* onde ficar as div */
section {
    background-color: white; /*cor de fundo*/
    border-radius: 10px; /*arredondar os cantos*/
    padding: 15px; /*tamanho do quadrado*/
    widht: 500px; /*largura*/
    margin: auto; /*centralizar no meio da tela*/
   
    /*deslocamento lateral, deslocamento vertical, espalhamento,cor*/
    box-shadow: 5px 5px 10px green;
}

/*rodapé*/
footer {

    color: white; /*cor do texto*/
    text-align: center; /*centralizar no meio da tela*/
    font-style: italic; /*estilo da fonte*/

}

"""

