# sourdough
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bre’s Bakes</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff8f0;
      color: #333;
      text-align: center;
      padding: 40px;
    }
    h1 {
      color: #6b4b3e;
      font-size: 2.2em;
      margin-bottom: 10px;
    }
    p {
      font-size: 1.1em;
      margin: 6px 0;
    }
    .prices {
      margin: 20px 0;
      font-weight: bold;
    }
    .qr {
      margin-top: 25px;
    }
    .order-button {
      display: inline-block;
      background-color: #c58940;
      color: white;
      padding: 12px 24px;
      border-radius: 8px;
      text-decoration: none;
      margin-top: 20px;
      font-weight: bold;
    }
    .order-button:hover {
      background-color: #a9742f;
    }
  </style>
</head>
<body>
  <h1>Bre’s Bakes</h1>
  <p>Fresh homemade sourdough loaves baked locally with love.</p>
  <div class="prices">
    <p>Regular Loaf – $10</p>
    <p>With Inclusions (nuts, olives, seeds, etc.) – $11</p>
  </div>
  <p>Payments accepted via Venmo, Cash App, or Zelle.</p>
  <p>Ready to order? Tap below or scan the QR code.</p>

  <a class="order-button" href="mailto:bresbakesorders@gmail.com?subject=New Sourdough Order&body=Hi Bre! I’d like to order:%0A%0AType of loaf:%0AQuantity:%0AName:%0AContact info:%0A%0APayment method (Venmo/Cash App/Zelle):" target="_blank">
    Place an Order
  </a>

  <div class="qr">
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=mailto:bresbakesorders@gmail.com" alt="Bre’s Bakes QR Code" />
  </div>

  <p style="margin-top: 25px; font-size: 0.9em; color: #555;">
    Scan the QR code to order by email or tap the button above.
  </p>
</body>
</html>
