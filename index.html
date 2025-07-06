<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <title>Bingo - Casamento Belsa 💍</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      background: #fff5f8;
      margin: 0;
      padding: 20px;
    }
    h1 {
      color: #c94f7c;
    }
    #bingo-board {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      width: 500px;
      margin: 20px auto;
      gap: 5px;
    }
    .cell {
      background: white;
      border: 2px solid #ffb6c1;
      padding: 15px;
      cursor: pointer;
      transition: 0.2s;
      border-radius: 8px;
    }
    .cell:hover {
      background: #ffe6ee;
    }
    .cell.marked {
      background: #ffc6d6;
      text-decoration: line-through;
      font-weight: bold;
    }
    #message {
      font-size: 1.5em;
      color: #d6336c;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1>Bingo - Casamento Belsa 💍</h1>
  <div id="bingo-board"></div>
  <p id="message"></p>

  <script>
    const frasesCasamento = [
      "Convidados pedem mais um beijo", "Alguem grita Viva os noivos!", "Padrinhos dancam juntos", "Convidados ", " ",
      " ", " ", " ", " ", " ",
      " ", " ", " ", " ", " ",
      " ", " ", " ", " ", " ",
      " ", " ", " ", " ", " "
    ];

    const board = document.getElementById("bingo-board");
    const message = document.getElementById("message");

    function shuffle(array) {
      return array.sort(() => Math.random() - 0.5);
    }

    function createBoard() {
      const selecionadas = shuffle(frasesCasamento).slice(0, 25);
      for (let i = 0; i < 25; i++) {
        const cell = document.createElement("div");
        cell.classList.add("cell");
        cell.innerText = selecionadas[i];
        cell.addEventListener("click", () => marcarCelula(cell, i));
        board.appendChild(cell);
      }
    }

    function marcarCelula(cell, index) {
      cell.classList.toggle("marked");
      if (verificaBingo()) {
        message.innerText = "🎉 BINGO  AMOR! 🎉";
      }
    }

    function verificaBingo() {
      const cells = document.querySelectorAll(".cell");
      const grid = Array.from(cells).map(c => c.classList.contains("marked"));

      const linhas = [0, 5, 10, 15, 20].map(i => [i, i+1, i+2, i+3, i+4]);
      const colunas = [0, 1, 2, 3, 4].map(i => [i, i+5, i+10, i+15, i+20]);
      const diagonais = [[0,6,12,18,24], [4,8,12,16,20]];

      const todas = [...linhas, ...colunas, ...diagonais];

      return todas.some(indices => indices.every(i => grid[i]));
    }

    createBoard();
  </script>
</body>
</html>
