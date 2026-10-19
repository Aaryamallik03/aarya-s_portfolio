# Aarya's Virtual World

An interactive portfolio site. Instead of a plain resume page, visitors dig through rocks in a little pickaxe game to unlock my projects, resume, experience and certificates, or skip straight to a scrolling 3D-style story of my work.

**Live site:** https://aaryamallik03.github.io/aarya-s_portfolio/

## About me

Hi, I'm Aarya, a computer science student at NIT Meghalaya. I build machine learning, computer vision and security systems, with a little sunshine in every project.

**Skills:** Python · PyTorch · FastAPI · Cybersecurity · React · MongoDB

## What's inside

- **Dig game:** click the rocks to uncover hidden items. A tracker keeps count of what you've found (projects, resume, experience, certificates) along with your XP and level.
- **Story mode:** a scroll-through tour of my work with sections for Start, Work, GitHub, Experience, Resume, Badges and Contact.
- **Floating skill chips:** draggable skill tags in the hero section.
- **Downloads and contact:** resume and CV downloads, a GitHub link, and a contact form.
- **Responsive:** works on desktop and phone.

## Tech

- Plain HTML, CSS and JavaScript in a single self-contained `index.html`, with no build step and no framework
- [Three.js](https://threejs.org/) (r128) and GLTFLoader for the 3D avatar and background effects
- Google Fonts: Inter, Anton and Fraunces
- Images, video and PDFs are embedded in the file, so there are no extra assets to host

## Run it locally

Just open the file in a browser:

```bash
git clone https://github.com/Aaryamallik03/digital-resume.git
cd digital-resume
# then open index.html in your browser
```

An internet connection is needed for the fonts and Three.js, which load from a CDN.

## Deploy

The site is hosted on GitHub Pages:

1. Push `index.html` to the `main` branch.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, then `main` and `/ (root)`.
3. The site appears at `https://<username>.github.io/digital-resume/` after a minute or two.

It also works on Netlify or Vercel with no build command, by importing the repo.

## Project structure

```
digital-resume/
├── index.html   # the whole site: markup, styles, scripts and embedded assets
└── README.md
```

## Contact

- GitHub: [@Aaryamallik03](https://github.com/Aaryamallik03)
