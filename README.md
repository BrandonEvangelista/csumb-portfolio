# CSUMB ILP Portfolio — Brandon Evangelista

Individual Learning Plan portfolio for the CSUMB Computer Science Online program (cohort #22).
Static site, GitHub Pages ready. No build step.

## Structure

```
csumb-portfolio/
├── index.html              # Homepage: name, bio, program + outcomes, goals, nav to all 13 courses
├── README.md
└── courses/
    ├── cst-300.html        # Major ProSeminar
    ├── cst-338.html        # Software Design
    ├── cst-363.html        # Introduction to Database Systems
    ├── cst-334.html        # Operating Systems
    ├── cst-311.html        # Introduction to Computer Networks
    ├── cst-336.html        # Internet Programming
    ├── cst-370.html        # Design & Analysis of Algorithms
    ├── cst-462s.html       # Race, Gender, Class in the Digital World
    ├── cst-328.html        # Digital Art and Design
    ├── cst-315.html        # Introduction to Cybersecurity
    ├── cst-438.html        # Software Engineering
    ├── cst-329.html        # Reasoning with Logic
    └── cst-489-499.html    # Computer Science Capstone (MediTap)
```

Each course page has the three sections the rubric grades: **Course Description**, **What I Learned**, and **Evidence** (links to real work, or a ~100-word description where the work is private).

## How it maps to the rubric (25 pts)

- **Homepage (5):** name, bio, program description + program outcomes, goals, and a Courses list that links to every course page.
- **Course Pages (10):** 13 pages, each with a course description.
- **Course Evidence (10):** each page links a final project / major assignment, or gives a ~100-word description of the work.

## Still to do before submitting

- [ ] **CST 300** — add the two AI Companionship YouTube URLs, and commit the ethics paper to `courses/assets/ethics_evangelista.pdf` (create the `assets/` folder). Then update the `href`s on `cst-300.html`.
- [x] **CST 462S** — service learning filled in: LibreOffice (The Document Foundation), 40 hours.
- [ ] **CST 336** — decide whether to make the repos public (quotefinder, hw1Express, renderRepo) or keep the "code on request" note.
- [ ] **Confirm two claims** — GymLog as a real Android app (CST 338) and the Render deployment (CST 336).
- [ ] **Course descriptions** are paraphrased. If an instructor wants exact wording, paste the official CSUMB catalog text into each "Course Description" block.
- [ ] **CST 329 / Capstone** — update as those courses finish.
- [ ] Optional: add screenshots of real work to each page.

## Publishing to GitHub Pages

From this folder:

```bash
cd /Users/snorlax.sys/Desktop/lab1/csumb-portfolio
git init
git add .
git commit -m "Rebuild ILP portfolio: homepage + 13 course pages"
git branch -M main
git remote add origin https://github.com/BrandonEvangelista/csumb-portfolio.git
git push -u origin main --force
```

> `--force` overwrites the old single-page version. If you'd rather keep history, pull first instead.

Then on GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / root**.
Your site will be at `https://brandonevangelista.github.io/csumb-portfolio/`.
