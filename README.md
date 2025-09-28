<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Crypto Donations</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #0d1117;
      color: #f0f6fc;
      text-align: center;
      padding: 20px;
      line-height: 1.6;
    }
    h1 {
      margin-bottom: 20px;
      font-size: 32px;
      color: #58a6ff;
    }
    p {
      margin-bottom: 30px;
      color: #8b949e;
      font-size: 16px;
    }
    .wallet {
      background: #161b22;
      padding: 20px;
      margin: 20px auto;
      border-radius: 12px;
      max-width: 600px;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
    }
    .wallet h2 {
      margin: 0 0 10px;
      font-size: 24px;
      color: #58a6ff;
    }
    .address {
      word-break: break-all;
      font-size: 14px;
      margin-bottom: 15px;
      color: #d0d7de;
    }
    .buttons {
      display: flex;
      justify-content: center;
      gap: 12px;
      margin-bottom: 15px;
      flex-wrap: wrap;
    }
    button {
      background: #238636;
      border: none;
      padding: 8px 14px;
      border-radius: 6px;
      cursor: pointer;
      font-weight: bold;
      color: white;
    }
    button:hover {
      background: #2ea043;
    }
    img {
      margin-top: 10px;
      width: 150px;
      height: 150px;
      border-radius: 8px;
      border: 1px solid #30363d;
    }
  </style>
</head>
<body>
  <h1>Support My Work with Crypto Donations</h1>
  <p>Your contribution helps me continue creating meaningful content and building my future from Gaza.  
  Thank you for your generosity ❤️</p>

  <!-- Bitcoin -->
  <div class="wallet">
    <h2>Bitcoin</h2>
    <div class="address">bc1qexamplebitcoinaddress1234567890</div>
    <div class="buttons">
      <button onclick="copyAddress('bc1qexamplebitcoinaddress1234567890')">📋 Copy Address</button>
      <a href="bitcoin:bc1qexamplebitcoinaddress1234567890" download>
        <button>💾 Save QR</button>
      </a>
    </div>
    <img src="bitcoin-qr.png" alt="Bitcoin QR Code">
  </div>

  <!-- Solana -->
  <div class="wallet">
    <h2>Solana</h2>
    <div class="address">J9f1UQT7CYeEpo1UvfiCRdHpZgWWHapAEVMwC6oo3kV</div>
    <div class="buttons">
      <button onclick="copyAddress('J9f1UQT7CYeEpo1UvfiCRdHpZgWWHapAEVMwC6oo3kV')">📋 Copy Address</button>
      <a href="solana:J9f1UQT7CYeEpo1UvfiCRdHpZgWWHapAEVMwC6oo3kV" download>
        <button>💾 Save QR</button>
      </a>
    </div>
    <img src="solana-qr.png" alt="Solana QR Code">
  </div>

  <!-- Ethereum -->
  <div class="wallet">
    <h2>Ethereum</h2>
    <div class="address">0xFe4E96D46303CF95efe53AEafC5766E5192c6c7</div>
    <div class="buttons">
      <button onclick="copyAddress('0xFe4E96D46303CF95efe53AEafC5766E5192c6c7')">📋 Copy Address</button>
      <a href="ethereum:0xFe4E96D46303CF95efe53AEafC5766E5192c6c7" download>
        <button>💾 Save QR</button>
      </a>
    </div>
    <img src="ethereum-qr.png" alt="Ethereum QR Code">
  </div>

  <!-- Base -->
  <div class="wallet">
    <h2>Base</h2>
    <div class="address">0xFe4E96D46303CF95efe53AEafC5766E5192c6c7</div>
    <div class="buttons">
      <button onclick="copyAddress('0xFe4E96D46303CF95efe53AEafC5766E5192c6c7')">📋 Copy Address</button>
      <a href="base:0xFe4E96D46303CF95efe53AEafC5766E5192c6c7" download>
        <button>💾 Save QR</button>
      </a>
    </div>
    <img src="base-qr.png" alt="Base QR Code">
  </div>

  <script>
    function copyAddress(address) {
      navigator.clipboard.writeText(address).then(() => {
        alert("Address copied: " + address);
      });
    }
  </script>
</body>
</html>
