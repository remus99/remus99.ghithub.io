<html>
<head>
    <title>Intrebare pentru tine</title>
    <style>
        body {
            background-color: #f2f2f2;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        
        h1 {
            color: #333333;
        }
        
        #continut {
            background-color: #ffffff;
            border-radius: 8px;
            padding: 20px;
            margin: 20px auto;
            max-width: 400px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        button {
            background-color: #4caf50;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 4px;
            cursor: pointer;
        }
        
        button:hover {
            background-color: #45a049;
        }
    </style>
    <script>
        function verificaParola() {
            var parolaIntrodusa = document.getElementById("parola").value;
            var parolaCorecta = "Anda05"; // Parola corectă

            if (parolaIntrodusa === parolaCorecta) {
                document.getElementById("continut").style.display = "block";
            } else {
                alert("Parolă incorectă!");
            }
        }
    </script>
</head>
<body>
    <h1>Introdu parola:</h1>
    <input type="password" id="parola">
    <button onclick="verificaParola()">Accesează</button>

    <div id="continut" style="display: none;">
        <h2>Accesează următorul LINK, te rog :)</h2>
        <p>https://docs.google.com/forms/d/e/1FAIpQLSdsiiXgSDLJdWQah9ieHwJnWZIPix1OVjAiAD8MXbcP6iLW8A/viewform?usp=sf_link</p>
    </div>
</body>
</html>
