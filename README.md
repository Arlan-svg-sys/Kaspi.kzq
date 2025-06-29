<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Удостоверение</title>
  <link rel="icon" href="https://kaspi.kz/img/favicon.ico" />
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #ffffff;
      margin: 0;
      padding: 0;
    }
    .header {
      background-color: red;
      color: white;
      padding: 16px;
      text-align: center;
      font-size: 20px;
    }
    .tabs {
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }
    .tab {
      padding: 10px 20px;
      border-bottom: 3px solid red;
      color: red;
      font-weight: bold;
    }
    .content {
      max-width: 400px;
      margin: 20px auto;
      border: 1px solid #eee;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .photo {
      width: 100%;
      height: 220px;
      background: #eee url('https://via.placeholder.com/300x200?text=Фото') center/cover no-repeat;
    }
    .info {
      padding: 16px;
    }
    .info p {
      margin: 8px 0;
      border-bottom: 1px solid #ddd;
      padding-bottom: 4px;
    }
    .buttons {
      text-align: center;
      margin: 20px 0;
    }
    .buttons button {
      background-color: #007bff;
      color: white;
      border: none;
      padding: 12px 20px;
      margin: 5px;
      border-radius: 6px;
      font-size: 16px;
    }
  </style>
</head>
<body>

  <div class="header">Удостоверение личности</div>

  <div class="tabs">
    <div class="tab">Документ</div>
    <div class="tab" style="border-bottom: 3px solid transparent;">Реквизиты</div>
  </div>

  <div class="content">
    <div class="photo"></div>
    <div class="info">
      <p>ФИО: Иванов Иван</p>
      <p>ИИН: ************</p>
      <p>Дата рождения: **.**.****</p>
      <p>Номер документа: *********</p>
      <p>Срок действия: **.**.****</p>
    </div>
  </div>

  <div class="buttons">
    <button>Предъявить документ</button>
    <button>Отправить документ</button>
  </div>

</body>
</html>
