# Hi, I'm Abolfazl Mirolyae 👋

### Web & Python Developer | Telegram/Bale Bots | Business Automation

I'm a web developer and IT professional with hands-on experience in building business websites, custom content management systems, organizational automation bots, and web-based management applications.

During my professional experience at Herosun, an automotive spare parts company, I have worked across software development, IT support, and digital marketing. I enjoy solving real-world problems through technology, improving business workflows, and building practical tools that make everyday work more efficient.

I build software that runs in production at a real company, and I deliver it tested, documented and supported.

---

## 🚀 Featured Projects

### 1. Herosun Website & Custom CMS
**Technology:** PHP · Yii2 · JavaScript · CSS · MySQL

🔗 **Live website: [herosunco.ir](https://herosunco.ir)**

🛠️ **Try the CMS dashboard: [live demo](https://abolfazl-mirolyae.github.io/herosun-demo/cms/)** — the real dashboard code in preview mode; changes stay in your browser.

Developed the company's website and built a custom content management system to manage website content and support day-to-day website administration.

**CMS features:**
- Blog, events (photo and video galleries), brands with PDF catalogues, products, homepage supplier logos and page texts, all managed from one Persian dashboard
- Two business lines (spare parts, sport & accessories) with per-brand placement
- Safe editing: optimistic locking between editors, atomic saves, automatic backups of the last 20 versions and one-click restore
- Uploads validated by real file type; photos automatically resized to 1920px with correct phone rotation
- Unused media finder to free server space
- Per-article SEO title, description and share image, with Open Graph and structured data on the site
- Recruitment inbox with private résumé storage, and admin-only access with login lockout

**Key contributions:**
- Website development and implementation
- Custom CMS development
- Website content management and maintenance
- Technical troubleshooting and improvements
- Responsive, right-to-left (Persian) redesign of the main pages
- Performance work: the spare parts page went from 4.2 MB of HTML to 26 KB
- Security and SEO clean-up: disabled production debug output, rebuilt the sitemap, added redirects for duplicate pages

*The production source code is not publicly available.*

### 2. Business Automation Bots

Developed automation tools to support internal business processes and improve communication.

**Customer Birthday Automation**
- Automated customer birthday greetings
- Implemented additional management features to support the workflow

**Internal Issue Reporting Bot**
- Provided a way for employees to report technical issues and problems
- Helped organize internal issue reporting and follow-up processes

*Project details and demonstrations will be shared without exposing confidential company information.*

### 3. Kartabl — Organizational Task Management & Office Automation Platform
**Technology:** Python · FastAPI · SQLAlchemy · SQLite · WebSocket · Bale Bot API · JavaScript · CSS

🔗 **Live demo: [abolfazl-mirolyae.github.io/kartabl-demo](https://abolfazl-mirolyae.github.io/kartabl-demo/)** · [demo repository](https://github.com/abolfazl-mirolyae/kartabl-demo)

Designed and developed a Persian (right-to-left) web application for organizational task and workflow management, built for daily use inside a real company.

**Key capabilities include:**
- Task and project management with list, kanban and Jalali (Persian) calendar views
- Office automation: multi-step approval workflows, official letters, leave requests, meetings and minutes
- Real-time chat and online meetings (WebSocket), plus always-on-screen sticky notes
- Bale messenger bot for notifications, approvals, leave requests and one-time-code login
- Light, dark and Liquid Glass themes, designed against WCAG contrast guidelines

**Quality and security:**
- Load-tested with 200 concurrent users
- 361 automated tests
- Security review: access-control attack sweep, XSS fixes, strict Content Security Policy

*The production source code is private; the public demo shows real screenshots and an interactive preview.*

### 4. Blasphemous 2 — Persian Translation & Installer (open source)
**Technology:** Python · UnityPy · Unity Addressables · TextMeshPro · FreeType · NumPy/SciPy · PyInstaller

🔗 **Repository & download: [github.com/abolfazl-mirolyae/blasphemous2-farsi](https://github.com/abolfazl-mirolyae/blasphemous2-farsi)**

A complete Persian (right-to-left) fan translation of the game *Blasphemous 2*, delivered as a one-click Windows installer that patches the game's asset bundles on the player's machine. It ships no game files.

<p>
  <img src="https://raw.githubusercontent.com/abolfazl-mirolyae/blasphemous2-farsi/main/docs/screenshots/05-weapon-memories-key-prompts.png" width="49%">
  <img src="https://raw.githubusercontent.com/abolfazl-mirolyae/blasphemous2-farsi/main/docs/screenshots/07-quest-item.png" width="49%">
</p>

**Key work:**
- Wrote a dependency-free Persian text engine: Arabic-script shaping (presentation forms, lam-alef ligatures, ZWNJ), a simplified Unicode Bidi algorithm and width-aware line breaking, so TextMeshPro (which has no RTL shaping) renders Persian correctly with inline keyboard/controller prompts
- Removed in-game stutter by pre-baking the font's SDF atlas offline (FreeType + distance transform, matching TextMeshPro's encoding) instead of rasterising glyphs at runtime
- Debugged the IL2CPP game through its own logs: traced frozen currency counters to an invalid .NET culture code, and measured real UI box widths from the prefabs' RectTransform hierarchy to stop broken line wrapping
- Rewrote 2,300+ strings of dialogue, lore and UI into natural, colloquial Persian with consistent terminology
- Installer: automatic game detection, backups, upgrade from older patches, uninstall; unit tests; verified in-game

---

## 🛠️ Skills & Experience

### Software Development
- PHP Web Development
- Custom Content Management Systems
- Business Process Automation
- Web Application Development
- Website Administration

### IT Support
- Technical Troubleshooting
- End-User Support
- Application and System Issue Resolution
- Support Ticket Management and Follow-up

### Digital Marketing
- Website Content Management
- Digital Content Creation
- Content Publishing and Administration
- Practical Experience with Digital Marketing Activities

---

## 💼 Professional Experience

### Herosun — Web Development, IT Support & Digital Marketing

**Duration:** Approximately 1 year and 1 month

My responsibilities have included:

- Developing and maintaining the company website
- Building a custom CMS
- Developing business automation bots
- Creating an organizational task management web application
- Providing technical support to employees
- Troubleshooting application and system issues
- Submitting and following up on support tickets with external software providers
- Managing website content and publishing digital content on company communication channels

This cross-functional experience has helped me understand both the technical side of software development and the practical needs of business operations.

---

## 🤝 Working With Me

I take on freelance projects end to end: websites and CMS dashboards, Telegram and Bale bots, and automation of repetitive business work.

- **Clear scope first:** a written estimate of features, timeline and cost before any work starts
- **Milestone delivery:** the project is split into phases, with a live preview at every step
- **Full handover:** complete source code, setup guide and a short walkthrough
- **Support:** 30 days of free bug fixes after delivery

---

*Thanks for visiting my portfolio!*
