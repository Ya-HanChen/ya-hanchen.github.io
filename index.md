---
layout: default
nav: home
---
<link rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
<nav style="max-width: 900px; margin: 20px auto 10px; padding: 10px 0; border-bottom: 1px solid #e5e5e5;">
  <div style="text-align: right; padding-right: 40px;">
    <a href="/" style="margin: 0 14px; color:#1a1a1a; text-decoration: none; border-bottom: {% if page.nav == 'home' %}2px solid #1a1a1a{% else %}none{% endif %}; padding-bottom: 2px;">Home</a>
    <a href="/cv" style="margin: 0 14px; color:#1a1a1a; text-decoration: none; border-bottom: {% if page.nav == 'cv' %}2px solid #1a1a1a{% else %}none{% endif %}; padding-bottom: 2px;">CV</a>
    <a href="/research" style="margin: 0 14px; color:#1a1a1a; text-decoration: none; border-bottom: {% if page.nav == 'research' %}2px solid #1a1a1a{% else %}none{% endif %}; padding-bottom: 2px;">Research</a>
    <a href="/contact" style="margin: 0 14px; color:#1a1a1a; text-decoration: none; border-bottom: {% if page.nav == 'contact' %}2px solid #1a1a1a{% else %}none{% endif %}; padding-bottom: 2px;">Contact</a>
  </div>
</nav>


<!-- Left Column -->
<div style="flex: 0 0 280px; text-align:center;">

    <img src="/profile.jpg"
         alt="Ya-Han Chen"
         style="width:280px; max-width:100%; border-radius:8px;">

    <div style="margin-top:24px;">

        <a href="https://www.dropbox.com/scl/fi/d86u9hg3m06u7nfm4erep/Han_CV__0628.pdf?rlkey=zgmmkobf7tmkjq8cje2u1ryx0&dl=0"
           style="display:block; margin:10px 0; color:#333; text-decoration:none;">
            <i class="fa-regular fa-file-lines"></i>
            CV
        </a>

        <a href="https://scholar.google.com/citations?user=GaNoAdEAAAAJ&hl=en"
           target="_blank"
           style="display:block; margin:10px 0; color:#333; text-decoration:none;">
            <i class="fa-solid fa-graduation-cap"></i>
            Google Scholar
        </a>
        
        <a href="https://orcid.org/0009-0003-9994-5038"
           target="_blank"
           style="display:block; margin:12px 0; color:#333; text-decoration:none;">
          <i class="fa-brands fa-orcid" style="width:24px;"></i>
          ORCID
        </a>

        <a href="mailto:chen40620@gmail.com"
           style="display:block; margin:10px 0; color:#333; text-decoration:none;">
            <i class="fa-regular fa-envelope"></i>
            Email
        </a>

    </div>

</div>
