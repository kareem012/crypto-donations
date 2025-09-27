<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Support My Work - Crypto Donations</title>
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
      margin-bottom: 10px;
      font-size: 28px;
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
      max-width: 650px;
      box-shadow: 0 0 10px rgba(0,0,0,0.6);
    }
    .wallet h2 {
      margin: 0 0 10px;
      font-size: 20px;
      color: #58a6ff;
    }
    .address {
      word-break: break-all;
      font-size: 14px;
      margin-bottom: 15px;
      color: #00ffcc;
    }
    .buttons {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin-bottom: 10px;
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
  <p>Your contribution helps me continue creating meaningful content and building my future from Gaza. Thank you for your generosity ❤️</p>

  <div class="wallet">
    <h2>Solana</h2>
    <div class="address">J9f1UQt7CtYeEPo1UvfiCRdHpZgWWHapAEVMwC6oo3kV</div>
    <div class="buttons">
      <button onclick="copyAddress('J9f1UQt7CtYeEPo1UvfiCRdHpZgWWHapAEVMwC6oo3kV')">📋 Copy Address</button>
      <button onclick="downloadQR('solana-qr')">💾 Save QR</button>
    </div>
    <div><img id="solana-qr" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=J9f1UQt7CtYeEPo1UvfiCRdHpZgWWHapAEVMwC6oo3kV" alt="Solana QR"></div>
  </div>

  <div class="wallet">
    <h2>Ethereum</h2>
    <div class="address">0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7</div>
    <div class="buttons">
      <button onclick="copyAddress('0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7')">📋 Copy Address</button>
      <button onclick="downloadQR('eth-qr')">💾 Save QR</button>
    </div>
    <div><img id="eth-qr" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7" alt="Ethereum QR"></div>
  </div>

  <div class="wallet">
    <h2>Base</h2>
    <div class="address">0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7</div>
    <div class="buttons">
      <button onclick="copyAddress('0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7')">📋 Copy Address</button>
      <button onclick="downloadQR('base-qr')">💾 Save QR</button>
    </div>
    <div><img id="base-qr" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7" alt="Base QR"></div>
  </div>

  <div class="wallet">
    <h2>Sui</h2>
    <div class="address">0x9d15eaf9c2efb4361d3f8d4119b272f309aba9fdd0f5db093827f9b9d7a5df10</div>
    <div class="buttons">
      <button onclick="copyAddress('0x9d15eaf9c2efb4361d3f8d4119b272f309aba9fdd0f5db093827f9b9d7a5df10')">📋 Copy Address</button>
      <button onclick="downloadQR('sui-qr')">💾 Save QR</button>
    </div>
    <div><img id="sui-qr" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=0x9d15eaf9c2efb4361d3f8d4119b272f309aba9fdd0f5db093827f9b9d7a5df10" alt="Sui QR"></div>
  </div>

  <div class="wallet">
    <h2>Polygon</h2>
    <div class="address">0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7</div>
    <div class="buttons">
      <button onclick="copyAddress('0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7')">📋 Copy Address</button>
      <button onclick="downloadQR('polygon-qr')">💾 Save QR</button>
    </div>
    <div><img id="polygon-qr" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7" alt="Polygon QR"></div>
  </div>

  <div class="wallet">
    <h2>Bitcoin</h2>
    <div class="address">bc1qmtx8f50v3xmvggmjc92jagcm6l3t5725e8ljn2</div>
    <div class="buttons">
      <button onclick="copyAddress('bc1qmtx8f50v3xmvggmjc92jagcm6l3t5725e8ljn2')">📋 Copy Address</button>
      <button onclick="downloadQR('btc-qr')">💾 Save QR</button>
    </div>
    <div><img id="btc-qr" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=bc1qmtx8f50v3xmvggmjc92jagcm6l3t5725e8ljn2" alt="Bitcoin QR"></div>
  </div>

  <script>
    function copyAddress(address) {
      navigator.clipboard.writeText(address).then(() => {
        alert("Address copied to clipboard: " + address);
      });
    }

    function downloadQR(id) {
      const img = document.getElementById(id);
      const link = document.createElement('a');
      link.href = img.src;
      link.download = id + '.png';
      link.click();
    }
  </script>
</body>
</html>

    <button onclick="copyAddress('0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7')">📋 نسخ العنوان</button>
    <div><img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=0xeFe4E96D46303CF95efe53AEafC5766E5192c6c7" alt="Polygon QR"></div>
  </div>  <div class="wallet">
    <h2>Bitcoin</h2>
    <div class="address">bc1qmtx8f50v3xmvggmjc92jagcm6l3t5725e8ljn2</div>
    <button onclick="copyAddress('bc1qmtx8f50v3xmvggmjc92jagcm6l3t5725e8ljn2')">📋 نسخ العنوان</button>
    <div><img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=bc1qmtx8f50v3xmvggmjc92jagcm6l3t5725e8ljn2" alt="Bitcoin QR"></div>
  </div>  <script>
    function copyAddress(address) {
      navigator.clipboard.writeText(address).then(() => {
        alert("تم نسخ العنوان: " + address);
      });
    }
  </script></body>
</html>
