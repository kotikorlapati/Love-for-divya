# Love-for-divya
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Love for Divya Bharathi</title>
<style>
body{
  background:linear-gradient(to right,#ff758c,#ff7eb3);
  font-family:Segoe UI,sans-serif;
  display:flex;
  justify-content:center;
  align-items:center;
  height:100vh;
  margin:0;
}
.card{
  background:white;
  padding:35px;
  border-radius:20px;
  text-align:center;
  width:360px;
  box-shadow:0 10px 25px rgba(0,0,0,0.2);
}
h1{color:#ff3366;}
.message{font-size:18px;margin:20px 0;}
.emoji{font-size:32px;}
button{
  background:#ff3366;
  color:white;
  border:none;
  padding:12px 20px;
  border-radius:25px;
  font-size:16px;
  cursor:pointer;
}
</style>
</head>
<body>

<div class="card">
  <h1>Happy Valentine’s Day 💖</h1>
  <h2>Divya Bharathi 😘</h2>

  <p class="message" id="msg">
    You are my forever love ❤️
  </p>

  <div class="emoji">💋😘❤️</div>

  <button onclick="changeMsg()">Click for a Kiss 😘</button>
</div>

<script>
const msgs=[
 "Divya Bharathi, you are my forever love 😘",
 "Every heartbeat belongs to you ❤️",
 "Life with you is my favorite love story 💖",
 "One kiss for you… and many more 💋",
 "I choose you, today and always 💕"
];
function changeMsg(){
 document.getElementById("msg").innerText=
 msgs[Math.floor(Math.random()*msgs.length)];
}
</script>

</body>
</html>
