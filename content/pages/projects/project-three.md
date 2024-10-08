---
type: ProjectLayout
title: One more cool project
colors: colors-a
date: '2024-10-08'
client: Welcome
description: ''
featuredImage:
  type: ImageBlock
  url: /images/bg3.jpg
  altText: Project thumbnail image
media:
  type: ImageBlock
  url: /images/photo_2024-10-08_18-22-20.jpg
  altText: Project image
---
this is my projects code :P

<!DOCTYPE html>

<html lang="uz">

<head>

    <meta charset="UTF-8"> 

   <meta name="viewport" content="width=device-width, initial-scale=1.0">  

  <title>Matnni Teskari Aylantirish</title>  

  <style>   

     body {            font-family: Arial, sans-serif;            padding: 20px;        } 

       input, button {            margin: 5px 0;        }

    </style>

</head>

<body>  

  <h1>turning text backwards</h1>   

 <input type="text" id="matn" placeholder="enter the text and click the button">

    <button onclick="teskariAylantir()">backward it</button>   

 <h2>result</h2> 

   <p id="natija"></p>


    \<script>    

    function teskariAylantir() {      

      var matn = document.getElementById('matn').value;         

   var teskariMatn = matn.split('').reverse().join(''); 

           document.getElementById('natija').innerText = teskariMatn;   

     } 

   </script>

</body>

</html>


