<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fada_Tope</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body{
      margin:0;
      font-family:Arial,sans-serif;
      background:linear-gradient(135deg,#2b6cb0,#b0bec5);
      color:#fff;
      display:flex;
      justify-content:center;
      align-items:center;
      height:100vh;
    }
    .card{
      background:rgba(255,255,255,.12);
      backdrop-filter:blur(10px);
      padding:30px;
      border-radius:20px;
      text-align:center;
      width:320px;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
      animation: slideIn 0.6s ease-out;
    }
    
    @keyframes slideIn {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    h1{
      margin-bottom:20px;
      font-size: 28px;
      letter-spacing: 1px;
    }
    
    a{
      display:block;
      margin:12px 0;
      padding:14px;
      text-decoration:none;
      color:#fff;
      background:#1565c0;
      border-radius:12px;
      font-weight:bold;
      transition: all 0.3s ease;
      border: 2px solid transparent;
    }
    
    a:hover{
      background:#0d47a1;
      transform: translateY(-2px);
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    }
    
    a:active {
      transform: translateY(0);
    }
    
    .whatsapp { background: #25d366; }
    .whatsapp:hover { background: #20ba5a; }
    
    .telegram { background: #0088cc; }
    .telegram:hover { background: #0077b5; }
    
    .snapchat { background: #fffc00; color: #000; }
    .snapchat:hover { background: #e6e600; }
    
    .x { background: #000; }
    .x:hover { background: #333; }
  </style>
</head>
<body>
  <div class="card">
    <h1>Fada_Tope</h1>

    <a href="https://wa.me/233534930457" class="whatsapp">💬 WhatsApp</a>

    <a href="https://t.me/Temishye" class="telegram">✈️ Telegram</a>

    <a href="https://www.snapchat.com/add/fadatope" class="snapchat">👻 Snapchat</a>
    
    <a href="https://twitter.com/JerryDc115152" class="x">𝕏 Follow on X</a>
  </div>
</body>
</html>
