# facti<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AUDIT 4.0 — Immutable Record</title>
  <style>
    body {
      font-family: 'Courier New', monospace;
      background: #0a0a0a;
      color: #00ff41;
      margin: 0;
      padding: 40px 20px;
      line-height: 1.6;
    }
    .stone {
      max-width: 900px;
      margin: 0 auto;
      border: 2px solid #00ff41;
      padding: 30px;
      background: #111;
      box-shadow: 0 0 20px rgba(0,255,65,0.2);
    }
    h1, h2 { 
      color: #fff; 
      border-bottom: 1px solid #333; 
      padding-bottom: 10px;
    }
    .stamp {
      background: #1a1a1a;
      padding: 15px;
      margin: 20px 0;
      border-left: 4px solid #00ff41;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
    }
    td, th {
      border: 1px solid #333;
      padding: 12px;
      text-align: left;
    }
    th { background: #1a1a1a; color: #fff; }
    .pass { color: #00ff41; }
    .blocked { color: #ff4141; }
    .pending { color: #ffaa41; }
    .sig {
      margin-top: 40px;
      font-size: 14px;
      color: #888;
    }
    code { 
      background: #222; 
      padding: 2px 6px; 
      border-radius: 3px;
      color: #00ff41;
    }
  </style>
</head>
<body>
  <div class="stone">
    <h1>AUDIT 4.0 — IMMUTABLE RECORD</h1>
    <div class="stamp">
      <strong>STRESS TEST:</strong> ACK