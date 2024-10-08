<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Special Friend</title>
<style>
body {
font-family: 'Arial', sans-serif;
margin: 0;
padding: 0;
background-color: #282c34;
color: #fff;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
height: 100vh;
overflow: hidden;
}
h1 {
font-size: 4em;
animation: zoomIn 2s ease-in-out;
}
p {
font-size: 1.5em;
margin: 20px 0;
animation: fadeInUp 3s ease-in-out;
}
@keyframes zoomIn {
from { transform: scale(0); }
to { transform: scale(1); }
}
@keyframes fadeInUp {
from { opacity: 0; transform: translateY(50px); }
to { opacity: 1; transform: translateY(0); }
}
.animation-bg {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: radial-gradient(circle, rgba(255,0,150,0.3) 0%, rgba(0,0,255,0.3) 100%);
animation: pulse 10s infinite;
z-index: -1;
}
@keyframes pulse {
0%, 100% { transform: scale(1); }
50% { transform: scale(1.1); }
}
.footer {
position: fixed;
bottom: 10px;
font-size: 1em;
color: #aaa;
text-align: center;
width: 100%;
}
</style>
</head>
<body>
<div class="animation-bg"></div>
<h1>Hey Best Friend!</h1>
<p>You make everything better with your presence</p>
<p>You're one in a million</p>
<p>Let's continue to make great memories together!</p>
<div class="footer">This webpage was made by Supernk</div>
</body>
</html>
