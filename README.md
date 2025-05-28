# UC12-FRONT-END

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FAVORITES SONGS</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
  <table>
    <thead>
      <tr>
        <th>Capa do Álbum</th>
        <th>Nome da Música</th>
        <th>Artista</th>
        <th>Player de Áudio</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><img src="CAOS.jpg" alt="Capa do Álbum 1"></td>
        <td>DISCO DE PLATINA</td>
        <td>Alee</td>
        <td><audio controls><source src="shape-of-you.mp3" type="audio/mp3"></audio></td>
      </tr>
      <tr>
        <td><img src="moneytrees.jpg" alt="Capa do Álbum 2"></td>
        <td>Money Trees</td>
        <td>Kendrick Lamar, Jay Rock</td>
        <td><audio controls><source src="uptown-funk.mp3" type="audio/mp3"></audio></td>
      </tr>
      <tr>
        <td><img src="90210.jpg" alt="Capa do Álbum 3"></td>
        <td>90210</td>
        <td>Travis Scott</td>
        <td><audio controls><source src="happy.mp3" type="audio/mp3"></audio></td>
      </tr>
      <tr>
        <td><img src="Hea.jpg" alt="Capa do Álbum 4"></td>
        <td>Heaven Can't Wait</td>
        <td>Michael Jackson</td>
        <td><audio controls><source src="cant-stop-the-feeling.mp3" type="audio/mp3"></audio></td>
      </tr>
      <tr>
        <td><img src="album5.jpg" alt="Capa do Álbum 5"></td>
        <td>BRAZIL</td>
        <td>Kyan, Mu540, Dj Ery</td>
        <td><audio controls><source src="we-found-love.mp3" type="audio/mp3"></audio></td>
      </tr>
    </tbody>
  </table>
</body>
</html>


































body {
    font-family: 'Open Sans', sans-serif;
    background: #4d4949;
background: linear-gradient(90deg, rgba(77, 73, 73, 1) 100%, rgba(51, 48, 48, 1) 100%, rgba(51, 50, 54, 1) 0%);
  }
  
  table {
    border-collapse: collapse;
    width: 100%;
    margin: 80px auto;
    border: 1px solid #ddd;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  th, td {
    border: 1px solid #ddd;
    padding: 20px;
    text-align: center;
  }
  
  th {
    background-color: #f0f0f0;
  }
  
  tr:nth-child(even) {
    background-color: #f9f9f9;
  }
  
  tr:nth-child(odd) {
    background-color: #fff;
  }
  
  img {
    width: 50px;
    height: 50px;
    border-radius: 50%;
  }
  
  audio {
    width: 100%;
    height: 30px;
  }










