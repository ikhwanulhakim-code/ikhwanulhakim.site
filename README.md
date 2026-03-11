# 🌐 ikhwanulhakim.site

🌐 _[Baca dalam Bahasa Indonesia](README.id.md)_

> A personal website that was supposed to be a quick weekend project. It's now a single HTML file with 1900+ lines and zero regrets.

<p align="center">
  <a href="https://ikhwanulhakim.site">
    <img src="https://img.shields.io/badge/👉_CHECK_IT_OUT-ikhwanulhakim.site-00d4ff?style=for-the-badge&labelColor=0a192f" alt="Visit Website"/>
  </a>
</p>

[![Self Hosted](https://img.shields.io/badge/Hosted_On-Old_Laptop_🏠-orange?style=flat-square)](#-fun-fact)

<p align="center">
  <img src="preview.png" alt="Preview" width="600"/>
</p>

---

## 📖 The Story

Started this as my "I'm gonna build an amazing portfolio" project. You know, the one every developer promises themselves.

The plan was _ambitious_:

```
✓ Cool intro page          (done! finally something works)
✓ Project showcase         (10 portfolio cards, flexing responsibly)
✓ Work experience timeline (with a "productive unemployment" entry, yes really)
✓ Personal projects        (with "Google it" buttons for SEO dominance)
✓ About section            (pizza proof, cat photos, and a homeserver video)
○ Blog section             (lol)
```

Plot twist: I got hired before finishing any of that. Then I finished it anyway because unemployment gave me two months of "creative energy" (read: too much free time and pizza dough).

Will I add a blog? Probably. When? After I run out of things to self-host.

---

## 💡 Fun Fact

This entire website runs on **an old Infinix InBook X1 laptop sitting in my room**. Intel i3-1005G1, 8GB RAM, 256GB NVMe. Running Proxmox because why use a cloud provider when you can anxiety-check your `/var/log` at 2 AM?

No AWS, no Vercel, no subscription fees. Just vibes and a laptop that refuses to retire. Only expense? A cheap domain.

Self-hosted gang rise up. 🏠

---

## ⚙️ Tech Stack

| Layer        | Tech                                   |
| ------------ | -------------------------------------- |
| Frontend     | HTML5, CSS3, Vanilla JS                |
| CMS          | WordPress + Elementor (HTML block)     |
| Architecture | One file. That's it. That's the stack. |
| Server       | Old laptop running Proxmox             |
| Uptime       | _depends on my electricity bill_       |
| CI/CD        | Ctrl+C, Ctrl+V into WordPress          |

---

## 🎯 Features

- 🌙 Dark/Light mode with `localStorage` persistence
- 📱 Fluid responsive layout using `clamp()` everywhere
- ✨ Smooth CSS animations (keyframes go brrr)
- 🔗 Social links (WhatsApp, Instagram, LinkedIn)
- 💼 Work experience timeline with semantic `<time>` elements
- 📂 Portfolio showcase (10 cards, some confidential because NDAs exist)
- 🚀 Personal projects with live links and "Google it" SEO flex
- 🍕 About section with photo/video lightbox modal
- 🎥 Video player support in modal (for the homeserver tour)
- ♿ Full ARIA tab roles because accessibility is a flex, not a chore
- 📊 Rich JSON-LD structured data (Google's crawlers send thank-you emails)
- 🔍 SEO so thorough it's basically a love letter to search engines

---

## 📂 Repository Structure

```
ikhwanulhakim.site/
├── elementor-embed.html  ← 1900+ lines of pure determination
├── linkedin_projects.txt ← portfolio data source (the sacred scrolls)
├── PLAN.md               ← the plan that somehow actually got followed
├── README.md             ← you are here, congrats
└── README.id.md          ← same thing but in Bahasa, karena inklusif
```

---

## 🚀 "Deployment" Process

```
1. Edit elementor-embed.html
2. Ctrl+A → Ctrl+C
3. Paste into Elementor HTML block
4. Click Save
5. Pray
6. Check if the laptop is still alive
```

No CI/CD. No pipelines. No Docker. Just vibes and Ctrl+V.

---

<p align="center">
  <b>© 2025 – 2026 Ikhwanul Hakim</b><br>
  <sub>Built with mass procrastination, homemade pizza, and an unreasonable amount of CSS custom properties</sub>
</p>
