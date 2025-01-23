<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Notification Box</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f9f9f9;
    }
    .notification-box {
      display: flex;
      align-items: center;
      border: 2px solid #f44336;
      border-radius: 8px;
      padding: 12px 16px;
      background-color: #fff;
      color: #333;
      max-width: 400px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .notification-box .icon {
      color: #f44336;
      font-size: 20px;
      margin-right: 12px;
    }
    .notification-box .content {
      font-size: 16px;
    }
    .notification-box .content .title {
      font-weight: bold;
      margin-bottom: 4px;
    }
  </style>
</head>
<body>
  <div class="notification-box">
    <div class="icon">⚠️</div>
    <div class="content">
      <div class="title">CAMT : CREATIVITY AND LEARNING ROOM</div>
      <div>We already have this book!</div>
    </div>
  </div>
</body>
</html>
