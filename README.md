<html lang="pt-br">
<head>
    <meta charset="utf-8">
    <meta name="description" content="teste.com">
    <meta name="keywords" content="teste, celular, site_html">
    <meta name="author" content="Luciano Daltoé">
    <title>Teste no celular</title>

    <style> 
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: red;
        }

        h1 {
            color: white;
            text-align: center;
            font-size: 60px;
            margin: 0;
        }

        p { 
            color: white;
            text-align: center;
            font-size: 18px;
        }

        table { 
            border-collapse: collapse;
            width: 150px;
            margin-top: 30px;
        }

        td {
            border: 1px solid black;
            padding: 20px;
            text-align: center;
            font-size: 20px;
            background-color: black;
        }

        td a { 
            text-decoration: none;
            color: white;
            font-weight: bold;
            cursor: pointer;
        }

        #mensagem {
            margin-top: 20px;
            font-size: 24px;
            color: white;
            display: none;
        }
    </style>
</head>

<body>
    <h1>Um recado pro amor da minha vida</h1>

    <p>Para ler escolha a opção "clique aqui"</p>

    <table>
        <tr>
            <td><a href="javascript:void(0);" onclick="mostrarMensagem()">Clique aqui</a></td>
        </tr>
    </table>

    <div id="mensagem">Eu te amo</div>

    <script>
        function mostrarMensagem() {
            document.getElementById("mensagem").style.display = "block";
        }
    </script>
</body>
</html>
