# Adam Abutaleb · Personal Portfolio

**Live site → [adam-abutaleb.github.io/Personal-Portfolio-Website](https://adam-abutaleb.github.io/Personal-Portfolio-Website/)**

My personal portfolio. I'm a sophomore at Worcester State University studying Computer Science and Mathematics, and I'm looking for a **software engineering internship for Summer 2027**.

The site is themed around a swimming pool, because I teach swimming and work as a lifeguard. As you scroll you move from the shallow end to the deep end. Each section is a depth marker, lane ropes separate the sections, and a depth gauge on the side shows where you are.

![HTML](https://img.shields.io/badge/HTML-single%20file-e34f26)
![CSS](https://img.shields.io/badge/CSS-no%20framework-1572b6)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-f7df1e)
![Hosting](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-222)

---

## What's on the page

| Depth | Section | What it shows |
|---|---|---|
| 0.9 m | **Shallow end** | Intro, links, and an animated water surface drawn on a canvas |
| 1.2 m | **Swim lanes** | A timeline where each lane is a school, job or team, drawn as long as it lasted. Click a lane to jump to its details |
| 1.5 m | **Projects** | My two projects, each with a small working demo you can try |
| 1.8 m | **Training log** | Completed and current coursework |
| 2.1 m | **Results board** | GPA, Dean's List, promotions and certifications, laid out like a swim-meet scoreboard |
| 2.4 m | **Toolkit** | Skills. Pick one and a "heat sheet" lists where I've actually used it |
| 3.0 m | **Deep end** | Teaching, lifeguarding and racing |
| ↑ | **Exit ladder** | Contact info and résumé |

### Interactive pieces

- **Tic-Tac-Toe:** a playable browser version of my [Python terminal game](https://github.com/adam-abutaleb/TicTacToe), with the same win checks and taken-square handling.
- **Ratings matrix:** a small version of the trainer-rating logic from my [Fitness Center Management System](https://github.com/adam-abutaleb/fitness-center-management-project). It averages a members × trainers table and ranks the trainers. It uses sample data.
- **Ask Adam:** a chatbot in the corner that answers questions about me. It is **not** an AI model. It has about a dozen pre-written answers, picks one by matching keywords, and offers suggested questions. Anything it doesn't recognise gets a polite fallback that points to my email.
- **Depth gauge navigation:** a rail on the right that highlights the current section and fills like a water level as you scroll. On phones it becomes a bottom bar.
- **Light and dark themes:** follows your system setting. The dark one is a night swim.

---

## Built with

- **One `index.html` file:** HTML, CSS and vanilla JavaScript. No framework, no build step, no dependencies.
- **Canvas** for the moving water and **inline SVG** for the swim-lane timeline and illustrations.
- **Google Fonts:** Barlow Condensed, Figtree and JetBrains Mono.
- **GitHub Pages** for free hosting. Every push to `main` redeploys the site.

Accessibility: the page works with the keyboard, shows visible focus outlines, respects "reduce motion" settings, and adapts down to phone width.

---

## Project structure

```
.
├── index.html   # the whole site: markup, styles and scripts
├── resume.pdf   # my résumé, linked from the site
└── README.md
```

---

## Run it locally

No install needed. Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/adam-abutaleb/Personal-Portfolio-Website.git
cd Personal-Portfolio-Website
start index.html        # Windows  (macOS: open index.html)
```

---

## Updating the content

All the content lives in plain JavaScript lists near the bottom of `index.html`, so updating the site means editing data, not layout:

| List | Controls |
|---|---|
| `LANES` | Timeline lanes and their detail cards |
| `COURSES_DONE` / `COURSES_NOW` | Training log |
| `RESULTS` | Results board rows |
| `SKILLS` / `USES` | Toolkit and the heat sheet |
| `STROKES` | Deep-end tabs |
| `ANSWERS` / `FALLBACK` | The Ask Adam chatbot's questions, trigger words and replies |

To publish a change, commit and push to `main`. GitHub Pages updates the live site in about a minute.

---

## Contact

- **Email:** aabutaleb2007@gmail.com
- **LinkedIn:** [adam-a-372943383](https://www.linkedin.com/in/adam-a-372943383)
- **GitHub:** [adam-abutaleb](https://github.com/adam-abutaleb)
- **Résumé:** [resume.pdf](resume.pdf)
