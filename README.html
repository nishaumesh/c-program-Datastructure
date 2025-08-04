<!DOCTYPE html>
<html>
<head>
  <title>Soil Moisture Monitor</title>
  <script src="https://www.gstatic.com/firebasejs/8.10.1/firebase-app.js"></script>
  <script src="https://www.gstatic.com/firebasejs/8.10.1/firebase-database.js"></script>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #f0f4f8;
      padding-top: 50px;
    }
    .card {
      background: white;
      display: inline-block;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
    }
    h1 {
      color: #333;
    }
    .status {
      font-size: 24px;
      margin: 10px 0;
    }
    .on {
      color: green;
    }
    .off {
      color: red;
    }
  </style>
</head>
<body>

  <div class="card">
    <h1>Soil Moisture Dashboard</h1>
    <p class="status">Moisture: <span id="moisture">--</span></p>
    <p class="status">Pump Status: <span id="pumpStatus" class="off">--</span></p>
  </div>

  <script>
    // Your web app Firebase configuration
    const firebaseConfig = {
      apiKey: "AIzaSyCPjxX1GspwotFYp5fKwrqHkzOLFpg9ZUg",
      authDomain: "my-iot-37673.firebaseapp.com",
      databaseURL: "https://my-iot-37673-default-rtdb.firebaseio.com",
      projectId: "my-iot-37673",
      storageBucket: "my-iot-37673.appspot.com",
      messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
      appId: "YOUR_APP_ID"
    };

    // Initialize Firebase
    firebase.initializeApp(firebaseConfig);
    const db = firebase.database();

    // Reference to your data
    const dataRef = db.ref('soilmoisture');

    dataRef.on('value', (snapshot) => {
      const data = snapshot.val();
      document.getElementById('moisture').textContent = data.moisture;
      const pumpEl = document.getElementById('pumpStatus');
      pumpEl.textContent = data.pump;
      pumpEl.className = 'status ' + (data.pump === 'ON' ? 'on' : 'off');
    }, (error) => {
      console.error("Firebase read failed: ", error);
    });
  </script>

</body>
</html>
