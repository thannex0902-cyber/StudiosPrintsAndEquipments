<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Equipment | Nathan Studios</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      background-color: #f7f7f7;
      color: #222;
      margin: 0;
      padding: 0;
    }

    header {
      background: url('https://images.unsplash.com/photo-1504208434309-cb69f4fe52b0?auto=format&fit=crop&w=1950&q=80') center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }

    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2em;
      font-weight: 300;
    }

    section {
      max-width: 1000px;
      margin: 60px auto;
      padding: 0 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 25px;
    }

    .gear {
      background: white;
      border-radius: 12px;
      box-shadow: 0 6px 18px rgba(0, 0, 0, 0.1);
      text-align: center;
      padding: 30px;
      transition: all 0.3s ease;
    }

    .gear:hover {
      transform: translateY(-8px);
    }

    .gear img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 15px;
    }

    .gear h2 {
      color: #111;
      font-size: 1.5em;
      margin-bottom: 10px;
    }

    .gear p {
      font-size: 0.95em;
      color: #555;
    }

    footer {
      background-color: #000;
      color: white;
      text-align: center;
      padding: 40px 20px;
      margin-top: 60px;
    }

    footer a {
      color: #c19a6b;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Our Equipment</h1>
    <p>Precision. Quality. Creativity. The tools behind every Nathan Studios photo.</p>
  </header>

  <section>
    <div class="gear">
      <img src="https://images.unsplash.com/photo-1519183071298-a2962eadc7cc?auto=format&fit=crop&w=800&q=80" alt="Camera">
      <h2>Sony A7 IV</h2>
      <p>Full-frame mirrorless camera delivering incredible detail and dynamic range for every shoot.</p>
    </div>

    <div class="gear">
      <img src="https://images.unsplash.com/photo-1584331928898-97a3c2d92e25?auto=format&fit=crop&w=800&q=80" alt="Lens">
      <h2>G Master Prime Lenses</h2>
      <p>Professional-grade lenses providing stunning sharpness and depth for portraits and landscapes.</p>
    </div>

    <div class="gear">
      <img src="https://images.unsplash.com/photo-1581091012184-5c8e3cf4f5f2?auto=format&fit=crop&w=800&q=80" alt="Drone">
      <h2>DJI Air 3 Drone</h2>
      <p>Capturing breathtaking aerial perspectives for weddings, events, and travel projects.</p>
    </div>

    <div class="gear">
      <img src="https://images.unsplash.com/photo-1593642532744-d377ab507dc8?auto=format&fit=crop&w=800&q=80" alt="Lighting">
      <h2>Godox Lighting Kit</h2>
      <p>Professional lighting for both studio and on-location shoots to achieve perfect balance and tone.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Nathan Studios | <a href="https://nathanstudios.github.io/about.html">About Us</a></p>
  </footer>
</body>
</html>
