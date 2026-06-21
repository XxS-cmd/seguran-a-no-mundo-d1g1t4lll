<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Segurança no Mundo Digital</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:"Segoe UI", sans-serif;
}

body{
    background: linear-gradient(135deg,#070012,#140024,#240046,#0b0018);
    color:white;
    min-height:100vh;
    overflow-x:hidden;
    position:relative;
}

/* estrelas */
body::before{
    content:"";
    position:fixed;
    inset:0;
    background:
    radial-gradient(circle at 10% 20%, rgba(255,255,255,0.7) 1px, transparent 2px),
    radial-gradient(circle at 30% 80%, rgba(255,255,255,0.5) 1px, transparent 2px),
    radial-gradient(circle at 70% 30%, rgba(255,255,255,0.6) 1px, transparent 2px),
    radial-gradient(circle at 85% 70%, rgba(255,255,255,0.4) 1px, transparent 2px),
    radial-gradient(circle at 50% 50%, rgba(255,255,255,0.3) 1px, transparent 2px);
    background-size:300px 300px;
    opacity:0.6;
    z-index:-2;
}

/* nebulosa */
body::after{
    content:"";
    position:fixed;
    inset:0;
    background:
    radial-gradient(circle at 20% 30%, rgba(160,0,255,0.25), transparent 40%),
    radial-gradient(circle at 80% 60%, rgba(90,0,200,0.25), transparent 45%),
    radial-gradient(circle at 50% 80%, rgba(200,0,255,0.15), transparent 50%);
    filter:blur(90px);
    z-index:-1;
}

header{
    text-align:center;
    padding:120px 20px 80px;
}

header h1{
    font-size:4.5em;
    background:linear-gradient(90deg,#ffffff,#caa6ff,#ffffff);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

header p{
    max-width:850px;
    margin:auto;
    font-size:1.2em;
    line-height:1.8;
    color:#e6dbff;
}

.container{
    width:90%;
    max-width:1000px;
    margin:auto;
}

.card{
    background:rgba(255,255,255,0.07);
    border:1px solid rgba(255,255,255,0.12);
    backdrop-filter:blur(15px);
    border-radius:28px;
    padding:40px;
    margin-bottom:30px;
    text-align:center;
    transition:0.4s;
}

.card:hover{
    transform:translateY(-8px);
    box-shadow:0 0 35px rgba(170,0,255,0.35);
}

h2{
    font-size:2em;
    margin-bottom:20px;
    color:#e7c9ff;
}

p{
    font-size:1.1em;
    line-height:1.9;
}

footer{
    text-align:center;
    padding:70px 20px;
    color:#cdb6ff;
    font-size:0.95em;
}

.autor{
    margin-top:30px;
    font-size:0.75em;
    color:rgba(255,255,255,0.08);
    letter-spacing:2px;
    user-select:none;
}
</style>
</head>

<body>

<header>
    <h1>Segurança no Mundo Digital</h1>
    <p>
        Em um mundo cada vez mais conectado, aprender a analisar e interpretar
        informações é essencial para usar a internet de forma consciente e responsável.
    </p>
</header>

<div class="container">

    <div class="card">
        <h2>O que é Educação Midiática</h2>
        <p>
            É a capacidade de compreender, analisar e interpretar conteúdos
            presentes nos meios de comunicação, desenvolvendo pensamento crítico
            sobre o que consumimos diariamente.
        </p>
    </div>

    <div class="card">
        <h2>Por que ela é importante</h2>
        <p>
            Ajuda a combater desinformação, desenvolver pensamento crítico,
            e promove o uso responsável da internet e redes sociais.
        </p>
    </div>

    <div class="card">
        <h2>Como praticar</h2>
        <p>
            Verifique fontes, compare informações, evite compartilhar conteúdos
            duvidosos e use a internet com responsabilidade.
        </p>
    </div>

    <div class="card">
        <h2>Cidadania Digital</h2>
        <p>
            Ser um cidadão digital significa agir com respeito, consciência e
            responsabilidade no ambiente virtual.
        </p>
    </div>

</div>

<footer>
    Desenvolvido para conscientização sobre o uso responsável das mídias digitais.

    <div class="autor">
        Feito por Gabriel Soares Santos
    </div>
</footer>

</body>
</html>
