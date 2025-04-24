<!DOCTYPE html>
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
      padding: 2rem 1rem;
      text-align: center;
      font-size: 1.75rem;
      font-weight: bold;
    }

    section {
      max-width: 960px;
      margin: 0 auto;
      padding: 2rem 1rem;
    }

    h2 {
      text-align: center;
      margin-bottom: 1rem;
    }

    .iframe-fixed {
      width: 100%;
      height: 800px; /* Fixed height to eliminate scrollbars */
      border: 1px solid #ccc;
      border-radius: 6px;
      box-shadow: 0 0 12px rgba(0,0,0,0.1);
    }

    @media screen and (max-width: 768px) {
      .iframe-fixed {
        height: 600px; /* Shorter on small devices */
      }
    }
  </style>
</head>
<body>

  <div class="header">Geopolitical Fragmentation Index Dashboard</div>

  <section>
    <h2>Trade Fragmentation</h2>
    <iframe
      class="iframe-fixed"
      src="https://lookerstudio.google.com/embed/reporting/8c92f986-d3b2-4bb7-a839-267912190484/page/1n0HF"
      allowfullscreen>
    </iframe>
  </section>

  <section>
    <h2>Financial Fragmentation</h2>
    <iframe
      class="iframe-fixed"
      src="https://lookerstudio.google.com/embed/reporting/8c92f986-d3b2-4bb7-a839-267912190484/page/p_u6dg9favrd"
      allowfullscreen>
    </iframe>
  </section>

  <!-- Add more sections below with other embed links if needed -->

</body>
</html>


