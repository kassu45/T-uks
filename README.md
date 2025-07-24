<!DOCTYPE html>
<html lang="et">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minu Elektritõuksi Soov</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f4f4f8;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 2rem;
    }

    .container {
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      max-width: 800px;
      width: 100%;
      padding: 2rem;
      text-align: center;
    }

    img {
      max-width: 100%;
      border-radius: 12px;
      margin-bottom: 1.5rem;
    }

    h1 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    p {
      line-height: 1.6;
      font-size: 1.1rem;
      text-align: left;
    }

    button {
      margin-top: 1.5rem;
      padding: 0.8rem 1.2rem;
      font-size: 1rem;
      border: none;
      background-color: #0078d7;
      color: white;
      border-radius: 8px;
      cursor: pointer;
    }

    button:hover {
      background-color: #005ea6;
    }

    @media (max-width: 600px) {
      .container {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Mu kallid vanemad</h1>
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Electric_scooter.jpg" alt="Elektriline tõukeratas">
    <p>
      Ma tahaksin väga saada endale elektrilist tõuksi. See oleks mulle turvaline, lõbus ja kasulik liikumisvahend.
    </p>
    <button onclick="näitaSõnum()">Vajuta siia</button>
  </div>

  <script>
    function näitaSõnum() {
      alert("Palun lubage mul saada elektritõuks – see on mulle väga oluline!");
    }
  </script>
</body>
</html>
