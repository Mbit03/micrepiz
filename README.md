# micrepiz
<!DOCTYPE html>
<html>
<head>
    <title>Accesso Protetto</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        #content {
            display: none;
        }
        input, button {
            padding: 10px;
            font-size: 16px;
            margin: 5px;
        }
    </style>
</head>
<body>
    <h1>Benvenuto!</h1>
    <div id="login">
        <p>Inserisci la password per accedere al contenuto:</p>
        <input type="password" id="password" placeholder="Password">
        <button onclick="checkPassword()">Accedi</button>
    </div>

    <div id="content">
        <h2>Contenuto Protetto</h2>
        <p>Questo è il testo che vuoi mostrare, ad esempio:</p>
        <p>
            "Benvenuto! Questo è il testo della canzone creata per il nostro re Michele, che da sempre ci tratta come signori, e ci fa mangiare da dio.
            (verso 1)
In un angolo della città, c'è una pizza da provare,
Michele Crepizza è il re, non puoi non assaporare.
Con le mani di ciola, impasta come un maestro,
“Questa pizza è speciale”, Michele ti scopo!”
(coro)
Michele, Michele, re della pizzeria,
Con il figlio Roberto in cucina,
Condisce le pizze con una a sorpresa,
Un tocco di sborra, un po' di passione,
Ogni morso è pura illusione!
La burrata diventa subito sbarrata!!

E tu chiami Claudio, lui sa cosa fare,
La trilogy in contante, senza scontrino da dare!
(verso 2)
La moglie in cucina, con le mani di ciola di Michele prepara il tiramisù
Un pizzico di dolcezza, un po’ di verità,
E nel menu delle pizze, un segreto da custodire, chissà!
E le pizze fatte con lo squirt della moglie
Michele sorride, un gran signore,
Con un segreto nel suo cuore,
Ogni sorso è un’esplosione,
Il suo liquido seminale fa vibrare la passione!
(Ritornello)
Michele, Michele, il re della pizza,
Con un limoncello che ti conquista!
E se paghi in contanti sei il preferito,
Niente scontrino, è il suo rito!
(Bridge)
Claudio arriva, prende la trilogy,
Pagando sempre in cash, fa felice il nostro re!
Michele storce il naso se qualcuno paga con la carta,
Perché le tasse non lo toccano, questa è la sua arte.
(Ritornello)
Michele, Michele, il re della pizza,
Con un limoncello che ti conquista!
E se paghi in contanti sei il preferito,
Niente scontrino, è il suo rito!
(Outro)
Siamo a Crepizza, il regno del divertimento,
e il limoncello sempre offerto.
Canta con noi, alza il bicchiere,
Per Michele Crepizza, per sempre in cima al potere!"
        </p>
    </div>

    <script>
        function checkPassword() {
            const input = document.getElementById("password").value;
            const correctPassword = "MICHELETISCOPO"; // Sostituisci con la password che vuoi usare
            if (input === correctPassword) {
                document.getElementById("login").style.display = "none";
                document.getElementById("content").style.display = "block";
            } else {
                alert("Password errata! Riprova.");
            }
        }
    </script>
</body>
</html>
