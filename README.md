<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>HADIX</title>

<style>
html,body{
margin:0;
width:100%;
height:100%;
background:transparent;
overflow:hidden;
display:flex;
justify-content:center;
align-items:center;
font-family:Arial,sans-serif;
}

.container{
display:flex;
flex-direction:column;
align-items:center;
animation:float 5s ease-in-out infinite;
}

/* هایلایت متن */
.logo{
font-size:96px;
font-weight:700;
letter-spacing:8px;
display:inline-block;
padding:5px 20px;
border-radius:12px;

background:rgba(255, 215, 0, 0.25);
color:#fff176;

text-shadow:
0 0 8px rgba(255,215,0,.55),
0 0 15px rgba(255,215,0,.35);

animation:wave 4s ease-in-out infinite;
backdrop-filter: blur(6px);
border:1px solid rgba(255,215,0,0.5);
}

.line{
width:100%;
height:4px;
margin-top:10px;
border-radius:20px;

background:linear-gradient(
90deg,
#ffd700,
#fff176,
#ffd700
);

box-shadow:
0 0 10px rgba(255,215,0,.7),
0 0 20px rgba(255,215,0,.5);

animation:shine 3s linear infinite;
background-size:200% 100%;
}

@keyframes float{
0%{transform:translateY(0px);}
50%{transform:translateY(-3px);}
100%{transform:translateY(0px);}
}

@keyframes wave{
0%{transform:translateX(-6px);}
50%{transform:translateX(6px);}
100%{transform:translateX(-6px);}
}

@keyframes shine{
0%{background-position:-200% 0;}
100%{background-position:200% 0;}
}
</style>
</head>

<body>

<div class="container">
<div class="logo">HADIX</div>
<div class="line"></div>
</div>

</body>
</html>
