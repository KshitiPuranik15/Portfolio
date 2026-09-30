# Kshiti Puranik | Developer Portfolio

A fast, single-file personal portfolio for a Computer Engineering student focused on machine learning and web development. It has a deep-plum design with a pink-to-amber accent, smooth interactions, and a light/dark theme toggle.

🔗 **Live site:** `ADD-YOUR-DEPLOYED-URL-HERE`

---

## ✨ Highlights

- **Single-file build:** HTML, CSS, JavaScript and the profile photo all live in one file, so there is no build step and no dependencies to install.
- **Dark / light theme:** a toggle in the nav, with your choice remembered between visits.
- **Interactive touches:** a cursor-following glow, a typing animation that cycles through roles, and scroll-triggered reveal animations.
- **Live data visual:** the featured project includes a confusion-matrix heatmap drawn from the model's real test results.
- **Distinct typography:** Syne for headings, Instrument Serif for body text, and JetBrains Mono for labels.
- **Responsive:** the layout adapts to mobile screens.

## 🧭 Sections

| Section | What's in it |
|---|---|
| **About** | Intro, availability badge, profile photo, and CGPA highlight |
| **Project** | MindCheck, with metrics and a confusion matrix heatmap |
| **Skills** | Languages, backend and ML tools, core CS, and dev tools |
| **Journey** | Education, ACM leadership role, and IBM SkillsBuild certifications |
| **Contact** | Email, phone, and LinkedIn |

## 🚀 Featured Project: MindCheck

An AI-assisted mental wellness screening app for students. It has a chat-style 10-question check-in, a Flask REST API serving a scikit-learn classifier, lexicon-based sentiment analysis on free-text notes, and a safety layer for urgent language. Logistic Regression was selected over Random Forest, reaching **68.3% accuracy** and **0.68 macro-F1** on a held-out test set.

It was trained on a synthetic demonstration dataset and is not clinically validated.

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| Markup & styling | HTML5, CSS3 (custom properties for theming, CSS grid) |
| Scripting | Vanilla JavaScript (IntersectionObserver, localStorage) |
| Fonts | Google Fonts: Syne, Instrument Serif, JetBrains Mono |

## 💻 Run Locally

No install needed. Clone the repo and open the file:

```bash
git clone https://github.com/USERNAME/REPO-NAME.git
cd REPO-NAME
```

Then open `index.html` in your browser, or serve it locally:

```bash
python -m http.server 8000
# visit http://localhost:8000
```

## 🎨 Customizing

- **Colors:** change the CSS variables at the top of the `<style>` block (`--accent`, `--accent2`, `--bg`, and so on). The light theme has its own set of values.
- **Typing roles:** edit the `roles` array in the script at the bottom of the file.
- **Photo:** the profile photo is embedded in the HTML. To swap it, replace the `src` of the `<img>` in the hero section with a file path or a new image.
- **GitHub link:** add your GitHub button in the Contact section (there is a commented example).
- **New projects:** duplicate the `.proj` block in the Project section and edit the content.

## ☁️ Deployment

Because it is a static site, it deploys anywhere with no configuration:

- **GitHub Pages:** rename the file to `index.html`, then go to *Settings → Pages*, choose the `main` branch, and save.
- **Vercel / Netlify:** import the repo and deploy, with no build command needed.

## 📬 Connect

- LinkedIn: [kshiti-puranik](https://www.linkedin.com/in/kshiti-puranik-2554a0376/)
- Email: puranik.kshiti@gmail.com

---

© 2026 Kshiti Puranik. Feel free to take inspiration from the layout, but please don't copy the content or personal details.
