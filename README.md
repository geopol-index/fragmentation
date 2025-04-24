<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Geopolitical Fragmentation Index Dashboard</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    html, body {
      margin: 0;
      padding: 0;
      background-color: white;
      color: black;
      font-family: sans-serif;
    }

    .header {
      padding: 1.5rem 1rem;
      text-align: center;
      font-size: 1.75rem;
      font-weight: bold;
    }

    section {
      max-width: 960px;
      margin: 0 auto;
      padding: 1.5rem 1rem;
    }

    h2 {
      text-align: center;
      margin-bottom: 1rem;
    }

    .iframe-container {
      position: relative;
      width: 100%;
      padding-bottom: 56.25%; /* 16:9 aspect ratio */
      height: 0;
      overflow: hidden;
      border: 1px solid #ccc;
      border-radius: 6px;
      box-shadow: 0 0 12px rgba(0,0,0,0.1);
    }

    .iframe-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }
  </style>
</head>
<body>

  <div class="header">Geopolitical Fragmentation Index Dashboard</div>

  <section>
    <h2>Trade Fragmentation</h2>
    <div class="iframe-container">
      <iframe src="https://lookerstudio.google.com/u/2/reporting/8c92f986-d3b2-4bb7-a839-267912190484/page/1n0HF" allowfullscreen></iframe>
    </div>
  </section>

  <section>
    <h2>Financial Fragmentation</h2>
    <div class="iframe-container">
      <iframe src="https://lookerstudio.google.com/u/2/reporting/8c92f986-d3b2-4bb7-a839-267912190484/page/p_u6dg9favrd" allowfullscreen></iframe>
    </div>
  </section>

  <!-- OPTIONAL: Add more charts below -->
  <!--
  <section>
    <h2>Mobility Fragmentation</h2>
    <div class="iframe-container">
      <iframe src="..." allowfullscreen></iframe>
    </div>
  </section>

  <section>
    <h2>Political Fragmentation</h2>
    <div class="iframe-container">
      <iframe src="..." allowfullscreen></iframe>
    </div>
  </section>
  -->

</body>
</html>
