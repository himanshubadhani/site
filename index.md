<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Himanshu Badhani — Research</title>
  <link rel="stylesheet" href="styles.css" />
  <meta name="description" content="Himanshu Badhani — Institute of Mathematical Sciences. Quantum physics research and publications." />
</head>
<body>
  <header class="site-header">
    <div class="container">
      <img src="images/profile.jpg" alt="Himanshu Badhani" class="avatar" />
      <div>
        <h1>Himanshu Badhani</h1>
        <p class="affil">Institute of Mathematical Sciences — Faculty of Theoretical Physics</p>
        <p class="tagline">Research interests: Quantum physics, non-Hermitian systems, quantum information.</p>
        <p class="links">
          <a href="https://scholar.google.com/citations?user=2b1W1P0AAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
          <!-- add other links here -->
        </p>
      </div>
    </div>
  </header>

  <main class="container">
    <section id="about">
      <h2>About</h2>
      <p>
        Researcher working on quantum dynamics, non-Hermitian quantum systems, quantum walks and
        aspects of quantum information. (Info pulled from Google Scholar profile.) :contentReference[oaicite:4]{index=4}
      </p>
    </section>

    <section id="publications">
      <h2>Selected publications</h2>
      <p class="note">List based on Google Scholar (selected recent works). :contentReference[oaicite:5]{index=5}</p>
      <ul class="pub-list">
        <li>
          <strong>Improvement in quantum communication using quantum switch</strong><br />
          A. Mitra, H. Badhani, S. Ghosh — Physica Scripta (2023). <a href="https://scholar.google.com/scholar?q=Improvement+in+quantum+communication+using+quantum+switch" target="_blank" rel="noopener">find</a>
        </li>
        <li>
          <strong>Gravitationally induced entanglement dynamics between two quantum walkers</strong><br />
          H. Badhani, C.M. Chandrashekar — Eur. Phys. J. C (2021). <a href="https://scholar.google.com/scholar?q=Gravitationally+induced+entanglement+dynamics+between+two+quantum+walkers" target="_blank" rel="noopener">find</a>
        </li>
        <li>
          <strong>Non-Hermitian quantum walks and non-Markovianity: the coin-position interaction</strong><br />
          H. Badhani, S. Banerjee, C.M. Chandrashekar — Physica Scripta (2021). <a href="https://scholar.google.com/scholar?q=Non-Hermitian+quantum+walks+and+non-Markovianity" target="_blank" rel="noopener">find</a>
        </li>
        <li>
          <strong>Reduced dynamics of a PT-symmetric evolution</strong><br />
          H. Badhani, C.M. Chandrashekar — arXiv:2309.03042 (2023). <a href="https://arxiv.org/abs/2309.03042" target="_blank" rel="noopener">arXiv</a>
        </li>
        <li>
          <strong>Decomposition of a system in pseudo-Hermitian quantum mechanics</strong><br />
          H. Badhani, S. Ghosh — J. Phys. A (2025). <a href="https://scholar.google.com/scholar?q=Decomposition+of+a+system+in+pseudo-Hermitian+quantum+mechanics" target="_blank" rel="noopener">find</a>
        </li>
      </ul>
      <p class="more">
        For a full list of publications, see the <a href="https://scholar.google.com/citations?user=2b1W1P0AAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar profile</a>. :contentReference[oaicite:6]{index=6}
      </p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>
        Verified email domain shown on profile: <code>@imsc.res.in</code>. For exact contact details use the profile or institutional page. :contentReference[oaicite:7]{index=7}
      </p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <small>Generated site — content sourced from Google Scholar profile.</small>
    </div>
  </footer>

  <script>
    // small enhancement: show year in footer
    document.addEventListener('DOMContentLoaded', () => {
      const year = new Date().getFullYear();
      const f = document.querySelector('.site-footer small');
      if (f) f.textContent = f.textContent + ' © ' + year;
    });
  </script>
</body>
</html>
2) styles.css
css
Copy code
:root{
  --bg:#0f1724; /* dark friendly */
  --card:#0b1220;
  --muted:#9aa4b2;
  --accent:#67c8ff;
  --text:#eef6ff;
}

*{box-sizing:border-box}
body{
  margin:0;
  font-family:system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
  background:linear-gradient(180deg,#071021,var(--bg));
  color:var(--text);
  line-height:1.5;
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
}
.container{
  max-width:920px;
  margin:0 auto;
  padding:20px;
}
.site-header{
  padding:28px 0;
  border-bottom:1px solid rgba(255,255,255,0.04);
}
.site-header .container{
  display:flex;
  gap:18px;
  align-items:center;
}
.avatar{
  width:120px;
  height:120px;
  object-fit:cover;
  border-radius:12px;
  box-shadow:0 6px 20px rgba(0,0,0,0.6);
  border:2px solid rgba(255,255,255,0.03);
}
h1{margin:0 0 6px;font-size:1.6rem}
.affil{margin:0;color:var(--muted)}
.tagline{margin-top:8px;color:var(--muted)}
.links a{
  color:var(--accent);
  text-decoration:none;
  margin-right:10px;
}
main{padding:28px 0}
section{margin-bottom:28px;background:rgba(255,255,255,0.01);padding:18px;border-radius:10px}
.pub-list{list-style:none;padding-left:0;margin:12px 0}
.pub-list li{padding:12px 0;border-bottom:1px dashed rgba(255,255,255,0.03)}
.pub-list li:last-child{border-bottom:none}
.note{color:var(--muted)}
.more{margin-top:10px}
.site-footer{
  border-top:1px solid rgba(255,255,255,0.03);
  padding:16px 0;
  text-align:center;
  color:var(--muted);
  font-size:0.9rem;
}

/* responsive */
@media (max-width:640px){
  .site-header .container{flex-direction:row; gap:12px; align-items:flex-start}
  .avatar{width:86px;height:86px}
}
