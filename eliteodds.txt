<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Elite Odds</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #014421;
      color: white;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 30px;
      background-color: #003d1b;
    }
    .jerseys {
      display: flex;
      gap: 10px;
    }
    .jerseys img {
      height: 50px;
    }
    .auth-buttons a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }
    .main {
      text-align: center;
      padding: 40px 20px;
    }
    .main h1 {
      font-size: 2em;
      margin-bottom: 10px;
    }
    .main p {
      font-size: 1.1em;
    }
    .view-btn {
      background-color: #fcd116;
      color: #014421;
      padding: 15px 30px;
      border: none;
      font-size: 1em;
      font-weight: bold;
      margin-top: 20px;
      cursor: pointer;
    }
    .odds-section {
      background-color: #013417;
      padding: 30px;
    }
    h2 {
      text-align: center;
      color: #fcd116;
    }
    table {
      width: 100%;
      max-width: 600px;
      margin: auto;
      border-collapse: collapse;
      color: white;
    }
    th, td {
      padding: 15px;
      text-align: center;
    }
    th {
      color: #fcd116;
    }
    .buy-btn {
      background-color: #fcd116;
      color: #014421;
      padding: 10px 20px;
      border: none;
      font-weight: bold;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <header>
    <div class="jerseys">
      <img src="https://i.imgur.com/G8Z1O9J.png" alt="Man U">
      <img src="https://i.imgur.com/CdLrNTG.png" alt="Chelsea">
      <img src="https://i.imgur.com/YQb0Il6.png" alt="Barca">
      <img src="https://i.imgur.com/lQFJyxg.png" alt="Man City">
      <img src="https://i.imgur.com/zbdqu0c.png" alt="Arsenal">
    </div>
    <div class="auth-buttons">
      <a href="#">Login</a>
      <a href="#">Sign Up</a>
    </div>
  </header>

  <div class="main">
    <h1>BUY ODDS WITH PAYPAL</h1>
    <p>Instant access to daily and weekly betting odds</p>
    <button class="view-btn">VIEW ODDS</button>
  </div>

  <div class="odds-section">
    <h2>DAILY & WEEKLY ODDS</h2>
    <table>
      <thead>
        <tr>
          <th>Event</th>
          <th>Odds</th>
          <th>Price</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Manchester City vs. Arsenal</td>
          <td>1.80</td>
          <td><button class="buy-btn">BUY NOW</button></td>
        </tr>
        <tr>
          <td>Liverpool vs. Tottenham</td>
          <td>2.25</td>
          <td><button class="buy-btn">BUY NOW</button></td>
        </tr>
      </tbody>
    </table>
  </div>

</body>
</html>
