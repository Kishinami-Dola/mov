<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://code.jquery.com/jquery-3.7.1.js" integrity="sha256-eKhayi8LEQwp4NKxN+CfCh+3qOVUtJn3QNZ0TciWLP4=" crossorigin="anonymous"></script>

    <style>
        .caixa{
            
            border: 1px solid #000;
            width: 200px;
            height: 200px;
            background-color: blueviolet;
            position: absolute;
            left: 0px;
            top: 50px;
            

        }
    </style>

</head>
<body>
    <div id="caixa" class="caixa">
        <h1>Teste de movimento</h1>
        <p>Olha so thiago</p>
    </div>

    <button id="btn_1">Aumentar</button>
    <button id="btn_2">Diminuir</button>
    <button id="btn_3">Direita</button>
    <button id="btn_4">Esquerda</button>

    <script>
        $('#btn_1').click(
            function(){
                $('#caixa').animate({width:"500px",height:"500px"})
            }
        )
        $('#btn_2').click(
            function(){
                $('#caixa').animate({width:"200px",height:"200px"})
            }
        )
        $('#btn_3').click(
            function(){
                $('#caixa').animate({left:"500px"},{duration:1000,complete:()=>{alert('pronto')}})
            }
        )
        $('#btn_4').click(
            function(){
                $('#caixa').animate({left:"0px"},{duration:1000,complete:()=>{alert('pronto')}})
            }
        )
    </script>

</body>
</html>
