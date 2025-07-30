<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Evolving the Role of Experience Enablers</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --gradient: linear-gradient(to right, #c7a17a, #f5f5dc);
      --bg: #f9fafb;
      --text: #1f2937;
      --muted: #6b7280;
      --card: #ffffff;
    }

    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
      overflow-x: hidden;
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 30px;
    }

    .slide {
      max-width: 800px;
      background: var(--card);
      border-radius: 16px;
      padding: 40px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      display: none;
      transition: all 0.5s ease;
      transform: translateX(100%);
      opacity: 0;
    }

    .slide.active {
      display: block;
      transform: translateX(0);
      opacity: 1;
    }

    h1, h2, h3 {
      background: var(--gradient);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      color: transparent;
      margin-top: 0;
    }

    h1 {
      font-size: 36px;
    }

    h2 {
      font-size: 28px;
    }

    h3 {
      font-size: 20px;
      font-weight: 400;
      color: var(--muted);
    }

    ul, ol {
      padding-left: 20px;
      margin-top: 16px;
    }

    li {
      margin-bottom: 10px;
    }

    .visual {
      margin-top: 16px;
      font-style: italic;
      color: #475569;
    }

    .footer {
      font-size: 14px;
      color: var(--muted);
      margin-top: 20px;
    }

    .nav-buttons {
      margin: 20px;
    }

    button {
      background: #c7a17a;
      border: none;
      color: white;
      padding: 10px 20px;
      font-size: 16px;
      margin: 0 10px;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background: #aa865d;
    }

    .dots {
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }

    .dot {
      width: 14px;
      height: 14px;
      border-radius: 50%;
      margin: 5px;
      background: #d1d5db;
      cursor: pointer;
    }

    .dot.active {
      background: #c7a17a;
    }

    @media screen and (max-width: 600px) {
      .slide {
        padding: 24px;
      }

      h1 { font-size: 26px; }
      h2 { font-size: 20px; }
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- Slides -->
    <div class="slide active">
      <h1>Evolving the Role of Experience Enablers</h1>
      <h3>Fresh approaches to elevate workplace experience</h3>
      <div class="footer">By: Sanaullah Fazal</div>
    </div>

    <div class="slide">
      <h2>Reverse Feedback Connects</h2>
      <ul>
        <li>Employees ask Enablers questions via AMA sessions or anonymous tools</li>
        <li>Builds openness, reveals communication gaps, and increases trust</li>
        <li>Helpful to log questions & share answers later</li>
      </ul>
      <div class="visual">🔍 Visual: Speech bubble with question mark</div>
    </div>

    <div class="slide">
      <h2>Experience Personas</h2>
      <ul>
        <li>Create fictional, data-based employee types</li>
        <li>Empathy‑driven design for better solutions</li>
        <li>Tailored communication for different personas</li>
        <li><strong>Example Persona:</strong> Aman, the New Joiner — struggles with orientation and seeks low‑pressure help</li>
      </ul>
      <div class="visual">🧑‍💼 Visual: Icons or avatars representing persona types</div>
    </div>

    <div class="slide">
      <h2>EQ (Emotional Intelligence) Training</h2>
      <ul>
        <li>Topics: body language reading, burnout spotting, psychological safety</li>
        <li>Format: 30‑min training circles once a month</li>
        <li>Outcome: Better listening and more empathetic engagement</li>
      </ul>
      <div class="visual">🧠 Visual: Brain or handshake icon</div>
    </div>

    <div class="slide">
      <h2>“Voice of Employee” Snippets</h2>
      <ul>
        <li>Capture 30‑60 second real testimonials (with informed consent)</li>
        <li>Share in leadership meetings or weekly updates</li>
        <li>Adds emotional impact beyond stats</li>
      </ul>
      <div class="visual">📹 Visual: Video camera or speech bubble with play icon</div>
    </div>

    <div class="slide">
      <h2>Vertical-Based Experience Audits</h2>
      <ul>
        <li>Enablers swap focus by experience verticals, not by team/building</li>
      </ul>
      <strong>Vertical Audit Types:</strong>
      <ul>
        <li>Facilities: Kitchen, seating, lighting, comfort</li>
        <li>Tech & Tools: Hardware/software usage, support systems</li>
        <li>Wellbeing: Breakspaces, noise levels, rest zones</li>
        <li>Onboarding: New hire experience, orientation resources</li>
        <li>Communication: Internal notices, updates clarity, frequency</li>
      </ul>
      <strong>Process:</strong>
      <ol>
        <li>Swap vertical observation focus for a day</li>
        <li>Document insights and quick-win suggestions</li>
        <li>Share in learning circles</li>
      </ol>
      <div class="visual">📋 Visual: Magnifying glass or audit checklist icon</div>
    </div>

    <div class="slide">
      <h2>Micro‑Wins Board</h2>
      <ul>
        <li>Enablers log daily small improvements (e.g. “fixed chair in Bay 4”)</li>
        <li>Display on whiteboard, sticky notes, or digital dashboard</li>
        <li>Review entries in huddles; appreciate and celebrate</li>
      </ul>
      <div class="visual">🏆 Visual: Sticky notes, trophy icon, or leaderboard</div>
    </div>

    <div class="slide">
      <h2>Summary & What’s Next</h2>
      <strong>Recap:</strong>
      <ol>
        <li>Reverse Feedback Sessions</li>
        <li>Experience Personas</li>
        <li>EQ Training</li>
        <li>Employee Voice Snippets</li>
        <li>Theme Campaigns (optional)</li>
        <li>Vertical Audits</li>
        <li>Micro‑Wins Board</li>
      </ol>
      <strong>Next Steps:</strong>
      <ul>
        <li>Choose 2–3 pilots for next month</li>
        <li>Assign champions among Enablers</li>
        <li>Track progress and insights</li>
      </ul>
      <div class="visual">🗺️ Visual: Checklist or roadmap icon</div>
    </div>

    <!-- Navigation -->
    <div class="nav-buttons">
      <button onclick="prevSlide()">← Previous</button>
      <button onclick="nextSlide()">Next →</button>
    </div>

    <div class="dots" id="dots"></div>

  </div>

  <script>
    const slides = document.querySelectorAll('.slide');
    const dotsContainer = document.getElementById('dots');
    let current = 0;

    function showSlide(index) {
      slides.forEach((slide, i) => {
        slide.classList.remove('active');
        dotsContainer.children[i].classList.remove('active');
      });
      slides[index].classList.add('active');
      dotsContainer.children[index].classList.add('active');
      current = index;
    }

    function nextSlide() {
      const next = (current + 1) % slides.length;
      showSlide(next);
    }

    function prevSlide() {
      const prev = (current - 1 + slides.length) % slides.length;
      showSlide(prev);
    }

    // Create dots
    slides.forEach((_, i) => {
      const dot = document.createElement('div');
      dot.classList.add('dot');
      if (i === 0) dot.classList.add('active');
      dot.addEventListener('click', () => showSlide(i));
      dotsContainer.appendChild(dot);
    });

    // Arrow key navigation
    document.addEventListener('keydown', (e) => {
      if (e.key === 'ArrowRight') nextSlide();
      if (e.key === 'ArrowLeft') prevSlide();
    });
  </script>
</body>
</html>