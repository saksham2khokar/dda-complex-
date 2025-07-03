# dda-complex-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Visitor Receipt</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .receipt {
      width: 600px;
      margin: 50px auto;
      padding: 30px;
      border: 2px solid #000;
      box-shadow: 5px 5px 10px rgba(0,0,0,0.2);
    }
    h1 {
      text-align: center;
      font-size: 28px;
    }
    .row {
      display: flex;
      margin-bottom: 10px;
    }
    .label {
      width: 180px;
      font-weight: bold;
    }
    .value {
      flex: 1;
    }
    .qr {
      text-align: center;
      margin: 20px 0;
    }
    .qr img {
      height: 100px;
      width: 100px;
      border-top: 5px solid red;
      padding-top: 5px;
    }
    .disclaimer {
      color: red;
      font-size: 14px;
      text-align: center;
      margin-top: 30px;
      line-height: 1.5;
    }
  </style>
</head>
<body>
  <div class="receipt">
    <h1>Visitor Receipt</h1>
    <div class="row"><div class="label">Complex Name:</div><div class="value">Dwarka Sports Complex Sector 17</div></div>
    <div class="row"><div class="label">Receipt Date:</div><div class="value">6 Jul 2025</div></div>
    <div class="row"><div class="label">Receipt Type:</div><div class="value">Casual</div></div>
    <div class="row"><div class="label">Receipt No:</div><div class="value">DSC17_V22977741896</div></div>
    <div class="row"><div class="label">Membership No:</div><div class="value">NA</div></div>
    <div class="row"><div class="label">Player Name:</div><div class="value">SAKSHAM</div></div>
    <div class="row"><div class="label">Facility:</div><div class="value">Track</div></div>
    <div class="row"><div class="label">Booking Fee:</div><div class="value">100.00</div></div>
    <div class="row"><div class="label">Payment Method:</div><div class="value">QR Code</div></div>
    <div class="row"><div class="label">User/Time:</div><div class="value">recp3/6:01 AM</div></div>

    <div class="qr">
      <img src="https://api.qrserver.com/v1/create-qr-code/?size=100x100&data=DSC17_V22977741896%7CSAKSHAM%7CTrack%7C6%20Jul%202025%7CCasual" alt="QR Code">
    </div>

    <div class="disclaimer">
      Once the receipt is issued, money will not be refunded.<br>
      The management accepts no responsibility for any accident or mishap.<br>
      Any injuries/infections/loss of life while availing the facilities will be<br>
      at the member/user's risk. No compensation/claim shall be entertained<br>
      in case of any mishap or loss of life.
    </div>
  </div>
</body>
</html>
