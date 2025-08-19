<?php include '../config.php'; ?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Jute Card Game Demo</title>
    <link rel="stylesheet" href="../assets/css/style.css">
    <style>
        body { font-family: Arial; text-align: center; }
        .card { display: inline-block; width: 80px; height: 120px; border: 1px solid #000; margin: 5px; line-height: 120px; font-size: 24px; cursor: pointer; }
        .selected { background-color: #f39c12; color: #fff; }
    </style>
</head>
<body>
    <h1>Jute Card Game Demo</h1>
    <p>Click cards to select 3 sets (3 cards each) + 1 set of 4 cards</p>
    <div id="gameBoard"></div>
    <p><button onclick="checkSets()">Check Selection</button></p>
    <p id="result"></p>

    <script>
        const gameBoard = document.getElementById('gameBoard');
        let selectedCards = [];

        // Generate 14 demo cards (A, B, C, D, E, F, G)
        const cards = ['A','A','A','B','B','B','C','C','C','D','D','D','E','E'];
        cards.forEach((card, index) => {
            const div = document.createElement('div');
            div.className = 'card';
            div.innerText = card;
            div.onclick = () => toggleCard(div, card);
            gameBoard.appendChild(div);
        });

        function toggleCard(div, card) {
            if (selectedCards.includes(div)) {
                div.classList.remove('selected');
                selectedCards = selectedCards.filter(c => c !== div);
            } else {
                if (selectedCards.length < 14) {
                    div.classList.add('selected');
                    selectedCards.push(div);
                }
            }
        }

        function checkSets() {
            const counts = {};
            selectedCards.forEach(div => {
                const val = div.innerText;
                counts[val] = (counts[val] || 0) + 1;
            });
            const set3 = Object.values(counts).filter(v => v === 3).length;
            const set4 = Object.values(counts).filter(v => v === 4).length;
            if (set3 === 3 && set4 === 1) {
                document.getElementById('result').innerText = "🎉 You completed the Jute game correctly!";
            } else {
                document.getElementById('result').innerText = "❌ Selection is not valid. Try again.";
            }
        }
    </script>
</body>
</html>