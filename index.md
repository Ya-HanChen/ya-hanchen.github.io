---
layout: default
nav: home
---

<nav style="max-width: 900px; margin: 20px auto 10px; padding: 10px 0; border-bottom: 1px solid #e5e5e5;">
  <div style="text-align: right; padding-right: 40px;">
    <a href="/" style="margin: 0 14px; color:#1a1a1a; text-decoration: none; border-bottom: {% if page.nav == 'home' %}2px solid #1a1a1a{% else %}none{% endif %}; padding-bottom: 2px;">Home</a>
    <a href="/cv" style="margin: 0 14px; color:#1a1a1a; text-decoration: none; border-bottom: {% if page.nav == 'cv' %}2px solid #1a1a1a{% else %}none{% endif %}; padding-bottom: 2px;">CV</a>
    <a href="/research" style="margin: 0 14px; color:#1a1a1a; text-decoration: none; border-bottom: {% if page.nav == 'research' %}2px solid #1a1a1a{% else %}none{% endif %}; padding-bottom: 2px;">Research</a>
    <a href="/contact" style="margin: 0 14px; color:#1a1a1a; text-decoration: none; border-bottom: {% if page.nav == 'contact' %}2px solid #1a1a1a{% else %}none{% endif %}; padding-bottom: 2px;">Contact</a>
  </div>
</nav>

<!-- Top section: photo left, about me right -->
<div style="max-width: 900px; margin: 30px auto;">
  <div style="display: flex; flex-wrap: wrap; align-items: flex-start; gap: 36px;">

    <!-- Profile Photo -->
<div style="max-width: 900px; margin: 40px auto; text-align: center;">
  <img src="/profile.jpg"
       alt="Ya-Han Chen"
       style="width: 280px; max-width: 100%; border-radius: 6px;">
</div>

      <!-- Icon links -->
      <div style="display: flex; flex-wrap: wrap; gap: 18px; align-items: center; font-size: 15px;">

        <a href="https://www.dropbox.com/scl/fi/d86u9hg3m06u7nfm4erep/Han_CV__0628.pdf?rlkey=zgmmkobf7tmkjq8cje2u1ryx0&dl=0">
          📄 CV
        </a>

        <a href="https://scholar.google.com/citations?user=GaNoAdEAAAAJ&hl=en"
           target="_blank"
           style="color:#1a1a1a; text-decoration: none;">
          🎓 Google Scholar
        </a>

        <a href="chen40620@gmail.com"
           style="color:#1a1a1a; text-decoration: none;">
          ✉ Email
        </a>

      </div>

  </div>
</div>
