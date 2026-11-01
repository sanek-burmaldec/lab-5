<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="color-scheme" content="light">
  <title>Контактні дані викладачів</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #ffffff;
      color: #222222;
    }
    table {
      border-collapse: collapse;
      width: 80%;
    }
    th, td {
      color: #222222;
      border: 1px solid #555;
      padding: 8px 12px;
      text-align: left;
    }
    caption {
      font-size: 18px;
      font-weight: bold;
      margin-bottom: 8px;
    }
    thead tr,
    thead th {
      background-color: #9fc5e8;
      color: #000000;
    }
    thead tr.sub,
    thead tr.sub th {
      background-color: #cfe2f3;
      color: #000000;
    }
    .kaf-mat { background-color: #e6f7e6; }
    .kaf-inf { background-color: #e3f0ff; }
    .kaf-eng { background-color: #fff4d6; }
    .kaf-web { background-color: #f3e5f5; }
    .kaf-chem { background-color: #ffe5e5; }
    tfoot td {
      background-color: #d9d9d9;
      font-weight: bold;
    }
    a { color: #0b5394; }
  </style>
</head>
<body>
  <h2>Викладацький склад факультету</h2>
  <table>
    <caption>Контактні дані викладачів</caption>
    <thead>
      <tr>
        <th rowspan="2">№</th>
        <th colspan="3">Контактна інформація</th>
      </tr>
      <tr class="sub">
        <th>Ім’я</th>
        <th>Кафедра</th>
        <th>Email</th>
      </tr>
    </thead>
    <tbody>
      <tr class="kaf-mat">
        <td>1</td>
        <td>Гелетей Людмила Петрівна</td>
        <td>Математики</td>
        <td><a href="mailto:geletey@zlfk.com.ua">geletey@zlfk.com.ua</a></td>
      </tr>
      <tr class="kaf-inf">
        <td>2</td>
        <td>Філіп Михайло Михайлович</td>
        <td>Інформатики</td>
        <td><a href="mailto:filip@zlfk.com.ua">filip@zlfk.com.ua</a></td>
      </tr>
      <tr class="kaf-eng">
        <td>3</td>
        <td>Лар Володимир Іванович</td>
        <td>Англійської мови</td>
        <td><a href="mailto:lar@zlfk.com.ua">lar@zlfk.com.ua</a></td>
      </tr>
      <tr class="kaf-web">
        <td>4</td>
        <td>Бровдій Максим Іванович</td>
        <td>Веб-технологій та веб-дизайну</td>
        <td><a href="mailto:brovdiy@zlfk.com.ua">brovdiy@zlfk.com.ua</a></td>
      </tr>
      <tr class="kaf-chem">
        <td>5</td>
        <td>Король Ангеліна Віталіївна</td>
        <td>Хімії</td>
        <td><a href="mailto:korol@zlfk.com.ua">korol@zlfk.com.ua</a></td>
      </tr>
    </tbody>
    <tfoot>
      <tr>
        <td colspan="3">Усього викладачів</td>
        <td>5</td>
      </tr>
    </tfoot>
  </table>
</body>
</html>
 
