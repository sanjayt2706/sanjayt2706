<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web & Machine Learning Developer focused on building helpful applications and effective teams.</title></title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        input, button {
            font-size: 16px;
            padding: 10px;
            margin: 10px;
        }
    </style>
</head>
<body>
    <h1>Sanjay </h1>
    <input type="text" id="nameInput" placeholder="Your Name">
    <button onclick="displayMessage()">Submit</button>
    <p id="message"></p>

    <script>
        function displayMessage() {
            var name = document.getElementById('nameInput').value;
            var message = `Hello ${name}, don't waste your time by always watching your phone. You need a mental hospital, can you join?`;
            document.getElementById('message').textContent = message;
        }
    </script>
</body>
</html>
