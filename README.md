<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    html, body {
      margin: 0;
      padding: 0;
      background-color: #0d1117; /* GitHub dark background */
      color: white;
      font-family: sans-serif;
    }

    .header {
      padding: 1.5rem 1rem;
      text-align: center;
      font-size: 1.5rem;
    }

    .iframe-container {
      position: relative;
      width: 100%;
      padding-bottom: 56.25%; /* 16:9 ratio */
      height: 0;
      overflow: hidden;
    }

    .iframe-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }

    .mobile-link {
      text-align: center;
      padding: 1rem;
      display: none;
    }

    @media screen and (max-width: 600px) {
      .iframe-container {
        display: none;
      }

      .mobile-link {
        display: block;
      }
    }
  </style>
</head>
<body>
  <div class="header">Geopolitical Fragmentation Dashboard</div>

  <div class="iframe-container">
    <iframe 
      src="https://lookerstudio.google.com/embed/reporting/8c92f986-d3b2-4bb7-a839-267912190484/page/1n0HF" 
      allowfullscreen>
    </iframe>
  </div>

  <div class="mobile-link">
    📱 Having trouble on mobile?  
    <a href="https://lookerstudio.google.com/reporting/8c92f986-d3b2-4bb7-a839-267912190484/page/1n0HF" style="color:#58a6ff;" target="_blank">
      Open dashboard in full screen
    </a>
  </div>
</body>
</html>


