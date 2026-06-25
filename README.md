# Ayush Joshi — Resume (HTML)

A personal resume built using **semantic HTML only** — no CSS, no frameworks.  
Structured for future styling with a two-column layout (`<aside>` + `<main>`).

---

## Structure

```
<article>              → entire resume
  <aside>              → left column (contact, skills, certifications, coursework)
  <main>               → right column (header, education, projects)
    <header>           → name + tagline + links
    <section>          → education
    <section>          → projects
      <article>        → each individual project
```

---

## Semantic Tags Used

| Tag | Purpose |
|---|---|
| `<article>` | Entire resume as a self-contained document |
| `<aside>` | Left sidebar — supporting info |
| `<main>` | Primary content — education & projects |
| `<header>` | Page top + inside each project |
| `<section>` | Thematic groups (skills, education, projects) |
| `<address>` | Contact info (location, GitHub, LinkedIn) |
| `<time>` | All dates with `datetime` attribute |
| `<em>` | Tech stack labels inside projects |
| `<strong>` | Degree name emphasis |

---

## How to Run

1. Clone or download this repo
2. Open `resume.html` in any browser

No build step. No dependencies. Just HTML.

---

## ScreenShots
![Resume](RESUMEHTML.png)
---
## Author

**Ayush Joshi**  
B.Tech CSE · Amrapali University · Haldwani, Uttarakhand  
GitHub: [AyushThinks](https://github.com/AyushThinks)  
LinkedIn: [ayush-joshi](https://www.linkedin.com/in/ayush-joshi-4a4316367/)