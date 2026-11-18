# Ex02 Commercial Website
## Date:18-11-2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## HTML
```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="/favicon.svg" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>exp2</title>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.jsx"></script>
  </body>
</html>

```
### CSS
```css

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #f5f5f5;
  color: #333;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #222;
  color: white;
  padding: 20px;
}

nav {
  display: flex;
  gap: 25px;
}

nav a {
  color: white;
  text-decoration: none;
  transition: 0.3s;
}

nav a:hover {
  color: orange;
}

section {
  padding: 40px 20px;
  text-align: center;
}

.hero {
  background: #dcecff;
  padding: 80px 20px;
}

.hero h1 {
  font-size: 40px;
  margin-bottom: 15px;
}

.btn, button {
  background: orange;
  color: white;
  border: none;
  padding: 12px 20px;
  text-decoration: none;
  cursor: pointer;
  transition: 0.3s;
}

button:hover, .btn:hover {
  background: #222;
}

.products {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 25px;
  margin-top: 25px;
}

.card {
  background: white;
  padding: 15px;
  width: 230px;
  border-radius: 10px;
  box-shadow: 0 2px 8px #ccc;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

.card img {
  width: 100%;
  height: 160px;
  object-fit: cover;
  border-radius: 8px;
}

.card h3, .card p {
  margin: 12px;
}

input {
  display: block;
  padding: 12px;
  margin: 12px auto;
  width: 250px;
}

footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 25px;
}

footer a {
  color: orange;
  text-decoration: none;
}

@media (max-width: 600px) {
  header {
    flex-direction: column;
    gap: 15px;
  }

  nav {
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
  }
}

}
```
## OUTPUT
<img width="1535" height="872" alt="image" src="https://github.com/user-attachments/assets/3f576fa6-c578-4dbc-b630-40ec68e5eeac" />
<img width="1533" height="870" alt="image" src="https://github.com/user-attachments/assets/78decdd8-fb04-44e8-8899-dde240f7c644" />




## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
