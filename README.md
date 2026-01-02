<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>HADIX</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
html, body {
  margin: 0;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle at top, #0c1022, #000000);
  overflow: hidden;
  font-family: Arial, Helvetica, sans-serif;
}

/* مرکز صفحه */
.container {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* متن HADIX */
.logo {
  font-size: 96px;
  font-weight: 700;
  letter-spacing: 12px;
  color: #ffffff;
  text-shadow:
    0 0 10px rgba(120, 120, 255, 0.6),
    0 0 30px rgba(80, 80, 255, 0.4);
  animation: glow 3s ease-in-out infinite;
}

/* انیمیشن نرم مثل hadix */
@keyframes glow {
  0% {
    opacity: 0.4;
    transform: scale(0.98);
  }
  50% {
    opacity: 1;
    transform: scale(1.02);
  }
  100% {
    opacity: 0.4;
    transform: scale(0.98);
  }
}

/* افکت ذرات ساده */
.star {
  position: absolute;
  width: 2px;
  height: 2px;
  background: white;
  opacity: 0.6;
  animation: float 6s linear infinite;
}

@keyframes float {
  from {
    transform: translateY(100vh);
  }
  to {
    transform: translateY(-10px);
  }
}
</style>
</head>

<body>

<div class="container">
  <div class="logo">HADIX</div>
</div>

<script>
for (let i = 0; i < 30; i++) {
  const star = document.createElement("div");
  star.className = "star";
  star.style.left = Math.random() * 100 + "vw";
  star.style.animationDuration = (3 + Math.random() * 5) + "s";
  document.body.appendChild(star);
}
</script>

</body>
</html>
