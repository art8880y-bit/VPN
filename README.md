# vpn-shop
สร้างเว็ปขายเน็ต
<!DOCTYPE html>

<html lang="th">
<head>
<meta charset="UTF-8">
<title>ThunderVPN Pro</title>
<style>
body {
  margin:0;
  font-family:sans-serif;
  background: linear-gradient(135deg,#0f2027,#2c5364);
  color:white;
  text-align:center;
}

.header {
padding:60px 20px;
}

.header h1 {
font-size:40px;
}

.card {
background:white;
color:black;
border-radius:20px;
padding:25px;
margin:20px;
display:inline-block;
width:260px;
box-shadow:0 10px 25px rgba(0,0,0,0.4);
transition:0.3s;
}

.card:hover {
transform:scale(1.05);
}

button {
background:#007bff;
color:white;
border:none;
padding:12px;
border-radius:10px;
cursor:pointer;
width:100%;
font-size:16px;
}

button:hover {
background:#0056b3;
}

.footer {
margin-top:40px;
opacity:0.7;
} </style>

</head>

<body>

<div class="header">
  <h1>⚡ ThunderVPN Pro</h1>
  <p>เร็ว แรง ปลอดภัย เล่นได้ทุกประเทศ</p>
</div>

<div class="card">
  <h2>🔥 30 วัน</h2>
  <p>💰 99 บาท</p>
  <button onclick="buy()">ซื้อเลย</button>
</div>

<div class="card">
  <h2>🚀 1 ปี</h2>
  <p>💰 899 บาท</p>
  <button onclick="buy()">ซื้อเลย</button>
</div>

<div class="footer">
  <p>ติดต่อ: LINE ID @vpnshop999</p>
</div>

<script>
function buy(){
  window.location.href = "https://line.me/ti/p/@vpnshop999";
}
</script>

</body>
</html>
