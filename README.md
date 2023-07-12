
<!DOCTYPE html>
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
        <h2>Intrebare:</h2>
        <p>Vrei să mergem într-o vacanță împreună?</p>

        <h3>Variante de răspuns:</h3>
        <ul>
            <li>Nup, îmi pare tare rău</li>
            <li>Hmm, nu știu ce să zic</li>
            <li>Nu am timp</li>
            <li>YES</li>
        </ul>
    </div>
</body>
</html>
