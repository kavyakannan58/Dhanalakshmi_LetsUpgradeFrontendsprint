# Dhanalakshmi_LetsUpgradeFrontendsprint
My Portfolio demo
css
 * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Poppins", sans-serif;
  background: linear-gradient(135deg, #e0c3fc, #8ec5fc);
  color: #333;
  padding: 20px;
}

.container {
  max-width: 1100px;
  margin: auto;
}

header {
  text-align: center;
  padding: 60px 20px;
  color: white;
}

.gradient-text {
  font-size: 2.5rem;
  background: linear-gradient(to right, #6a11cb, #2575fc);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.section-title {
  text-align: center;
  margin-bottom: 20px;
  font-size: 1.8rem;
  color: #333;
}

section {
  margin: 50px 0;
}

.glass {
  background: rgba(255, 255, 255, 0.2);
  backdrop-filter: blur(10px);
  padding: 25px;
  border-radius: 15px;
  box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
}

.projects .project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 30px;
}

.card {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
}

.contact {
  text-align: center;
}

footer {
  text-align: center;
  margin-top: 60px;
  color: #222;
  font-size: 0.9rem;
}
