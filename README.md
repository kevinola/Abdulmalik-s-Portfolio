# Abdulmalik's Portfolio: The Investigation Bag

An interactive portfolio where each section is a document inside an investigation bag. Open the bag, pick a file, and read it.

**Live site:** https://kevinola.github.io/YOUR-REPO/  <!-- replace after hosting -->

---

## The idea behind the design

I was inspired by a graphic design portfolio that showed the designer's abilities as documents arranged inside an investigation bag. I was looking for a job and building a portfolio to help me find one, so I took that idea and made it my own. Each page is a document: one about me, one about my experience, one for my projects, one for my skills, and one for contact details. The visitor opens the bag and goes through the files one by one.

## What I want visitors to take away

I want visitors to see that you can build almost anything with the web. A website no longer has to be a plain, professional page. It can also be creative, with motion, personality and a strong interface. Web development is moving that way, toward experiences that are captivating, visual and easier for people to understand and interact with, and this portfolio shows that I'm up to date with that direction.

## Features

- **Interactive bag:** documents sit in the bag; tap one to bring it into focus, tap again to read it in full.
- **Five documents:** About, Projects, Experience, Skills and Contact.
- **Guided first-visit tutorial:** a dark spotlight and animated hands teach the three moves (open a document, read it, go back). A **?** button replays it at any time, and it can be skipped.
- **Tooltips:** on hover, keyboard focus, and touch long-press. They stay off while the tutorial is running.
- **Navigation:** bottom nav to jump between documents, an **X** to zoom back out to the whole bag, and support for the browser Back button and the Escape key.
- **Mobile friendly:** designed to work on phones as well as desktop.

## How it's built

The whole portfolio is one HTML file with hand-written CSS and vanilla JavaScript. There is no framework, no build step and nothing to install. The project screenshot is embedded in the file, so it can be opened locally or hosted as it is.

- **Layout and motion:** CSS transforms and transitions place the documents in the bag and zoom into each one.
- **Interaction:** JavaScript handles the focus, expand and return logic.
- **External resources:** Font Awesome icons and the Inter typeface load from a CDN, so an internet connection is needed for them.
- **Built with AI assistance:** the concept, direction and decisions are mine, and AI tools helped with the implementation.

## Projects featured

| Project | What it is | Stack |
| --- | --- | --- |
| **Calculator** | A simple calculator built to learn JavaScript | HTML, CSS, JavaScript |
| **CivilReport** | A mobile app for reporting incidents, with photos, location and a live feed | Cordova, JavaScript, WordPress REST API, JWT |
| **Blog App** | A mobile-friendly blog app backed by WordPress | Cordova, JavaScript, WordPress, MySQL |
| **Manga App** | A manga-reading app *(details coming soon)* | |

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

## Credits

- **Design inspiration:** a graphic design portfolio by **[ORIGINAL DESIGNER'S NAME / LINK]**, which showed documents arranged in an investigation bag. This project is my own interactive interpretation of that idea, and all code is my own.
- **Icons:** [Font Awesome](https://fontawesome.com)
- **Typeface:** [Inter](https://rsms.me/inter/) via Google Fonts

## Contact

Find my details in the Contact document inside the portfolio.
