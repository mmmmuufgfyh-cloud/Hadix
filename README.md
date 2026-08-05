<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Double Yellow Lines</title>

<style>
html,body{
    margin:0;
    width:100%;
    height:100%;
    display:flex;
    justify-content:center;
    align-items:center;
    background:transparent;
}

.container{
    width:320px;
    display:flex;
    flex-direction:column;
    align-items:center;
    gap:80px; /* فاصله بین دو خط */
}

.line{
    width:260px;
    height:4px;
    border-radius:50px;

    background:linear-gradient(
        90deg,
        #ffd700,
        #fff8c4,
        #ffd700
    );

    box-shadow:
        0 0 4px rgba(255,255,255,.20),
        0 0 8px rgba(255,215,0,.35),
        0 0 14px rgba(255,215,0,.20);
}
</style>
</head>

<body>

<div class="container">
    <div class="line"></div>
    <div class="line"></div>
</div>

</body>
</html>
