<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>HADIX</title>

<style>
html,body{
margin:0;
height:100%;
display:flex;
justify-content:center;
align-items:center;
background:#0b0b0b;
font-family:Arial,sans-serif;
}

.container{
display:flex;
flex-direction:column;
align-items:center;
}

/* متن HADIX */
.logo{
font-size:90px;
font-weight:700;
letter-spacing:6px;
color:#ffd700;

/* نور کم و ملایم */
text-shadow:
0 0 6px rgba(255,215,0,0.4),
0 0 12px rgba(255,215,0,0.2);

margin-bottom:12px;
}

/* خط زیر */
.line{
width:260px;
height:4px;
background:#ffd700;
border-radius:20px;

/* نور ملایم */
box-shadow:
0 0 6px rgba(255,215,0,0.4),
0 0 10px rgba(255,215,0,0.2);
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
