<html>

<head>
    <meta charset="utf-8">
    <title> KaykyDS102</title>

</head>

<body>
    <h1> O Rei leão </h1>
    <p id="p1"> Agora vamos </p>

    nome: <input id="idnome" type="text"> </input>
    sobrenome:<input id="idsobrenome" type="text"> </input>



    <button onclick="preencher()"> Enviar </button>



    <script>
        function preencher() {
            document.getElementById("p1").innerHTML = "macaco de rodas ";



            var nome = document.getElementById("idnome").value;
            var sobrenome = document.getElementById("idsobrenome").value;
            var nomecompleto = nome + " " + sobrenome;
            alert(nomecompleto);
        }
    </script>



</body>
