# 🌍 Travel Agency Page

A simple **HTML project** showcasing travel packages and top itineraries using semantic elements such as `<figure>`, `<figcaption>`, and `<meta>` for SEO best practices.  
Built as part of a **freeCodeCamp** HTML learning exercise.

---

## 🧩 Features

- Semantic HTML structure  
- Accessible image descriptions with `alt` attributes  
- Properly nested `<figure>` and `<figcaption>` elements  
- External links open safely in new tabs (`target="_blank"`)  
- Includes a valid meta description tag for SEO  

---

## 🏖️ Live Preview

You can view or test your project locally by opening the HTML file in your browser or using VS Code’s Live Server extension.

**File name:** `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Curated travel packages including group trips, private tours, and top itineraries across Italy—Rome, national parks, and southern islands.">
  <title>Travel Agency Page</title>
</head>
<body>
  <h1>Travel Destinations</h1>
  <p>Below you will see the various travel packages that our agency offers:</p>

  <h2>Packages</h2>
  <p>Please see the various travel packages below:</p>
  <ul>
    <li><a href="https://www.freecodecamp.org/learn" target="_blank">Group Travels</a></li>
    <li><a href="https://www.freecodecamp.org/learn" target="_blank">Private Tours</a></li>
  </ul>

  <h2>Top Itineraries</h2>

  <figure>
    <a href="https://www.freecodecamp.org/learn" target="_blank">
      <img src="https://cdn.freecodecamp.org/curriculum/labs/colosseo.jpg" alt="Rome and Central Italy">
    </a>
    <figcaption>Rome and Central Italy</figcaption>
  </figure>

  <figure>
    <a href="https://www.freecodecamp.org/learn" target="_blank">
      <img src="https://cdn.freecodecamp.org/curriculum/labs/alps.jpg" alt="Nature and National Parks">
    </a>
    <figcaption>Nature and National Parks</figcaption>
  </figure>

  <figure>
    <a href="https://www.freecodecamp.org/learn" target="_blank">
      <img src="https://cdn.freecodecamp.org/curriculum/labs/sea.jpg" alt="South Italy and Islands">
    </a>
    <figcaption>South Italy and Islands</figcaption>
  </figure>
</body>
</html>
