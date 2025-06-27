/* === style.css === */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
}
body {
  background-color: #f9f9f9;
  color: #222;
  line-height: 1.6;
}
header, footer {
  background-color: #fff;
  padding: 1.5rem;
  text-align: center;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}
nav a, a.volver {
  color: #222;
  text-decoration: none;
  font-weight: bold;
}
nav a:hover, a.volver:hover {
  color: #000;
}
main {
  max-width: 1000px;
  margin: auto;
  padding: 2rem 1rem;
}
h1, h2 {
  text-align: center;
  margin-bottom: 1rem;
}
.botones {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  align-items: center;
  margin-top: 2rem;
}
.botones a {
  padding: 1rem 2rem;
  background-color: #222;
  color: white;
  text-decoration: none;
  border-radius: 8px;
  transition: background-color 0.3s;
}
.botones a:hover {
  background-color: #444;
}
form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  max-width: 500px;
  margin: auto;
}
input, textarea {
  padding: 0.75rem;
  border: 1px solid #ccc;
  border-radius: 5px;
}
button {
  background-color: #222;
  color: #fff;
  padding: 0.75rem;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s;
}
button:hover {
  background-color: #444;
}
.subtitulo {
  margin-top: 2rem;
  font-size: 1.5rem;
  font-weight: bold;
  border-bottom: 2px solid #ccc;
  padding-bottom: 0.5rem;
}
.galeria {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
}
.galeria img, .galeria video {
  width: 100%;
  border-radius: 10px;
  object-fit: cover;
}

/* === README.md === */

# Fernando Salazar Web
