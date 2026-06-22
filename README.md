# Hi there, I'm Oleksiy 👋
**AI-Driven Front-End Web Developer**

I design and develop modern, responsive, and conversion-focused websites for businesses. By leveraging advanced AI workflows, I deliver high-quality, production-ready web experiences in days rather than weeks. 

---

### 🚀 Performance & Stats
- **4+ Sites** completely designed, developed, and delivered.
- **2–4 Days** average turnaround time per project.
- **100% Mobile-Responsive** layout optimization guaranteed.
- **5★ Client Satisfaction** across all built platforms.

---

### 🧰 Tech Stack & Tools
- **Core Web:** HTML5, CSS3, JavaScript (ES6+)
- **Design Philosophy:** Clean Typography, Responsive UI/UX, Component-driven CSS layouts (Grid, Flexbox)
- **Methodology:** AI-assisted rapid prototyping, Semantic markup, Smooth interaction handling

---

### 📁 Featured Projects (Demo Gallery)

Here are the four demo websites built to demonstrate distinct aesthetic styles, typographic treatments, and domain solutions:

#### 1. [Blade & Co. Barbershop](<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Blade & Co. Barbershop</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,400&family=Inter:wght@400;500&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#0F0D0A;color:#F2EDE4;font-family:'Inter',sans-serif;overflow-x:hidden}
nav{position:fixed;top:0;left:0;right:0;z-index:99;display:flex;align-items:center;justify-content:space-between;padding:0 3rem;height:64px;background:rgba(15,13,10,0.92);backdrop-filter:blur(10px);border-bottom:1px solid rgba(255,255,255,0.06)}
.logo{font-family:'Playfair Display',serif;font-size:1.3rem;color:#C9A84C;letter-spacing:0.04em}
.nav-links{display:flex;gap:2rem;list-style:none}
.nav-links a{color:rgba(242,237,228,0.5);font-size:0.82rem;text-decoration:none;letter-spacing:0.08em;text-transform:uppercase;transition:color .2s}
.nav-links a:hover{color:#C9A84C}
.book-btn{background:#C9A84C;color:#0F0D0A;padding:0.4rem 1.2rem;font-size:0.8rem;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;text-decoration:none}
.hero{min-height:100vh;display:flex;align-items:center;padding:0 3rem;background:linear-gradient(135deg,#0F0D0A 55%,#1a1410 100%)}
.hero-badge{display:inline-block;border:1px solid rgba(201,168,76,0.35);color:#C9A84C;font-size:0.72rem;letter-spacing:0.2em;text-transform:uppercase;padding:0.35rem 1rem;margin-bottom:2rem}
h1{font-family:'Playfair Display',serif;font-size:clamp(3rem,6vw,5.5rem);line-height:1.0;font-weight:700;margin-bottom:1.5rem}
h1 span{color:#C9A84C;font-style:italic}
.hero-sub{color:rgba(242,237,228,0.5);font-size:1rem;line-height:1.75;margin-bottom:2.5rem;max-width:400px}
.hero-btns{display:flex;gap:1rem;flex-wrap:wrap}
.btn-gold{background:#C9A84C;color:#0F0D0A;padding:0.75rem 2rem;font-weight:700;font-size:0.85rem;letter-spacing:0.06em;text-transform:uppercase;text-decoration:none}
.btn-outline{border:1px solid rgba(255,255,255,0.2);color:#F2EDE4;padding:0.75rem 2rem;font-size:0.85rem;text-decoration:none}
section{padding:6rem 3rem}
.section-label{font-size:0.7rem;letter-spacing:0.2em;text-transform:uppercase;color:#C9A84C;margin-bottom:0.5rem}
h2{font-family:'Playfair Display',serif;font-size:clamp(2rem,4vw,3rem);font-weight:700;margin-bottom:0.25rem}
.services-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:rgba(255,255,255,0.06);margin-top:3rem;border:1px solid rgba(255,255,255,0.06)}
.service{background:#0F0D0A;padding:2.5rem 2rem}
.service-price{font-family:'Playfair Display',serif;font-size:2rem;color:#C9A84C;margin-bottom:0.5rem}
.service-name{font-size:1rem;font-weight:500;margin-bottom:0.5rem}
.service-desc{font-size:0.82rem;color:rgba(242,237,228,0.4);line-height:1.6}
.team{background:#110E0B}
.team-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.5rem;margin-top:3rem}
.barber{background:#1a1410;padding:2rem;border:1px solid rgba(255,255,255,0.05)}
.barber-av{width:56px;height:56px;border-radius:50%;background:linear-gradient(135deg,#C9A84C,#7a5c10);margin-bottom:1rem;display:flex;align-items:center;justify-content:center;font-size:1.4rem}
.barber-name{font-family:'Playfair Display',serif;font-size:1.1rem;margin-bottom:0.2rem}
.barber-role{font-size:0.75rem;color:#C9A84C;letter-spacing:0.12em;text-transform:uppercase;margin-bottom:0.75rem}
.barber-spec{font-size:0.82rem;color:rgba(242,237,228,0.4);line-height:1.6}
.cta-sec{text-align:center;background:#0F0D0A;border-top:1px solid rgba(255,255,255,0.05)}
.cta-sec p{color:rgba(242,237,228,0.45);margin:1rem 0 2.5rem}
footer{background:#080705;padding:1.75rem 3rem;display:flex;justify-content:space-between;align-items:center;font-size:0.78rem;color:rgba(242,237,228,0.25);border-top:1px solid rgba(255,255,255,0.04)}
</style>
</head>
<body>
<nav>
  <div class="logo">Blade & Co.</div>
  <ul class="nav-links"><li><a href="#">Services</a></li><li><a href="#">Team</a></li><li><a href="#">Gallery</a></li></ul>
  <a href="#" class="book-btn">Book Now</a>
</nav>
<section class="hero">
  <div>
    <div class="hero-badge">Est. 2018 · Warsaw, PL</div>
    <h1>Sharp cuts.<br><span>Sharper</span><br>look.</h1>
    <p class="hero-sub">Premium barbershop experience for the modern gentleman. Walk in with an idea, walk out with a statement.</p>
    <div class="hero-btns"><a href="#" class="btn-gold">Book Appointment</a><a href="#" class="btn-outline">View Services</a></div>
  </div>
</section>
<section>
  <div class="section-label">What we offer</div><h2>Our Services</h2>
  <div class="services-grid">
    <div class="service"><div class="service-price">$25</div><div class="service-name">Classic Haircut</div><div class="service-desc">Scissors or clippers, tailored to your face shape and lifestyle.</div></div>
    <div class="service"><div class="service-price">$35</div><div class="service-name">Fade & Style</div><div class="service-desc">Clean taper fade with a personalized style finish.</div></div>
    <div class="service"><div class="service-price">$20</div><div class="service-name">Hot Towel Shave</div><div class="service-desc">Traditional straight-razor shave with warm towel treatment.</div></div>
    <div class="service"><div class="service-price">$15</div><div class="service-name">Beard Trim</div><div class="service-desc">Shape and define your beard for a polished look.</div></div>
    <div class="service"><div class="service-price">$55</div><div class="service-name">Full Package</div><div class="service-desc">Haircut + beard + hot towel. The complete gentleman experience.</div></div>
    <div class="service"><div class="service-price">$40</div><div class="service-name">Color & Tone</div><div class="service-desc">Gray blending, highlights, or full color. Subtle or bold.</div></div>
  </div>
</section>
<section class="team">
  <div class="section-label">Meet the crew</div><h2>Our Barbers</h2>
  <div class="team-grid">
    <div class="barber"><div class="barber-av">✂️</div><div class="barber-name">Marco Silva</div><div class="barber-role">Master Barber</div><div class="barber-spec">Classic cuts, hot towel shaves. 12 years of precision.</div></div>
    <div class="barber"><div class="barber-av">💈</div><div class="barber-name">James O'Brien</div><div class="barber-role">Fade Specialist</div><div class="barber-spec">Skin fades, textures, modern styles. 8 years in the game.</div></div>
    <div class="barber"><div class="barber-av">🪒</div><div class="barber-name">Luca Ferretti</div><div class="barber-role">Color & Style</div><div class="barber-spec">Hair coloring, beard styling. Former fashion week groomer.</div></div>
  </div>
</section>
<section class="cta-sec">
  <div class="section-label">Ready?</div><h2>Book Your Seat</h2>
  <p>Available Mon–Sat, 9 AM – 8 PM. Walk-ins welcome.</p>
  <a href="#" class="btn-gold">Reserve a Spot →</a>
</section>
<footer><span>Blade & Co. Barbershop</span><span>Warsaw · +48 22 123 45 67</span><span>© 2026</span></footer>
</body>
</html>)
*Premium local service business landing page.*
- **Aesthetic:** High-contrast dark theme with premium gold accents (`#C9A84C`), serif headers, and bold layouts.
- **Features:** Comprehensive service grid with pricing cards, barber profile highlight section, and integrated table booking call-to-actions.
- **Build Time:** 1 Day

#### 2. [Solis Yoga Studio](https://github.com/yourusername/solis-yoga)
*Editorial-style wellness studio platform.*
- **Aesthetic:** Warm, soothing neutral background colors (`#F7F4EF`) paired with elegant typography (`Cormorant Garamond`).
- **Features:** Group class category cards with custom meta attributes (duration/level) and a multi-tier structured membership pricing grid.
- **Build Time:** 2 Days

#### 3. [Foresta — Farm to Table](https://github.com/yourusername/foresta-restaurant)
*Immersive restaurant website themed around nature and seasonal ingredients.*
- **Aesthetic:** Forest green gradients (`#3D7A4F`) with delicate italicized serif headings, conveying fresh organic values.
- **Features:** Interactive grouped menu layout split by courses (Starters / Mains), storytelling section, and an integrated reservation scheduler form interface.
- **Build Time:** 3 Days

#### 4. [Taskly — Project Management](https://github.com/yourusername/taskly)
*Sleek, modern SaaS landing page and app interface preview.*
- **Aesthetic:** Crisp tech tech style utilizing a vibrant purple accent hue (`#6C47FF`) with rounded geometry.
- **Features:** Simulated interactive web app UI featuring a mock sidebar navigation, active design-system tasks with completion states, dynamic feature matrices, and transparent SaaS pricing models.
- **Build Time:** 3 Days

---

### 🛠️ My Development Process
1. **Goal Alignment:** Define the conversion strategy, key actions, and aesthetic mood.
2. **AI Prototyping:** Rapid layout generation, exploring structural variations using state-of-the-art AI tools.
3. **Refinement & Polish:** Hand-tuning semantic markup, setting custom CSS variables, structuring robust Flex/Grid wrappers, and ensuring fluid mobile layouts.
4. **Optimization:** Auditing visual hierarchy, checking form hooks, and minimizing load times for final delivery.

---

### 📫 Get in touch!
I'm always looking to connect for freelance opportunities, open-source collaborations, or to help your business launch its next rapid web product!

- 📧 **Email:** [alosha.tatarin95@gmail.com](mailto:alosha.tatarin95@gmail.com)
- 📍 **Based in:** Warsaw, Poland

*Let's build something fast and beautiful together!*
