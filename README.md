<html>
<head>
    <title>Intrebare pentru tine</title>
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
        <h2>Acceseaza urmatorul LINK, te rog :)</h2>
        <p>https://docs.google.com/forms/d/e/1FAIpQLSdthvpQbEprWZ3iQ3euHddUU6gjko-03djuptSa8-hsSbtlww/viewform?usp=sf_link</p>
    </div>
</body>
</html>
