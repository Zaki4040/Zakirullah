<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Zakirullah | Academic Homepage</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Georgia, "Times New Roman", serif;
      background: #f3f3f3;
      color: #333;
    }
    
    .page {
      max-width: 900px; /* Narrower width is often more readable for academic sites */
      margin: 20px auto;
      padding: 40px;
      background: #ffffff;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }

    header {
      display: grid;
      grid-template-columns: 1fr 180px;
      gap: 30px;
      align-items: center;
    }

    h1 {
      font-size: 36px;
      margin: 0 0 10px 0;
      font-weight: normal;
      color: #000;
    }

    .contact {
      font-size: 15px;
      color: #444;
      line-height: 1.6;
    }

    .photo img {
      width: 180px;
      height: auto;
      border-radius: 4px;
      border: 1px solid #ddd;
    }

    section {
      margin-top: 40px;
    }

    section h2 {
      font-size: 24px;
      font-weight: normal;
      border-bottom: 1px solid #ddd;
      padding-bottom: 8px;
      margin-bottom: 15px;
      color: #222;
    }

    p, li {
      line-height: 1.6;
      font-size: 16px;
      margin-bottom: 12px;
    }

    ul {
      padding-left: 20px;
    }

    a {
      color: #1a4fff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .pdf-link {
      font-size: 12px;
      color: #666;
      margin-left: 10px;
      border: 1px solid #ccc;
      padding: 2px 6px;
      border-radius: 3px;
      text-transform: uppercase;
    }

    /* Mobile View Optimization */
    @media (max-width: 600px) {
      header {
        grid-template-columns: 1fr;
        text-align: center;
      }
      .photo {
        grid-row: 1; /* Move photo to top on mobile */
      }
      .page {
        padding: 20px;
        margin: 0;
      }
    }
  </style>
</head>
<body>
  <div class="page">
    <header>
      <div>
        <h1>Zakirullah</h1>
        <div class="contact">
          Department of Mathematics and Statistics<br />
          University of Electronic Science and Technology of China<br />
          <strong>Phone:</strong> +(86) 18382130061<br />
          <strong>Email:</strong> <a href="mailto:zakirullahbzt@gmail.com">zakirullahbzt@gmail.com</a>
        </div>
      </div>
      <div class="photo">
        <img src="profile.jpg" alt="Portrait of Zakirullah" />
      </div>
    </header>

    <section>
      <h2>Research</h2>
      <p>
        I am a mathematical ecologist with interests in <strong>adaptive dynamics</strong>,
        speciation, evolutionary epidemiology, spatial ecology, and life histories.
      </p>
      <p>
        <strong>ORCID:</strong> <a href="https://orcid.org/0000-0001-8916-6717" target="_blank">0000-0001-8916-6717</a>
      </p>
    </section>

    <section>
      <h2>Selected Publications</h2>
      <ul>
        <li>
          Zakirullah. Measles disease spread and control via vaccination and treatment: A mathematical framework. 
          <em>Chaos, Solitons & Fractals</em>, Vol 203, 2026. 
          <a href="https://doi.org/10.1016/j.chaos.2025.117703">DOI</a>
          <a href="m.pdf" class="pdf-link">PDF</a>
        </li>
        <li>
          Zakirullah, Lu, C., Li, L. et al. Mathematical insights into chaos in fractional-order fishery model. 
          <em>Model. Earth Syst. Environ.</em> 11, 201 (2025). 
          <a href="https://doi.org/10.1007/s40808-025-02375-2">DOI</a>
          <a href="k.pdf" class="pdf-link">PDF</a>
        </li>
        <li>
          Zakirullah. Using treatment and vaccination strategies to investigate transmission dynamics of influenza mathematical model. 
          <em>Ain Shams Engineering Journal</em>, 16(9). 
          <a href="https://doi.org/10.1016/j.asej.2025.103519">DOI</a>
        </li>
      </ul>
    </section>
  </div>
</body>
</html>
