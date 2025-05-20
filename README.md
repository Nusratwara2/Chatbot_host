"MyFlight is your smart virtual assistant for flight bookings and cancellations.
It helps you search and book flights quickly by collecting your travel details like departure city, destination, travel dates, passenger count, and class preference etc.. Whether you're planning a one-way or round-trip journey, MyFlight makes the process fast, simple, and conversational.


<!DOCTYPE html>
<html>
<head>
  <title>Split Background Page</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(to right, yellow 50%, black 50%);
      display: flex;
      justify-content: center;
      align-items: center;
    }

    img {
      width: 800px;
      height: auto;
      border: 5px solid white; /* Optional: adds visibility if part overlaps black */
    }
  </style>
</head>
<body>
  <img src="airplane.jpeg" alt="Airplane" width="800" height="600">
</body>
</html>



<script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>
<df-messenger
  chat-icon="https:&#x2F;&#x2F;fastly.picsum.photos&#x2F;id&#x2F;888&#x2F;5000&#x2F;2813.jpg?hmac=3XtGF_LkOPI7BEE5ktdpxgNZZKNOPqIiQZqoOL1b2y8"
  intent="WELCOME"
  chat-title="MyFlight"
  agent-id="8aafdb1c-ee58-4f28-add1-b0a5b0861f7f"
  language-code="en"
></df-messenger>
