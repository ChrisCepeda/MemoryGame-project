# MemoryGame-project

Memory card game as our first group project
Hello world, trying stuff out

Todo list

1. responsive container
2. more pop ups linked to menu options
3. close button


<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="css/style.css">
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
  
  <title>Memory Card Game - how fun!!!!!</title>
</head>

<body>
  <nav>
    
   <div class="logo">
    <h1>Memory</h1></div>

    <ul class="nav-links nav-active">
      <li><a class="#"><a id="myBtn">about</a> </li>
  
      <li><a href="game">rules</a></li>
      <li><a href="game">game</a></li>  
    </ul>
    

    <div class="burger toggle">
      <div class="line1"></div>
      <div class="line2"></div>
      <div class="line3"></div>
    </div>
  </nav>
 
<main>
 

 
  
  <!-- The Modal -->
  <div id="myModal" class="modal">
  
    <!-- Modal content -->
    <div class="modal-content">
    
    
      <div class="card">
        <img src="images/Artboards_Diversity_Avatars_by_Netguru-19.png" alt="Avatar" style="width:100%">
        <div class="container">
          <h4><b>Tintin Hamrin</b></h4>
          <p>Frontend Developer student <br>
            <a href="mailto:tintin.hamrin@hyperisland.se"><img src="images/mailicon.png" style="width:16px"></a>
          </p>
        </div>
      </div>

      <div class="card">
        <img src="images/Artboards_Diversity_Avatars_by_Netguru-14.png" alt="Avatar" style="width:100%">
        <div class="container">
          <h4><b>Birk Kensén</b></h4>
          <p>Frontend Developer student <br>
            <a href="mailto:birk.kensen@hyperisland.se"><img src="images/mailicon.png" style="width:16px"></a>
          </p>
        </div>
      </div>
  
      <div class="card">
        <img src="images/Artboards_Diversity_Avatars_by_Netguru-11.png" alt="Avatar" style="width:100%">
        <div class="container">
          <h4><b>Christina Cepeda</b></h4>
          <p>Frontend Developer student <br>
            <a href="mailto:christina.cepeda@hyperisland.se"><img src="images/mailicon.png" style="width:16px"></a>
          </p>
        </div>
      </div>

      <div class="card">
        <img src="images/Artboards_Diversity_Avatars_by_Netguru-08.png" alt="Avatar" style="width:100%">
        <div class="container">
          <h4><b>Johan Klingström</b></h4>
          <p>Frontend Developer student <br>
            <a href="mailto:johan.klingstrom@hyperisland.se"><img src="images/mailicon.png" style="width:16px"></a>
          </p>
        </div>
      </div>
      
      <span class="close">&times;</span>
      

        
        


    </div>
</div>

</main>


<script src="scripts/script.js"></script>
</body>

</html>