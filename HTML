<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Click for Cash</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 400px;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .balance-card {
            font-size: 24px;
            font-weight: bold;
            padding: 20px;
            background: #007bff;
            color: white;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .coin-balance {
            position: absolute;
            top: 10px;
            left: 10px;
            font-size: 16px;
            font-weight: bold;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        .click-btn {
            background-color: #28a745;
            color: white;
        }
        .watch-ad-btn {
            background-color: #ffc107;
            color: black;
            display: none;
        }
        .watch-ad-coins-btn {
            background-color: #ff5722;
            color: white;
        }
        .exchange-btn {
            background-color: #17a2b8;
            color: white;
        }
        .cashout-btn {
            background-color: #dc3545;
            color: white;
        }
    </style>
</head>
<body>

    <div class="coin-balance">Coins: <span id="coinBalance">0</span></div>

    <div class="container">
        <div class="balance-card">£<span id="moneyBalance">0.00</span></div>
        
        <button class="click-btn" onclick="clickForCash()">Click Me (£1.50)</button>
        <button class="watch-ad-btn" onclick="watchAd()">Watch Ad (£1)</button>
        <button class="watch-ad-coins-btn" onclick="watchAdForCoins()">Watch Ad for Coins</button>
        <button class="exchange-btn" onclick="exchangeCoins()">Exchange Coins</button>
        <button class="cashout-btn" onclick="cashOut()">Cashout</button>
    </div>

    <script>
        let cashBalance = 0;
        let clickCount = 0;
        let coinBalance = 0;

        function clickForCash() {
            cashBalance += 1.50;
            clickCount++;
            updateDisplay();

            if (clickCount >= 3) {
                document.querySelector('.watch-ad-btn').style.display = 'block';
            }
        }

        function watchAd() {
            alert("Watching ad... (Pretend an ad is playing)");
            setTimeout(() => {
                cashBalance += 1.00;
                updateDisplay();
                alert("Ad finished! You earned £1.");
            }, 3000);
        }

        function watchAdForCoins() {
            alert("Watching ad for coins...");
            setTimeout(() => {
                let coinsEarned = Math.floor(Math.random() * (1000 - 500 + 1)) + 500;
                coinBalance += coinsEarned;
                updateDisplay();
                alert(`You earned ${coinsEarned} coins!`);
            }, 3000);
        }

        function exchangeCoins() {
            if (coinBalance >= 10000) {
                let cashEarned = (coinBalance / 10000) * 0.01;
                cashBalance += cashEarned;
                coinBalance = 0;
                updateDisplay();
                alert(`Exchanged coins for £${cashEarned.toFixed(2)}!`);
            } else {
                alert("Not enough coins to exchange!");
            }
        }

        function cashOut() {
            let email = prompt("Enter your PayPal email:");
            if (email && cashBalance > 0) {
                alert(`Sending £${cashBalance.toFixed(2)} to ${email} via PayPal...`);
                cashBalance = 0;
                updateDisplay();
            } else {
                alert("Invalid email or insufficient balance!");
            }
        }

        function updateDisplay() {
            document.getElementById("moneyBalance").innerText = cashBalance.toFixed(2);
            document.getElementById("coinBalance").innerText = coinBalance;
        }
    </script>

</body>
</html>
