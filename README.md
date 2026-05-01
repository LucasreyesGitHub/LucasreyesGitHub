<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lucas Reyes - Profile</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
<style>
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background: #0d1117;
  color: #e6edf3;
}
.container {
  max-width: 1100px;
  margin: auto;
  padding: 20px;
}
.header {
  background: linear-gradient(135deg, #0d1117, #001f1a);
  border: 1px solid #00ff41;
  border-radius: 20px;
  padding: 30px;
  box-shadow: 0 0 25px rgba(0,255,65,0.15);
}
.title {
  font-size: 48px;
  font-weight: 800;
}
.title span {
  color: #00ff41;
}
.subtitle {
  margin-top: 10px;
  color: #8b949e;
}
.terminal {
  margin-top: 20px;
  background: #010409;
  border-radius: 12px;
  padding: 15px;
  font-family: monospace;
  border: 1px solid #00ff41;
}
.section {
  margin-top: 25px;
}
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 15px;
}
.card {
  background: #0d1117;
  border: 1px solid #1f2937;
  border-radius: 16px;
  padding: 20px;
  transition: 0.3s;
}
.card:hover {
  border-color: #00ff41;
  transform: translateY(-5px);
}
.card h3 {
  margin: 0 0 10px;
  color: #00ff41;
}
.badge {
  display: inline-block;
  padding: 5px 10px;
  border-radius: 10px;
  background: #00ff41;
  color: #000;
  font-size: 12px;
  margin-right: 5px;
}
.footer {
  text-align: center;
  margin-top: 40px;
  color: #8b949e;
}
</style>
</head>
<body>
<div class="container">

<div class="header">
  <div class="title">Lucas <span>Reyes</span></div>
  <div class="subtitle">Engineering Student · Data · Automation · Cybersecurity (Learning)</div>

  <div class="terminal">
    <p>lucas@github:~$ whoami</p>
    <p>> Ingeniería en Computación · Data · Automation · Cyber (Jr)</p>
    <p>lucas@github:~$ locate --focus</p>
    <p>> Data Analysis · AI Workflows · Automation</p>
    <p>lucas@github:~$ status</p>
    <p>> OPEN TO WORK ✓ | LEARNING: Always</p>
  </div>
</div>

<div class="section grid">
  <div class="card"><h3>Status</h3>Engineering Student</div>
  <div class="card"><h3>Focus</h3>Data & Automation</div>
  <div class="card"><h3>Cyber</h3>Learning (Blue Team)</div>
  <div class="card"><h3>AI</h3>Workflows</div>
</div>

<div class="section">
  <div class="card">
    <h3>About Me</h3>
    <p>Soy estudiante de Ingeniería en Computación enfocado en datos, automatización y ciberseguridad en formación.</p>
  </div>
</div>

<div class="section grid">
  <div class="card">
    <h3>Projects</h3>
    <p><strong>QrSocAnalyzer</strong><br>Análisis de QR maliciosos</p>
    <span class="badge">Python</span>
    <span class="badge">Automation</span>
  </div>
  <div class="card">
    <h3>Automation</h3>
    <p>Make · APIs · Bots</p>
  </div>
  <div class="card">
    <h3>Data</h3>
    <p>Pandas · Analysis · Processing</p>
  </div>
</div>

<div class="section">
  <div class="card">
    <h3>Contact</h3>
    <p>Email: lucasrfcapilla.1b2015@gmail.com</p>
    <p>LinkedIn: linkedin.com/in/lucasreyes2003</p>
  </div>
</div>

<div class="footer">
  Code. Automate. Analyze. Improve.
</div>

</div>
</body>
</html>
