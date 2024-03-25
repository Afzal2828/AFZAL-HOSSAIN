/* Basic styles for layout and formatting */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav ul li {
  margin-right: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

main {
  padding: 20px;
}

section {
  margin-bottom: 40px;
}

#gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  grid-gap: 20px;
}

#gallery img {
  max-width: 100%;
  height: auto;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
}
