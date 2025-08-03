<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Der MatheMentor – Nachhilfe buchen</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: 2rem auto;
      padding: 1rem;
      background: #f5f5f5;
      color: #333;
    }
    h1, h2 {
      text-align: center;
      color: #2a6ebb;
    }
    iframe {
      width: 100%;
      height: 700px;
      border: none;
      border-radius: 8px;
      margin-top: 1.5rem;
    }
    .contact {
      margin-top: 3rem;
      padding: 1rem;
      background: #e9f0fb;
      border-radius: 5px;
      font-size: 1rem;
      line-height: 1.5;
    }
    .contact a {
      color: #2a6ebb;
      text-decoration: none;
    }
    .contact a:hover {
      text-decoration: underline;
    }
    .payment-note {
      text-align: center;
      margin-top: 1rem;
      font-style: italic;
    }
    .description {
      text-align: center;
      margin-bottom: 1rem;
    }
    .preise {
      text-align: center;
      font-weight: bold;
      margin-bottom: 2rem;
      font-size: 1.1rem;
    }
    img {
      max-width: 200px;
      display: block;
      margin: 0 auto 1rem;
      position: relative; /* damit der Text absolut über dem Bild gefunden wird */
      z-index: 1;
    }

    /* NEU: Text direkt über dem Bild verstecken */
    img::before {
      content: "";
      display: block;
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      z-index: 2;
    }

    /* Verstecke alle Elemente, die über dem Bild liegen und Text enthalten */
    /* Alternativ kannst du das Bild in ein Wrapper-Div packen, der overflow:hidden hat */
  </style>
</head>
<body>

  <img src="https://i.imgur.com/8FYYMtm.png" alt="Logo Der MatheMentor" />

  <h1>Der MatheMentor</h1>

  <p class="description">
    Individuelle Mathe-Nachhilfe im Präsenzunterricht – von Klasse 5 bis zur 10. Klasse.<br />
    Buche jetzt ganz einfach deinen 2-Stunden-Termin!
  </p>

  <p class="preise">
    Preis: 2 Stunden – 30 €
  </p>

  <h2>Termin buchen</h2>
  <iframe src="https://zeeg.me/aliyorulmaz4242/2h" allowfullscreen></iframe>

  <p class="payment-note">
    💶 Die Bezahlung erfolgt direkt vor Ort nach dem Termin. Kein Online-Zahlungsvorgang nötig.
  </p>

  <div class="contact">
    <h2>Kontakt</h2>
    <p>👤 Ali Batin Yorulmaz</p>
    <p>📧 E-Mail: <a href="mailto:aliyorulmaz4242@gmail.com">aliyorulmaz4242@gmail.com</a></p>
    <p>📱 Telefon/WhatsApp: <a href="tel:+4915757764491">0157 57764491</a></p>
    <p>📍 Adresse: Friedrich-Ebert-Straße 199, 58566 Kierspe</p>
  </div>

</body>
</html>
