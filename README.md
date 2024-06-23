<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fortnite Accounts zum Verkauf</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        header nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }
        header nav ul li {
            display: inline;
            margin: 0 15px;
        }
        header nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            overflow: hidden;
        }
        .account-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .account {
            background: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            margin: 10px;
            width: calc(25% - 20px);
            box-sizing: border-box;
            padding: 20px;
            text-align: center;
        }
        .account img {
            max-width: 100%;
            height: auto;
        }
        .account h3 {
            margin: 10px 0;
            color: #333;
        }
        .account p {
            color: #666;
        }
        .account .price {
            color: #e60000;
            font-weight: bold;
            margin: 10px 0;
        }
        .account a {
            text-decoration: none;
            color: inherit;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            width: 100%;
            bottom: 0;
        }
        .button {
            background-color: #e60000;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
        }
        .hidden {
            display: none;
        }
        form label {
            display: block;
            margin: 10px 0 5px;
        }
        form input {
            padding: 10px;
            width: 100%;
            box-sizing: border-box;
            margin-bottom: 20px;
        }
        form button {
            background-color: #e60000;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Fortnite Accounts zum Verkauf</h1>
        <nav>
            <ul>
                <li><a href="#" onclick="showPage('home')">Startseite</a></li>
                <li><a href="#" onclick="showPage('about')">Über uns</a></li>
                <li><a href="#" onclick="showPage('contact')">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <div id="home" class="container">
        <div class="account-list">
            <div class="account" onclick="showPage('account1')">
                <img src="https://via.placeholder.com/150" alt="Fortnite Account 1">
                <h3>Account 1</h3>
                <p>Level 150, 2000 V-Bucks</p>
                <p class="price">€50</p>
            </div>
            <div class="account" onclick="showPage('account2')">
                <img src="https://via.placeholder.com/150" alt="Fortnite Account 2">
                <h3>Account 2</h3>
                <p>Level 100, 1000 V-Bucks</p>
                <p class="price">€40</p>
            </div>
            <div class="account" onclick="showPage('account3')">
                <img src="https://via.placeholder.com/150" alt="Fortnite Account 3">
                <h3>Account 3</h3>
                <p>Level 200, 3000 V-Bucks</p>
                <p class="price">€60</p>
            </div>
            <div class="account" onclick="showPage('account4')">
                <img src="https://via.placeholder.com/150" alt="Fortnite Account 4">
                <h3>Account 4</h3>
                <p>Level 250, 4000 V-Bucks</p>
                <p class="price">€70</p>
            </div>
        </div>
    </div>

    <div id="account1" class="container hidden">
        <div class="account-detail">
            <img src="https://via.placeholder.com/300" alt="Fortnite Account 1">
            <h3>SUPER MYSTERY BOX</h3>
            <p>Level 150, 2000 V-Bucks</p>
            <p class="price">€50</p>
            <a href="#" class="button" onclick="showPage('payment')">Mit Paysafecard kaufen</a>
        </div>
    </div>

    <div id="account2" class="container hidden">
        <div class="account-detail">
            <img src="https://via.placeholder.com/300" alt="Fortnite Account 2">
            <h3>RARE MYSTERY BOX</h3>
            <p>Level 100, 1000 V-Bucks</p>
            <p class="price">€40</p>
            <a href="#" class="button" onclick="showPage('payment')">Mit Paysafecard kaufen</a>
        </div>
    </div>

    <div id="account3" class="container hidden">
        <div class="account-detail">
            <img src="https://via.placeholder.com/300" alt="Fortnite Account 3">
            <h3>Stacked Chance Account</h3>
            <p>Level 200, 3000 V-Bucks</p>
            <p class="price">€60</p>
            <a href="#" class="button" onclick="showPage('payment')">Mit Paysafecard kaufen</a>
        </div>
    </div>

    <div id="account4" class="container hidden">
        <div class="account-detail">
            <img src="https://via.placeholder.com/300" alt="Fortnite Account 4">
            <h3>Black Knight + Rare Skins</h3>
            <p>Level 250, 4000 V-Bucks</p>
            <p class="price">€70</p>
            <a href="#" class="button" onclick="showPage('payment')">Mit Paysafecard kaufen</a>
        </div>
    </div>

    <div id="payment" class="container hidden">
        <h2>Zahlung mit Paysafecard</h2>
        <p>Bitte geben Sie den Code Ihrer Paysafecard ein, um den Kauf abzuschließen.</p>
        <form action="#" method="post" onsubmit="alert('Zahlung mit Paysafecard abgeschlossen!'); return false;">
            <label for="paysafe-code">Paysafecard Code:</label>
            <input type="text" id="paysafe-code" name="paysafe-code" required>
            <button type="submit">Bezahlen</button>
        </form>
    </div>

    <footer class="footer">
        
    <script>
        function showPage(pageId) {
            const pages = document.querySelectorAll('.container');
            pages.forEach(page => {
                if (page.id === pageId) {
                    page.classList.remove('hidden');
                } else {
                    page.classList.add('hidden');
                }
            });
        }
    </script>
</body>
</html>
