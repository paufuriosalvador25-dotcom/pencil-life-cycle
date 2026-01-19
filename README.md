<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Life Cycle of a Pencil</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 2.5rem;
      text-align: center;
    }
    nav {
      background: #34495e;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      color: white;
      padding: 1rem;
      text-decoration: none;
      font-size: 0.95rem;
    }
    nav a:hover {
      background: #2c3e50;
    }
    section {
      padding: 3rem;
      background: white;
      margin: 1.5rem auto;
      max-width: 1000px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #2c3e50;
    }
    figure {
      margin: 2rem 0;
      text-align: center;
    }
    figure img {
      max-width: 100%;
      border-radius: 8px;
    }
    figcaption {
      font-size: 0.9rem;
      color: #555;
      margin-top: 0.5rem;
    }
    button {
      padding: 0.6rem 1rem;
      background: #2c3e50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 1rem;
    }
    button:hover {
      background: #1a252f;
    }
    .hidden {
      display: none;
    }
    footer {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 2rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

<header>
  <h1>The Life Cycle of a Pencil</h1>
  <p>A Complete Environmental and Industrial Analysis</p>
</header>

<nav>
  <a href="#intro">Introduction</a>
  <a href="#materials">Raw Materials</a>
  <a href="#processing">Processing</a>
  <a href="#manufacturing">Manufacturing</a>
  <a href="#transport">Transportation</a>
  <a href="#use">Use Phase</a>
  <a href="#end">End of Life</a>
  <a href="#impact">Impact</a>
  <a href="#sustainability">Sustainability</a>
  <a href="#references">References</a>
</nav>

<section id="intro">
  <h2>Introduction</h2>
  <p>A pencil may appear simple, but its creation depends on complex global systems involving forestry, mining, manufacturing, transportation, and waste management. This website explains the complete life cycle of a pencil from raw material extraction to disposal.</p>
  <figure>
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Pencils.jpg" alt="Pencils">
    <figcaption>Figure 1: Finished pencils ready for distribution and use.</figcaption>
  </figure>
</section>

<section id="materials">
  <h2>Raw Materials</h2>
  <p>Pencils are made from both renewable and non-renewable resources. The wooden body is typically made from incense cedar trees, chosen for their strength and ease of sharpening. The core is made of graphite mixed with clay to control hardness. Aluminum is used for the ferrule, rubber for the eraser, and paint for protection.</p>
  <figure>
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Cedar_tree.jpg" alt="Cedar tree">
    <figcaption>Figure 2: Cedar trees are commonly harvested for pencil production.</figcaption>
  </figure>
</section>

<section id="processing">
  <h2>Material Processing</h2>
  <p>After extraction, materials must be processed. Wood is cut into slats and kiln-dried. Graphite is crushed, mixed with clay, and baked into rods. Aluminum undergoes refining and electrolysis, one of the most energy-intensive industrial processes.</p>
  <button onclick="toggleInfo('processingMore')">Learn more</button>
  <p id="processingMore" class="hidden">Processing requires large amounts of energy and water and produces emissions that contribute to climate change if not managed sustainably.</p>
</section>

<section id="manufacturing">
  <h2>Manufacturing</h2>
  <p>Factories assemble pencils by inserting graphite cores into grooved wooden slats, shaping and sanding the pencils, applying paint, and attaching erasers and ferrules.</p>
  <figure>
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/8c/Pencil_manufacturing.jpg" alt="Pencil factory">
    <figcaption>Figure 3: Pencil manufacturing involves automated machinery and quality control.</figcaption>
  </figure>
</section>

<section id="transport">
  <h2>Transportation and Distribution</h2>
  <p>Pencils are packaged and shipped worldwide using trucks, trains, and ships. Transportation relies heavily on fossil fuels, increasing the product’s carbon footprint.</p>
</section>

<section id="use">
  <h2>Use Phase</h2>
  <p>The use phase is the longest stage. Pencils are used for writing, drawing, and learning. Although environmental impact during use is low, frequent replacement increases demand for new pencils.</p>
</section>

<section id="end">
  <h2>End of Life</h2>
  <p>Most pencils end up in landfills. Wood and graphite decompose naturally, while erasers and metal parts persist longer. Recycling is limited due to mixed materials.</p>
</section>

<section id="impact">
  <h2>Environmental Impact</h2>
  <p>The pencil life cycle contributes to deforestation, mining damage, energy use, greenhouse gas emissions, and waste generation.</p>
</section>

<section id="sustainability">
  <h2>Sustainability and Improvements</h2>
  <p>Sustainability can be improved by using certified wood, reducing packaging, increasing recycled materials, and encouraging full use of pencils.</p>
</section>

<section id="references">
  <h2>References (APA 7th Edition)</h2>
  <p>Encyclopaedia Britannica. (2023). <i>Pencil</i>.</p>
  <p>Encyclopaedia Britannica. (2024). <i>Graphite</i>.</p>
  <p>Forest Stewardship Council. (2023). <i>What is sustainable forestry?</i></p>
  <p>International Organization for Standardization. (2006). <i>ISO 14040: Life Cycle Assessment</i>.</p>
  <p>United States Environmental Protection Agency. (2023). <i>Sources of greenhouse gas emissions</i>.</p>
</section>

<footer>
  <p>© 2026 | The Life Cycle of a Pencil | Educational Website</p>
</footer>

<script>
  function toggleInfo(id) {
    const el = document.getElementById(id);
    el.classList.toggle('hidden');
  }
</script>

</body>
</html>
