# Lumipay (루미페이)

> Financial education & consumer-protection focused static website  
> Built with SEO-first architecture on Cloudflare Pages

🌐 **Live site**: https://lumipay.pages.dev  
🧱 **Stack**: Static HTML · CSS · Cloudflare Pages  
🔍 **Topic**: 신용카드현금화 (정보 제공 · 구조 이해 중심)

---

## 📌 Project Purpose

**Lumipay** is a static information website designed to help users understand  
the **structure, risks, regulations, and common misconceptions** around the term  
**“신용카드현금화” (credit card cashing)**.

This project is strictly focused on:

- Consumer education
- Risk awareness
- Financial regulation understanding
- Preventing misinformation and scams

❌ No services  
❌ No methods or execution guides  
❌ No promotions or referrals  

---

## 🧭 Site Architecture (Hub-Based SEO Model)

/
├─ index.html # Main hub
├─ terms/ # Terminology
├─ risks/ # Risk analysis
├─ scams/ # Scam patterns
├─ alternatives/ # Legitimate alternatives (conceptual)
├─ cases/ # Situation-based case explanations
├─ rules/ # Regulations & policy context
├─ faq/ # FAQ (FAQ Schema)
├─ about/ # About & trust
├─ privacy-policy/ # Privacy policy
├─ terms-of-use/ # Terms of use
├─ 404.html # Error page
├─ sitemap.xml # Sitemap
├─ robots.txt # Crawling rules
└─ assets/
└─ css/style.css

yaml
코드 복사

### Architecture principles
- Static HTML only (no backend, no JS framework)
- Hub → Detail → Hub internal linking
- Concept-based navigation (no keyword stuffing)
- Mobile-first, performance-focused

---

## 🔍 SEO Strategy

- Core keyword cluster: **신용카드현금화**
- Main page links only to hub pages
- Detail pages indexed via sitemap + internal links
- FAQ Schema applied only to `/` and `/faq/`
- Organization Schema applied only to `/about/`

### Indexing policy
- **Manual indexing**: Main page + hub pages
- **Automatic indexing**: All detail pages
- **Excluded from indexing**:
  - `/404.html`
  - `/privacy-policy/`
  - `/terms-of-use/`
  - `/assets/*`

---

## 🔐 Privacy & Compliance

- No personal data collection
- No cookies used for tracking
- No login, signup, comments, or contact forms
- Content does **not** replace legal or financial advice

See:
- `/privacy-policy/`
- `/terms-of-use/`

---

## 🚀 Deployment

- **Hosting**: Cloudflare Pages
- **Build step**: None (pure static)
- **CDN**: Cloudflare global CDN
- **Performance**:
  - Mobile-first layout
  - CLS-safe images
  - Minimal JS usage
  - System fonts preferred

---

## ⚠️ Contribution Guidelines

This repository **does not accept** contributions that:

- Promote financial services or vendors
- Describe execution methods or workarounds
- Add advertising, CTA-heavy, or affiliate content
- Weaken consumer-protection intent

All content must remain **informational and educational**.

---

## 📄 License

© 2025 Lumipay  
All rights reserved.

Content may not be reused, redistributed, or commercialized without permission.
