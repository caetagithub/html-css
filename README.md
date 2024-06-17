<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curso em Vídeo - HTML/CSS</title>
    <style>
      /* Paleta de cores */
      :root {
         --yale-blue: #083d77;
         --beige: #ebebd3;
         --naples-yellow: #f4d35e;
         --sandy-brown: #ee964b;
         --tomato: #f95738;
      }
      * {
         font-family: Arial, Helvetica, sans-serif;
         padding: 0px;
         margin: 0px;
         box-sizing: border-box;
      }
      body, html {
         background-color: var(--yale-blue);
         height: 100vh;
         width: 100vw;
      }
      main {
         position: relative;
         height: 76vh;
         width: 100vw;
      }
      header {
         background-color: var(--sandy-brown);
      }
      header > h1 {
         text-align: center;
         padding: 10px;
         font-variant: small-caps;
      }
      header > p {
         padding: 10px 20px;
      }
      div.container {
         position: absolute;
         overflow: auto;
         top: 50%;
         left: 50%;
         background-color: #ebebd3;
         height: 100%;
         width: 400px;
         transform: translate(-50%, -50%);
      }
      div.container > table {
         position: absolute;
         top: 50%;
         left: 50%;
         margin: auto;
         text-align: center;
         line-height: 43px;
         border: 1px solid var(--tomato);
         color: var(--yale-blue);
         transform: translate(-50%, -50%);
      }
      div.container > table > caption {
         background-color: var(--tomato);
         color: var(--beige);
         font-variant: small-caps;
      }
      footer {
         background-color: #ee964b;
         padding: 10px 20px;
         text-align: center;
      }
      footer a {
         text-decoration: none;
         color: var(--beige);
         padding: 5px 0px;
      }
      footer a:hover {
         background-color: #083d77;
      }


    </style>
</head>
   <body>
   <header>
      <h1>Curso em Vídeo - HTML/CSS</h1>
      <p>Exercícios, desafios e projetos feitos para o Curso de HTML/CSS do Curso em Vídeo promovido pelo professor Gustavo Guanabara.</p>
   </header>
   <main>
      <div class="container">
         <table>
            <caption>Conteúdo</caption><br>
            <thead>
               <tr>
                  <th>Descrição</th>
                  <th>Completado?</th>
               </tr>
            </thead>
            <tbody>
               <tr>
                  <td>Exercícios e Desafios do Módulo 1</td>
                  <td>Sim</td>
               </tr>
               <tr>
                  <td>Exercícios e Desafios do Módulo 2</td>
                  <td>Sim</td>
               </tr>
               <tr>
                  <td>Exercícios e Desafios do Módulo 3</td>
                  <td>Sim</td>
               </tr>
               <tr>
                  <td>Exercícios e Desafios do Módulo 4</td>
                  <td>Sim</td>
               </tr>
               <tr>
                  <td>Exercícios e Desafios do Módulo 5</td>
                  <td><span class="material-symbols-outlined">hourglass_top</span></td>
               </tr>
            </tbody>
         </table>
      </div>
   </main>
   <footer>
      <p>Todo o conteúdo está armazenado e pode ser acessado em <a href="https://github.com/caetagithub" target="_blank">Git Hub de Ricardo Caetano</a>.</p>
   </footer>
   </body>
</html>