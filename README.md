h1 {
  text-align: center;
  font-size: 48px;
  margin-bottom: 10px;
  color: #B0B0B0; /* light grey */
}

p.intro {
  text-align: center;
  font-size: 20px;
  margin-bottom: 40px;
  color: #B0B0B0; /* light grey */
}

/* Grid layout */
.movie-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  max-width: 1000px;
  margin: 0 auto;
}

.movie-card {
  background-color: #F8D8E2; /* slightly deeper blush */
  padding: 15px;
  border-radius: 15px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  text-align: center;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  color: #B0B0B0; /* light grey text in cards */
}

.movie-card:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

.movie-card img {
  width: 100%;
  border-radius: 12px;
  margin-bottom: 10px;
  object-fit: cover;
}

.movie-card a {
  display: inline-block;
  background-color: #FFECEC;
  color: #B0B0B0; /* light grey links */
  padding: 8px 16px;
  border-radius: 12px;
  text-decoration: none;
  font-weight: bold;
  transition: all 0.2s ease;
}

.movie-card a:hover {
  background-color: #FFB6C1;
  transform: scale(1.05);
  color: #B0B0B0; /* keep hover text light grey */
}

footer {
  margin-top: 50px;
  text-align: center;
  font-size: 16px;
  color: #B0B0B0; /* light grey footer */
}
